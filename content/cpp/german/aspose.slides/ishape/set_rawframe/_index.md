---
title: set_RawFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Eigenschaften des rohen Shape-Frames. Schreiben IShapeFrame.
type: docs
weight: 53
url: /de/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) Methode


Setzt die Eigenschaften des rohen Shape-Frames. Schreiben [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## Hinweise


Code, der versucht, einen undefinierten Frame an [IShape::set_Frame](../set_frame/) zuzuweisen, ergibt im allgemeinen Fall keinen Sinn (insbesondere im Fall, wenn das übergeordnete [GroupShape](../../groupshape/) mehrfach in andere GroupShape-s eingebettet ist). Zum Beispiel: 
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
 Ein solcher Code kann zu unklaren Situationen führen. Daher wurden Beschränkungen für die Verwendung undefinierter Werte für [IShape::set_Frame](../set_frame/) hinzugefügt. Werte von x, y, width, height, flipH, flipV und rotationAngle müssen definiert sein (nicht std::numeric_limits<float>::quiet_NaN() oder [NullableBool::NotDefined](../../nullablebool/)). Der obige Beispielcode wirft jetzt eine ArgumentException aus. Dies gilt für die folgenden Anwendungsfälle: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // kann nicht undefiniert sein

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


Ein Frame für die Methode [IShape::set_RawFrame](./) kann jedoch undefiniert sein. Das ist sinnvoll, wenn das Shape mit einem Platzhalter verknüpft ist. Dann werden die undefinierten Shape-Frame-Werte vom übergeordneten Platzhalter-Shape überschrieben. Wenn es für dieses Shape keinen übergeordneten Platzhalter-Shape gibt, verwendet das Shape Standardwerte, wenn es den effektiven Frame basierend auf seinem [IShape::get_RawFrame](../get_rawframe/) evaluiert. Standardwerte sind 0 und [NullableBool::False](../../nullablebool/) für x, y, width, height, flipH, flipV und rotationAngle. Zum Beispiel: 
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