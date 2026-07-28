---
title: set_RawFrame()
second_title: Aspose.Slides C++ API referencia
description: Beállítja a nyers alakkeret tulajdonságait. Írja IShapeFrame.
type: docs
weight: 53
url: /hu/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) method

Beállítja a nyers alakkeret tulajdonságait. Írja [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## Megjegyzés

Az a kód, amely megpróbál egy meghatározatlan keretet hozzárendelni a [IShape::set_Frame](../set_frame/)-hez, általános esetben nem értelmezhető (különösen abban az esetben, amikor a szülő [GroupShape](../../groupshape/) több szinten be van ágyazva más GroupShape-okba). Például:
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
Az ilyen kód bizonytalan helyzetekhez vezethet. Ezért korlátozások kerültek bevezetésre a [IShape::set_Frame](../set_frame/) számára meghatározatlan értékek használatára. Az x, y, width, height, flipH, flipV és rotationAngle értékeket meg kell adni (nem std::numeric_limits<float>::quiet_NaN() vagy [NullableBool::NotDefined](../../nullablebool/)). A fenti példakód most ArgumentException kivételt dob. Ez az alábbi felhasználási esetekre vonatkozik:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // nem lehet meghatározatlan

SharedPtr<IShapeCollection> shapes = ...;
// x, y, width, height paraméterek nem lehetnek std::numeric_limits<float>::quiet_NaN():
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

Azonban a [IShape::set_RawFrame](./) metódus kerete lehet meghatározatlan. Ez akkor értelmezhető, ha az alakzat egy helyfoglalóhoz van kapcsolva. Ekkor a meghatározatlan alakkeret értékeket a szülő helyfoglaló alakzat felülírja. Ha nincs szülő helyfoglaló alakzat az adott alakzat számára, akkor az alakzat az alapértelmezett értékeket használja, amikor a [IShape::get_RawFrame](../get_rawframe/) alapján kiszámítja a tényleges keretet. Az alapértelmezett értékek 0 és [NullableBool::False](../../nullablebool/) az x, y, width, height, flipH, flipV és rotationAngle esetén. Például:
```cpp
SharedPtr<IShape> shape = ...; // shape a helyfoglalóhoz van kapcsolva
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // most shape örökli az x, y, height, flipH, flipV értékeket a placeholder-ből, és felülírja a width=100 és rotationAngle=0 értékeket.
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IShapeFrame](../../ishapeframe/)
* Osztály [IShape](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)