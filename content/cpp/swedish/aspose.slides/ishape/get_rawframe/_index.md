---
title: get_RawFrame()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar egenskaperna för den råa formens ram. Läs IShapeFrame.
type: docs
weight: 40
url: /sv/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() metod

Returnerar egenskaperna för den råa formens ram. Läs [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Anmärkningar

Kod som försöker tilldela en odefinierad ram till [IShape::set_Frame](../set_frame/) är inte meningsfull i allmänna fallet (särskilt när föräldern [GroupShape](../../groupshape/) är flera gånger inbäddad i andra GroupShape-s). Till exempel: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 eller 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 Sådan kod kan leda till oklara situationer. Så har restriktioner lagts till för att använda odefinierade värden för [IShape::set_Frame](../set_frame/). Värdena för x, y, width, height, flipH, flipV och rotationAngle måste vara definierade (inte std::numeric_limits<float>::quiet_NaN() eller [NullableBool::NotDefined](../../nullablebool/)). Exempelkoden ovan kastar nu ett ArgumentException-undantag. Detta gäller för följande användningsfall: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // kan inte vara odefinierad

SharedPtr<IShapeCollection> shapes = ...;
// x, y, width, height-parametrar kan inte vara std::numeric_limits<float>::quiet_NaN():
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

Men en ram för [IShape::set_RawFrame](../set_rawframe/)-metoden kan vara odefinierad. Detta är meningsfullt när formen är länkad till en platshållare. Då åsidosätts de odefinierade ramvärdena av förälderns platshållarform. Om det inte finns någon föräldraplatshållarform för den formen så använder den formen standardvärden när den beräknar den effektiva ramen baserat på dess [IShape::get_RawFrame](./). Standardvärdena är 0 och [NullableBool::False](../../nullablebool/) för x, y, width, height, flipH, flipV och rotationAngle. Till exempel: 
```cpp
SharedPtr<IShape> shape = ...; // formen är länkad till en platshållare
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // nu är formen ärver x, y, height, flipH, flipV-värden från platshållaren och åsidosätter width=100 och rotationAngle=0.
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IShapeFrame](../../ishapeframe/)
* Klass [IShape](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)