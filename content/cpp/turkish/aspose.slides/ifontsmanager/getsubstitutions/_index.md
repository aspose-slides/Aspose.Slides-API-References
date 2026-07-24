---
title: GetSubstitutions()
second_title: Aspose.Slides C++ API Referansı
description: Sunumun render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır.
type: docs
weight: 66
url: /tr/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() metod

Sunumun render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### Dönüş Değeri

Tüm yazı tipi değişimlerinin koleksiyonu [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) metod


Belirtilen slaytların render edilmesi sırasında değiştirilecek yazı tipleri hakkında bilgi alır.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Yazar tip değişim bilgilerini almak için kullanılacak slayt indekslerinin bir dizisi, 1'den başlayarak. |

### Dönüş Değeri

Belirtilen slaytlar için tüm yazı tipi değişimlerinin bir koleksiyonu ([FontSubstitutionInfo](../../fontsubstitutioninfo/)).

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
* Sınıf [IEnumerable](../../../system.collections.generic/ienumerable/)
* Sınıf [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Sınıf [IFontsManager](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)