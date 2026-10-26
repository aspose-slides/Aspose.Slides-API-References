---
title: Remove()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyondan belirli bir FallBack kuralının ilk oluşumunu kaldırır.
type: docs
weight: 53
url: /tr/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) metod

Koleksiyondan belirli bir FallBack kuralının ilk oluşumunu kaldırır.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Koleksiyondan kaldırılacak kural. |
## Açıklamalar



```cpp
auto pres = MakeObject<Presentation>();
//FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alıyor
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Koleksiyona birkaç kural ekleniyor
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Koleksiyondaki ilk kuralın nesnesi alınıyor
auto firstRule = rulesList->idx_get(0);
//Kaldırma
rulesList->Remove(firstRule);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontFallBackRule](../../ifontfallbackrule/)
* Sınıf [FontFallBackRulesCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)