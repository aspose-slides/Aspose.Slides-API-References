---
title: set_RawFrame()
second_title: Aspose.Slides C++ API Referenciája
description: Beállítja a nyers alakzatkeret tulajdonságait. Írja IShapeFrame.
type: docs
weight: 53
url: /hu/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) metódus


Beállítja a nyers alakzat keret tulajdonságait. Írja [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## Megjegyzések


Az a kód, amely megpróbál nem definiált keretet hozzárendelni a [IShape::set_Frame](../../ishape/set_frame/)-hez, általános esetben nem értelmezhető (különösen akkor, ha a szülő [GroupShape](../../groupshape/) több szinttel be van ágyazva más GroupShape-okba). Például: 
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
Az ilyen kód bizonytalan helyzetekhez vezethet. Ezért korlátozások lettek bevezetve az [IShape::set_Frame](../../ishape/set_frame/) esetén nem definiált értékek használatára. Az x, y, width, height, flipH, flipV és rotationAngle értékeknek definiáltnak kell lenniük (nem std::numeric_limits<float>::quiet_NaN() vagy [NullableBool::NotDefined](../../nullablebool/)). A fenti példakód most ArgumentException kivételt dob. Ez az alábbi felhasználási esetekre vonatkozik: 
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


De egy keret a [IShape::set_RawFrame](../../ishape/set_rawframe/) metódushoz lehet nem definiált. Ez akkor értelmes, ha az alakzat egy helyőrzőhöz van kapcsolva. Ebben az esetben a nem definiált alakzatkeret értékeket a szülő helyőrző alakzat felülírja. Ha nincs szülő helyőrző alakzat az adott alakzathoz, akkor az alakzat az alapértelmezett értékeket használja, amikor a [IShape::get_RawFrame](../../ishape/get_rawframe/) alapján a tényleges keretet számítja ki. Az alapértelmezett értékek 0 és [NullableBool::False](../../nullablebool/) az x, y, width, height, flipH, flipV és rotationAngle esetén. Például: 
```cpp
SharedPtr<IShape> shape = ...; // shape a helyőrzőhöz van kapcsolva
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // most shape örökli az x, y, height, flipH, flipV értékeket a helyőrzőtől, és felülírja a width=100 és rotationAngle=0 értékeket.
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IShapeFrame](../../ishapeframe/)
* Osztály [Shape](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)