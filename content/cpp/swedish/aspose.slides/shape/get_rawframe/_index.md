---
title: get_RawFrame()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar den råa formramens egenskaper. Läs IShapeFrame.
type: docs
weight: 40
url: /sv/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() metod


Returnerar den råa formramens egenskaper. Läs [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
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
 Sådan kod kan leda till oklara situationer. Så har restriktioner lagts till för att använda odefinierade värden för [IShape::set_Frame](../../ishape/set_frame/). Värdena för x, y, width, height, flipH, flipV och rotationAngle måste vara definierade (inte std::numeric_limits<float>::quiet_NaN() eller [NullableBool::NotDefined](../../nullablebool/)). Exempelkoden ovan kastar nu ett ArgumentException-undantag. Detta gäller för följande användningsfall: 
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


Men en ram för [IShape::set_RawFrame](../../ishape/set_rawframe/)-metoden kan vara odefinierad. Detta är meningsfullt när en form är länkad till en platshållare. Då ersätts de odefinierade ramvärdena av det föräldra-platshållarformen. Om det inte finns någon föräldra-platshållarform för den formen använder formen standardvärden när den beräknar den effektiva ramen baserat på dess [IShape::get_RawFrame](../../ishape/get_rawframe/). Standardvärdena är 0 och [NullableBool::False](../../nullablebool/) för x, y, width, height, flipH, flipV och rotationAngle. Till exempel: 
```cpp
SharedPtr<IShape> shape = ...; // shape är länkad till platshållare
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // nu shape ärver x, y, height, flipH, flipV värden från platshållaren och överskriver width=100 och rotationAngle=0.
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IShapeFrame](../../ishapeframe/)
* Klass [Shape](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)