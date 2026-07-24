---
title: idx_get()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen indeksteki kuralı alır. Yalnızca okuma IFontFallBackRule.
type: docs
weight: 1
url: /tr/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) metod

Belirtilen indeksteki kuralı alır. Yalnızca okuma [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Açıklamalar



```cpp
auto pres = MakeObject<Presentation>();
//FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alıyor
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Koleksiyona birkaç kural ekliyor
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Koleksiyondaki ilk kuralın nesnesini alıyor
auto firstRule = rulesList->idx_get(0);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontFallBackRule](../../ifontfallbackrule/)
* Sınıf [IFontFallBackRulesCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)