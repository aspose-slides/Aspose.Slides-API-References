---
title: get_RawFrame()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a nyers alakzatkeret tulajdonságait. Olvassa el az IShapeFrame-et.
type: docs
weight: 40
url: /hu/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() metódus

Visszaadja a nyers alakzatkeret tulajdonságait. Olvassa el [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## Megjegyzések

Az a kód, amely megpróbál egy nem definiált keretet hozzárendelni a [IShape::set_Frame](../../ishape/set_frame/)-hez, általános esetben nem értelmezhető (különösen abban az esetben, amikor a szülő [GroupShape](../../groupshape/) többszörösen beágyazott más GroupShape-ekbe). Például: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 vagy 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
Az ilyen kód félreérthető helyzetekhez vezethet. Ezért korlátozások kerültek bevezetésre a [IShape::set_Frame](../../ishape/set_frame/)-hez nem definiált értékek használatára. Az x, y, width, height, flipH, flipV és rotationAngle értékeknek definiáltnak kell lenniük (nem std::numeric_limits<float>::quiet_NaN() vagy [NullableBool::NotDefined](../../nullablebool/)). A fenti példakód most ArgumentException kivételt dob. Ez az alábbi esetekre vonatkozik: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // nem lehet meghatározatlan

SharedPtr<IShapeCollection> shapes = ...;
// az x, y, width, height paraméterek nem lehetnek std::numeric_limits<float>::quiet_NaN():
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

Azonban a [IShape::set_RawFrame](../../ishape/set_rawframe/) metódus kerete lehet nem definiált. Ez akkor értelmes, ha az alakzat egy helytartóhoz van kapcsolva. Ebben az esetben a nem definiált alakzatkeret értékeket a szülő helytartó alakzat felülírja. Ha nincs szülő helytartó alakzat az adott alakzathoz, akkor az alakzat alapértelmezett értékeket használ, amikor a [IShape::get_RawFrame](../../ishape/get_rawframe/) alapján a hatékony keretet számítja ki. Az alapértelmezett értékek 0 és [NullableBool::False](../../nullablebool/) az x, y, width, height, flipH, flipV és rotationAngle esetén. Például: 
```cpp
SharedPtr<IShape> shape = ...; // az alakzat a helytartóhoz van kapcsolva
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // most az alakzat örökli az x, y, height, flipH, flipV értékeket a helytartótól, és felülírja a width=100 és a rotationAngle=0 értékeket.
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IShapeFrame](../../ishapeframe/)
* Osztály [Shape](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)