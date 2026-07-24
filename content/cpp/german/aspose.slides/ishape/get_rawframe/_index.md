---
title: get_RawFrame()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt die Eigenschaften des rohen Formrahmens zurück. Lesen Sie IShapeFrame.
type: docs
weight: 40
url: /de/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() Methode

Gibt die Eigenschaften des rohen Formrahmens zurück. Lesen [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Hinweise

Code, der versucht, einen undefinierten Rahmen [IShape::set_Frame](../set_frame/) zuzuweisen, ergibt im allgemeinen Fall keinen Sinn (insbesondere im Fall, wenn das übergeordnete [GroupShape](../../groupshape/) mehrfach in andere GroupShape-s eingebettet ist). Zum Beispiel: 
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
 Solcher Code kann zu unklaren Situationen führen. Daher wurden Einschränkungen für die Verwendung undefinierter Werte für [IShape::set_Frame](../set_frame/) hinzugefügt. Werte von x, y, width, height, flipH, flipV und rotationAngle müssen definiert sein (nicht std::numeric_limits<float>::quiet_NaN() oder [NullableBool::NotDefined](../../nullablebool/)). Der obige Beispielcode wirft jetzt eine ArgumentException-Ausnahme. Dies gilt für die folgenden Anwendungsfälle: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // darf nicht undefiniert sein

SharedPtr<IShapeCollection> shapes = ...;
// x, y, width, height Parameter dürfen nicht std::numeric_limits<float>::quiet_NaN() sein:
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

Aber ein Rahmen für die [IShape::set_RawFrame](../set_rawframe/) Methode kann undefiniert sein. Das ergibt Sinn, wenn die Form mit einem Platzhalter verknüpft ist. Dann werden die undefinierten Rahmenwerte der Form vom übergeordneten Platzhalter überschrieben. Wenn es keinen übergeordneten Platzhalter für diese Form gibt, verwendet die Form Standardwerte, wenn sie den effektiven Rahmen basierend auf ihrem [IShape::get_RawFrame](./) auswertet. Standardwerte sind 0 und [NullableBool::False](../../nullablebool/) für x, y, width, height, flipH, flipV und rotationAngle. Zum Beispiel: 
```cpp
SharedPtr<IShape> shape = ...; // shape ist mit Platzhalter verknüpft
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // jetzt erbt shape x, y, height, flipH, flipV Werte vom Platzhalter und überschreibt width=100 und rotationAngle=0.
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShapeFrame](../../ishapeframe/)
* Klasse [IShape](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)