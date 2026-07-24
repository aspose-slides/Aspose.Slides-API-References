---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides için C++ API Referansı
description: Kullanıcının FontFallBack kurallarının bir koleksiyonunu temsil eder; yedekleme işleviyle uygun ikameler için yazı tiplerinin koleksiyonlarını yönetir. IFontFallBackRulesCollection.
type: docs
weight: 40
url: /tr/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) metod

Kullanıcının FontFallBack kurallarının bir koleksiyonunu temsil eder; yedekleme işleviyle uygun ikameler için yazı tiplerinin koleksiyonlarını yönetir. Yaz [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## Açıklamalar

```cpp
auto pres = MakeObject<Presentation>();
// FontsManager'dan boş veya önceden başlatılmış kurallar koleksiyonunu alıyor
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// kuralları koleksiyona ekliyor
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// veya
// kurallar koleksiyonunun yeni örneğini başlatıyor
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// kuralları koleksiyona ekliyor
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ve mevcut koleksiyonu FontsManager'da yeni olanla değiştiriyor
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Diğer

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)