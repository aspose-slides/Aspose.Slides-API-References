---
title: set_RawFrame()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in egenskaperna för den råa formramen. Skriv IShapeFrame.
type: docs
weight: 53
url: /sv/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) metod

Ställer in egenskaperna för den råa formens ram. Skriv [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## Anmärkningar

Kod som försöker tilldela en odefinierad ram till [IShape::set_Frame](../../ishape/set_frame/) är inte meningsfull i allmänna fallet (särskilt när föräldern [GroupShape](../../groupshape/) är flera gånger inbäddad i andra GroupShape-s). Till exempel: 
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
 Sådan kod kan leda till oklara situationer. Därför har begränsningar lagts till för användning av odefinierade värden för [IShape::set_Frame](../../ishape/set_frame/). Värdena för x, y, width, height, flipH, flipV och rotationAngle måste vara definierade (inte std::numeric_limits<float>::quiet_NaN() eller [NullableBool::NotDefined](../../nullablebool/)). Exempelkoden ovan kastar nu ett ArgumentException-undantag. Detta gäller för följande användningsfall: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // kan inte vara odefinierad

SharedPtr<IShapeCollection> shapes = ...;
// x, y, width, height parametrar kan inte vara std::numeric_limits<float>::quiet_NaN():
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

Men en ram för [IShape::set_RawFrame](../../ishape/set_rawframe/) metod kan vara odefinierad. Detta är meningsfullt när en form är länkad till en platshållare. Då åsidosätts de odefinierade ramvärdena för formen från förälderns platshållarform. Om det inte finns någon föräldraplatshållarform för den formen så använder den formen standardvärden när den beräknar den faktiska ramen baserat på sitt [IShape::get_RawFrame](../../ishape/get_rawframe/). Standardvärden är 0 och [NullableBool::False](../../nullablebool/) för x, y, width, height, flipH, flipV och rotationAngle. Till exempel: 
```cpp
SharedPtr<IShape> shape = ...; // formen är länkad till en platshållare
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // nu ärver formen x, y, height, flipH, flipV värden från platshållaren och åsidosätter width=100 och rotationAngle=0.
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShapeFrame](../../ishapeframe/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)