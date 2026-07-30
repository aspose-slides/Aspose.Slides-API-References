---
title: GetEffective()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá efektivní data pozadí s použitým děděním.
type: docs
weight: 118
url: /cs/aspose.slides/background/geteffective/
---
## Background::GetEffective() metoda


Získá efektivní data pozadí s použitým děděním.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### Návratová hodnota

A [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## Poznámky



Tento příklad ukazuje získání efektivních vlastností pozadí. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Třída [Background](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)