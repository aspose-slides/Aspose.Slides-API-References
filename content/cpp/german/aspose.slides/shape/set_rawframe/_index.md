---
title: set_RawFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Eigenschaften des rohen Shape-Frames. Schreiben Sie IShapeFrame.
type: docs
weight: 53
url: /de/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) Methode

Setzt die Eigenschaften des rohen Shape-Frames. Schreiben Sie [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## Hinweise

Code, der versucht, einen undefinierten Frame zu [IShape::set_Frame](../../ishape/set_frame/) zuzuweisen, ergibt im Allgemeinen keinen Sinn (insbesondere im Fall, dass das übergeordnete [GroupShape](../../groupshape/) mehrfach in andere GroupShape-s verschachtelt ist). Zum Beispiel: 
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
 Solcher Code kann zu unklaren Situationen führen. Daher wurden Einschränkungen für die Verwendung undefinierter Werte für [IShape::set_Frame](../../ishape/set_frame/) hinzugefügt. Werte von x, y, width, height, flipH, flipV und rotationAngle müssen definiert sein (nicht std::numeric_limits<float>::quiet_NaN() oder [NullableBool::NotDefined](../../nullablebool/)). Der obige Beispielcode wirft jetzt eine ArgumentException-Ausnahme. Dies gilt für folgende Anwendungsfälle: 
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

Aber ein Frame für die [IShape::set_RawFrame](../../ishape/set_rawframe/)-Methode kann undefiniert sein. Das ist sinnvoll, wenn das Shape mit einem Platzhalter verknüpft ist. Dann werden undefinierte Shape-Frame-Werte vom übergeordneten Platzhalter-Shape überschrieben. Gibt es keinen übergeordneten Platzhalter-Shape für dieses Shape, verwendet das Shape Standardwerte, wenn es den effektiven Frame basierend auf seinem [IShape::get_RawFrame](../../ishape/get_rawframe/) auswertet. Standardwerte sind 0 und [NullableBool::False](../../nullablebool/) für x, y, width, height, flipH, flipV und rotationAngle. Zum Beispiel: 
```cpp
SharedPtr<IShape> shape = ...; // shape ist mit Platzhalter verknüpft
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // jetzt erbt shape die Werte x, y, height, flipH, flipV vom Platzhalter und überschreibt width=100 und rotationAngle=0.
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShapeFrame](../../ishapeframe/)
* Klasse [Shape](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)