---
title: GetEffective()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá efektivní data formátování výplně s aplikovaným děděním.
type: docs
weight: 105
url: /cs/aspose.slides/fillformat/geteffective/
---
## FillFormat::GetEffective() metoda

Získá efektivní data formátování výplně s aplikovaným děděním.

```cpp
System::SharedPtr<IFillFormatEffectiveData> Aspose::Slides::FillFormat::GetEffective() override
```

### Návratová hodnota

A [IFillFormatEffectiveData](../../ifillformateffectivedata/).
## Poznámky

Tento příklad ukazuje, jak získat efektivní vlastnosti formátu výplně tvaru. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveFillFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_FillFormat()->GetEffective();

Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(effectiveFillFormat->get_FillType()));
switch (effectiveFillFormat->get_FillType())
{
    case FillType::Solid:
        Console::WriteLine(String(u"Fill color: ") + effectiveFillFormat->get_SolidFillColor());
        break;

    case FillType::Pattern:
        Console::WriteLine(String(u"Pattern style: ") + ObjectExt::ToString(effectiveFillFormat->get_PatternFormat()->get_PatternStyle()));
        Console::WriteLine(String(u"Fore color: ") + effectiveFillFormat->get_PatternFormat()->get_ForeColor());
        Console::WriteLine(String(u"Back color: ") + effectiveFillFormat->get_PatternFormat()->get_BackColor());
        break;

    case FillType::Gradient:
        Console::WriteLine(String(u"Gradient direction: ") + ObjectExt::ToString(effectiveFillFormat->get_GradientFormat()->get_GradientDirection()));
        Console::WriteLine(String(u"Gradient stops count: ") + effectiveFillFormat->get_GradientFormat()->get_GradientStops()->get_Count());
        break;

    case FillType::Picture:
        Console::WriteLine(String(u"Picture width: ") + effectiveFillFormat->get_PictureFillFormat()->get_Picture()->get_Image()->get_Width());
        Console::WriteLine(String(u"Picture height: ") + effectiveFillFormat->get_PictureFillFormat()->get_Picture()->get_Image()->get_Height());
        break;

    default:
        break;
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IFillFormatEffectiveData](../../ifillformateffectivedata/)
* třída [FillFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)