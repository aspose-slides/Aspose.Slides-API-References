---
title: GetEffective()
second_title: Aspose.Slides pro C++ referenci API
description: Získá efektivní data formátování části s použitím dědičnosti.
type: docs
weight: 131
url: /cs/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() metoda

Získá efektivní data formátování části s použitím dědičnosti.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```

### Návratová hodnota

Jedná se o [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Poznámky

Tento příklad ukazuje získání některých efektivních vlastností formátu části.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Třída [PortionFormat](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)