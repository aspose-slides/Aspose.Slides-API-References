---
title: Add()
second_title: C++ için Aspose.Slides API Referansı
description: Belirtilen FallBack kuralını koleksiyonun sonuna ekler.
type: docs
weight: 40
url: /tr/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) method

Belirtilen FallBack kuralını koleksiyonun sonuna ekler.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Eklemek için belirtilen kural |
## Açıklamalar

```cpp
auto pres = MakeObject<Presentation>();
//FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alıyor
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Yeni kuralı koleksiyona ekleme
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Ayrıca

* Tür tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontFallBackRule](../../ifontfallbackrule/)
* Sınıf [FontFallBackRulesCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)