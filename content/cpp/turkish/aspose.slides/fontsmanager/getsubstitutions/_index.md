---
title: GetSubstitutions()
second_title: Aspose.Slides için C++ API Referansı
description: Sunumun render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır.
type: docs
weight: 66
url: /tr/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() yöntemi


Sunumun render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```


### Dönüş Değeri

Collection of all fonts substitution [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) yöntemi


Belirtilen slaytların render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | YZı tipi değiştirme bilgilerini almak için bir dizi slayt indeksi, 1'den başlayarak. |

### Dönüş Değeri

A collection of all font substitutions ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) for the specified slides.
## Açıklamalar




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)