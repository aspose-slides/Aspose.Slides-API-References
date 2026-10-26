---
title: Add()
second_title: Aspose.Slides için C++ API Referansı
description: Koleksiyonun sonuna yeni bir FallBack kuralı ekleyin.
type: docs
weight: 14
url: /tr/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) yöntemi

Koleksiyonun sonuna yeni bir FallBack kuralı ekleyin.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
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
//Yeni kuralı koleksiyona ekliyor
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontFallBackRule](../../ifontfallbackrule/)
* Sınıf [IFontFallBackRulesCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)