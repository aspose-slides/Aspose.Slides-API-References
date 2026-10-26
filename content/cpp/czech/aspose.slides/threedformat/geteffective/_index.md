---
title: GetEffective()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá efektivní 3-D formátovací data s aplikovaným děděním.
type: docs
weight: 183
url: /cs/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() metoda


Získá efektivní 3-D formátovací data s aplikovaným děděním.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```


### Návratová hodnota

Objekt [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).
## Poznámky



Tento příklad ukazuje, jak získat efektivní vlastnosti pro kameru, osvětlovací soupravu a horní zkosení objektu. 
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

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Třída [ThreeDFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)