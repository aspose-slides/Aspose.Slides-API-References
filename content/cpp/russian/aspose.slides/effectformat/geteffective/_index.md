---
title: GetEffective()
second_title: Aspose.Slides для C++: справочник API
description: Получает данные эффективного форматирования эффектов с применённым наследованием.
type: docs
weight: 430
url: /ru/aspose.slides/effectformat/geteffective/
---
## EffectFormat::GetEffective() метод


Получает данные эффективного форматирования эффектов с применённым наследованием.

```cpp
System::SharedPtr<IEffectFormatEffectiveData> Aspose::Slides::EffectFormat::GetEffective() override
```


### Возвращаемое значение

Объект [IEffectFormatEffectiveData](../../ieffectformateffectivedata/).

## Примечания



В этом примере демонстрируется получение некоторых эффективных свойств эффекта фигуры. 
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

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IEffectFormatEffectiveData](../../ieffectformateffectivedata/)
* Класс [EffectFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)