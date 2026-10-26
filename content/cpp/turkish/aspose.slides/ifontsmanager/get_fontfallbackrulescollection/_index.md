---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides için C++ API Referansı
description: Yedekleme işleviyle uygun değişimler sağlamak için yazı tipleri koleksiyonlarını yönetmek amacıyla bir kullanıcının FontFallBack kurallarının koleksiyonunu temsil eder. Oku IFontFallBackRulesCollection.
type: docs
weight: 27
url: /tr/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() metodu

FontFallBack işleviyle uygun yedekleme değişimleri sağlamak için yazı tipleri koleksiyonlarını yönetmek amacıyla bir kullanıcının FontFallBack kurallarının koleksiyonunu temsil eder. Oku [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## Açıklamalar



```cpp
auto pres = MakeObject<Presentation>();
// FontsManager'dan boş ya da önceden başlatılmış kurallar koleksiyonunu alıyor
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// kuralları koleksiyona ekleme
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// veya
// yeni kurallar koleksiyonu örneğinin başlatılması
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// kuralları koleksiyona ekleme
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ve mevcut koleksiyonu FontsManager'da yeni olanla değiştirme
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)