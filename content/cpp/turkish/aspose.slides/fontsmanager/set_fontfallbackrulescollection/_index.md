---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides için C++ API Referansı
description: Bir kullanıcının FontFallBack kurallarının koleksiyonunu temsil eder; font koleksiyonlarını yönetmek ve yedekleme işleviyle doğru ikameler sağlamak için. Write IFontFallBackRulesCollection.
type: docs
weight: 40
url: /tr/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) metodu

Bir kullanıcının FontFallBack kurallarının koleksiyonunu, font koleksiyonlarını yönetmek ve yedekleme işleviyle doğru ikameler sağlamak için temsil eder Write [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Açıklamalar


```cpp
auto pres = MakeObject<Presentation>();
// FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alma
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// kuralları koleksiyona ekleme
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ya da
// kurallar koleksiyonunun yeni bir örneğinin başlatılması
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// kuralları koleksiyona ekleme
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ve mevcut koleksiyonu FontsManager'da yenisiyle değiştirme
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Sınıf [FontsManager](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)