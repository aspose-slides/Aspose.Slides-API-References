---
title: GetEffective()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a hatás érvényes formázási adatait az öröklődés alkalmazásával.
type: docs
weight: 430
url: /hu/aspose.slides/effectformat/geteffective/
---
## EffectFormat::GetEffective() metódus


Lekéri a hatás érvényes formázási adatait az öröklődés alkalmazásával.

```cpp
System::SharedPtr<IEffectFormatEffectiveData> Aspose::Slides::EffectFormat::GetEffective() override
```


### Visszatérési érték

A [IEffectFormatEffectiveData](../../ieffectformateffectivedata/).
## Megjegyzések



Ez a példa bemutatja, hogyan lehet lekérni a shape néhány érvényes hatás tulajdonságát. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveEffectFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_EffectFormat()->GetEffective();

if (effectiveEffectFormat->get_IsNoEffects())
{
    Console::WriteLine(u"The shape has not effects applied.");
}
else
{
    if (effectiveEffectFormat->get_BlurEffect() != nullptr)
    {
        Console::WriteLine(String(u"Blur effect radius: ") + effectiveEffectFormat->get_BlurEffect()->get_Radius());
    }
    if (effectiveEffectFormat->get_FillOverlayEffect() != nullptr)
    {
        Console::WriteLine(String(u"Fill overlay effect fill type: ") + ObjectExt::ToString(effectiveEffectFormat->get_FillOverlayEffect()->get_FillFormat()->get_FillType()));
    }
    if (effectiveEffectFormat->get_GlowEffect() != nullptr)
    {
        Console::WriteLine(String(u"Glow effect color: ") + effectiveEffectFormat->get_GlowEffect()->get_Color());
    }
    if (effectiveEffectFormat->get_InnerShadowEffect() != nullptr)
    {
        Console::WriteLine(String(u"Inner shadow effect shadow color: ") + effectiveEffectFormat->get_InnerShadowEffect()->get_ShadowColor());
    }
    if (effectiveEffectFormat->get_OuterShadowEffect() != nullptr)
    {
        Console::WriteLine(String(u"Outer shadow effect shadow color: ") + effectiveEffectFormat->get_OuterShadowEffect()->get_ShadowColor());
    }
    if (effectiveEffectFormat->get_PresetShadowEffect() != nullptr)
    {
        Console::WriteLine(String(u"Preset shadow effect shadow color: ") + effectiveEffectFormat->get_PresetShadowEffect()->get_ShadowColor());
    }
    if (effectiveEffectFormat->get_ReflectionEffect() != nullptr)
    {
        Console::WriteLine(String(u"Reflection effect distance: ") + effectiveEffectFormat->get_ReflectionEffect()->get_Distance());
    }
    if (effectiveEffectFormat->get_SoftEdgeEffect() != nullptr)
    {
        Console::WriteLine(String(u"Soft edge effect radius: ") + effectiveEffectFormat->get_SoftEdgeEffect()->get_Radius());
    }
}
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IEffectFormatEffectiveData](../../ieffectformateffectivedata/)
* Osztály [EffectFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)