---
title: get_RawFrame()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a nyers alakkeret tulajdonságait. Olvassa el IShapeFrame.
type: docs
weight: 40
url: /hu/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() metódus


Visszaadja a nyers alakkeret tulajdonságait. Olvassa el [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Megjegyzések


Az a kód, amely megpróbál meghatározatlan keretet hozzárendelni a [IShape::set_Frame](../set_frame/)-hez, általában nem értelmezhető (különösen akkor, amikor a szülő [GroupShape](../../groupshape/) több szintben be van ágyazva más GroupShape-ökbe). Például: 
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
Az ilyen kód homályos helyzeteket eredményezhet. Ezért korlátozások lettek bevezetve a [IShape::set_Frame](../set_frame/) számára meghatározatlan értékek használatára. Az x, y, width, height, flipH, flipV és rotationAngle értékeket definiálni kell (nem std::numeric_limits<float>::quiet_NaN() vagy [NullableBool::NotDefined](../../nullablebool/)). A fenti példa most ArgumentException kivételt dob. Ez a következő esetekre vonatkozik: 
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


De egy [IShape::set_RawFrame](../set_rawframe/) metódus kerete lehet meghatározatlan. Ez akkor értelmes, ha az alakzat egy helyőrzőhöz van kapcsolva. Ekkor a meghatározatlan alakkeret értékeket a szülő helyőrző alakzat felülírja. Ha nincs szülő helyőrző alakzat az adott alakzathoz, akkor az alakzat az alapértelmezett értékeket használja, amikor a [IShape::get_RawFrame](./) alapján értékeli a hatékony keretet. Az alapértelmezett értékek 0 és [NullableBool::False](../../nullablebool/) a x, y, width, height, flipH, flipV és rotationAngle esetén. Például: 
```cpp
SharedPtr<IShape> shape = ...; // az alakzat a helyőrzőhöz van kapcsolva
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // most az alakzat örökli az x, y, height, flipH, flipV értékeket a helyőrzőtől, és felülírja a width=100 és a rotationAngle=0 értékeket.
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IShapeFrame](../../ishapeframe/)
* Osztály [IShape](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)