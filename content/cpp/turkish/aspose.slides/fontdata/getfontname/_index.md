---
title: GetFontName()
second_title: Aspose.Slides C++ API Referansı
description: Yazı tipi adını döndürür, tema referansını kullanılan gerçek bir yazı tipiyle değiştirir.
type: docs
weight: 27
url: /tr/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) metodu


Yazı tipi adını, tema referansını gerçek kullanılan bir yazı tipiyle değiştirerek döndürür.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) alınacak temalı yazı tipi adının geldiği yer. Doğru bir değer sağlamak çağıranın sorumluluğundadır. Bakınız [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Dönüş Değeri

Yazı tipi adı.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* Sınıf [FontData](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)