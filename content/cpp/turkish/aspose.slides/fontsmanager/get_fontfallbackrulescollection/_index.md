---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides için C++ API Referansı
description: Kullanıcının FontFallBack kurallarının bir koleksiyonunu temsil eder; fallback işleviyle doğru ikameler için yazı tipi koleksiyonlarını yönetir. IFontFallBackRulesCollection'ı okuyun.
type: docs
weight: 27
url: /tr/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() metot


Kullanıcının FontFallBack kurallarının koleksiyonunu temsil eder; fallback işlevselliği sayesinde doğru ikameler için yazı tipleri koleksiyonlarını yönetir. Oku [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Açıklamalar


```cpp
auto pres = MakeObject<Presentation>();
// FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alıyor
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// kuralları koleksiyona ekleme
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// veya
// kurallar koleksiyonunun yeni bir örneğini başlatma
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// kuralları koleksiyona ekleme
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ve mevcut koleksiyonu FontsManager'da yeniyle değiştiriyor
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Sınıf [FontsManager](../)
* Ad Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)