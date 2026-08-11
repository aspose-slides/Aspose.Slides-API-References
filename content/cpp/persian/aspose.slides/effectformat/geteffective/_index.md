---
title: GetEffective()
second_title: مرجع API Aspose.Slides برای C++
description: داده‌های قالب‌بندی اثر مؤثر را با اعمال ارث‌بری دریافت می‌کند.
type: docs
weight: 430
url: /fa/aspose.slides/effectformat/geteffective/
---
## EffectFormat::GetEffective() متد


داده‌های قالب‌بندی اثر مؤثر را که ارث‌بری اعمال شده است، دریافت می‌کند.

```cpp
System::SharedPtr<IEffectFormatEffectiveData> Aspose::Slides::EffectFormat::GetEffective() override
```

### مقدار بازگشت

یک [IEffectFormatEffectiveData](../../ieffectformateffectivedata/).

## توضیحات



این مثال نشان می‌دهد که چگونه برخی از ویژگی‌های مؤثر اثر شکل را دریافت می‌کنیم.
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

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IEffectFormatEffectiveData](../../ieffectformateffectivedata/)
* کلاس [EffectFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)