---
title: idx_get()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen indeksteki kuralı alır. Yalnızca okunabilir IFontFallBackRule.
type: docs
weight: 66
url: /tr/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) metot

Belirtilen indeksteki kuralı alır. Yalnızca okunabilir [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## Açıklamalar



```cpp
auto pres = MakeObject<Presentation>();
//Boş veya önceden başlatılmış kurallar koleksiyonunu FontsManager'dan alıyor
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Koleksiyona birkaç kural ekleniyor
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Koleksiyondaki ilk kuralın nesnesi alınıyor
auto firstRule = rulesList->idx_get(0);
```

## Ayrıca

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontFallBackRule](../../ifontfallbackrule/)
* Sınıf [FontFallBackRulesCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)