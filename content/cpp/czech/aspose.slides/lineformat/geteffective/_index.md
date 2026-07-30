---
title: GetEffective()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá efektivní data formátování čáry s aplikovaným děděním.
type: docs
weight: 417
url: /cs/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() metoda


Získá efektivní data formátování čáry s aplikovaným děděním.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### Návratová hodnota

A [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## Poznámky



Tento příklad ukazuje, jak získat efektivní vlastnosti formátu čáry tvaru. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Class [LineFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)