---
title: GetEffective()
second_title: Referencja API Aspose.Slides dla C++
description: Zwraca efektywne dane tła z zastosowanym dziedziczeniem.
type: docs
weight: 118
url: /pl/aspose.slides/background/geteffective/
---
## Background::GetEffective() metoda


Zwraca efektywne dane tła z zastosowanym dziedziczeniem.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### Wartość zwracana

Obiekt [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## Uwagi



Ten przykład demonstruje pobieranie efektywnych własności tła. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Klasa [Background](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)