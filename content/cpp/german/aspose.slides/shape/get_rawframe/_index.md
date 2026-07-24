---
title: get_RawFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Eigenschaften des rohen Formenrahmens zurück. Lesen Sie IShapeFrame.
type: docs
weight: 40
url: /de/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() Methode

Gibt die Eigenschaften des rohen Formenrahmens zurück. Lesen Sie [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## Anmerkungen

Code, der versucht, einem [IShape::set_Frame](../../ishape/set_frame/) einen undefinierten Rahmen zuzuweisen, ergibt im Allgemeinen keinen Sinn (insbesondere im Fall, dass das übergeordnete [GroupShape](../../groupshape/) mehrfach in andere GroupShape-s verschachtelt ist). Zum Beispiel: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 oder 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 Ein solcher Code kann zu unklaren Situationen führen. Daher wurden Einschränkungen für die Verwendung undefinierter Werte bei [IShape::set_Frame](../../ishape/set_frame/) hinzugefügt. Werte von x, y, width, height, flipH, flipV und rotationAngle müssen definiert sein (nicht std::numeric_limits<float>::quiet_NaN() oder [NullableBool::NotDefined](../../nullablebool/)). Der obige Beispielcode wirft nun eine ArgumentException-Ausnahme. Dies gilt für die folgenden Anwendungsfälle: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // darf nicht undefiniert sein

SharedPtr<IShapeCollection> shapes = ...;
// x-, y-, width- und height-Parameter dürfen nicht std::numeric_limits<float>::quiet_NaN() sein:
{
    shapes->AddAudioFrameCD(...);
    shapes->AddAudioFrameEmbedded(...);
    shapes->AddAudioFrameLinked(...);
    shapes->AddAutoShape(...);
    shapes->AddChart(...);
    shapes->AddConnector(...);
    shapes->AddOleObjectFrame(...);
    shapes->AddPictureFrame(...);
    shapes->AddSmartArt(...);
    shapes->AddTable(...);
    shapes->AddVideoFrame(...);
    shapes->InsertAudioFrameEmbedded(...);
    shapes->InsertAudioFrameLinked(...);
    shapes->InsertAutoShape(...);
    shapes->InsertChart(...);
    shapes->InsertConnector(...);
    shapes->InsertOleObjectFrame(...);
    shapes->InsertPictureFrame(...);
    shapes->InsertTable(...);
    shapes->InsertVideoFrame(...);
}
```

Ein Rahmen für die Methode [IShape::set_RawFrame](../../ishape/set_rawframe/) kann jedoch undefiniert sein. Das ergibt Sinn, wenn die Form mit einem Platzhalter verknüpft ist. Dann werden die undefinierten Rahmenwerte der Form vom übergeordneten Platzhalterform überschrieben. Wenn es für diese Form keinen übergeordneten Platzhalter gibt, verwendet die Form Standardwerte, wenn sie den effektiven Rahmen basierend auf ihrem [IShape::get_RawFrame](../../ishape/get_rawframe/) auswertet. Standardwerte sind 0 und [NullableBool::False](../../nullablebool/) für x, y, width, height, flipH, flipV und rotationAngle. Zum Beispiel: 
```cpp
SharedPtr<IShape> shape = ...; // shape ist mit Platzhalter verknüpft
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // Jetzt shape erbt die x-, y-, height-, flipH- und flipV-Werte vom Platzhalter und überschreibt width=100 und rotationAngle=0.
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShapeFrame](../../ishapeframe/)
* Klasse [Shape](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)