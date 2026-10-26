---
title: ToArray()
second_title: Aspose.Slides için C++ API Referansı
description: Bu kural için tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür.
type: docs
weight: 105
url: /tr/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() metod


Bu kural için tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### Dönüş Değeri

Array of [System::String](../../../system/string/)
## Açıklamalar



```cpp
// Yazı tipi listesi içeren bir kural oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Get tüm yazı tipi adlarını dizi olarak al
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) metod


Listede belirtilen aralıktaki tüm FallBack yazı tiplerini içeren bir dizi oluşturur ve döndürür.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | **int32_t** | Eklenecek ilk yazı tipinin dizini. |
| count | **int32_t** | Eklenecek yazı tiplerinin sayısı. |

### Dönüş Değeri

Array of [System::String](../../../system/string/)
## Açıklamalar



```cpp
// Yazı tipi listesi içeren bir kural oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Son iki yazı tipi adını dizi olarak al
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [IFontFallBackRule](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)