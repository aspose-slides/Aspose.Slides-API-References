---
title: GetEffective()
second_title: Aspose.Slides for C++ API referenciája
description: Lekéri a hatékony 3-D formázási adatokat az öröklődés alkalmazásával.
type: docs
weight: 183
url: /hu/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() metódus

Lekéri a hatékony 3-D formázási adatokat az öröklődés alkalmazásával.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```

### Visszatérési érték

A [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).

## Megjegyzések

Ez a példa bemutatja, hogyan lehet lekérni a kamera, a fényrendszer és a forma felső rézszerkezetének hatékony tulajdonságait.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto threeDEffectiveData = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_ThreeDFormat()->GetEffective();

Console::WriteLine(u"= Effective camera properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_Camera()->get_CameraType()));
Console::WriteLine(String(u"Field of view: ") + threeDEffectiveData->get_Camera()->get_FieldOfViewAngle());
Console::WriteLine(String(u"Zoom: ") + threeDEffectiveData->get_Camera()->get_Zoom());

Console::WriteLine(u"= Effective light rig properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_LightType()));
Console::WriteLine(String(u"Direction: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_Direction()));

Console::WriteLine(u"= Effective shape's top face relief properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_BevelTop()->get_BevelType()));
Console::WriteLine(String(u"Width: ") + threeDEffectiveData->get_BevelTop()->get_Width());
Console::WriteLine(String(u"Height: ") + threeDEffectiveData->get_BevelTop()->get_Height());
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Osztály [ThreeDFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)