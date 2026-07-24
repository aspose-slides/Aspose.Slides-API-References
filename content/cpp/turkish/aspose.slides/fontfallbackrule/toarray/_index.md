---
title: ToArray()
second_title: Aspose.Slides for C++ API Referansı
description: Bu kural için tüm FallBack yazı tipleriyle bir dizi oluşturur ve döndürür.
type: docs
weight: 144
url: /tr/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() metod

Bu kural için tüm FallBack yazı tipleriyle bir dizi oluşturur ve döndürür.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```


### Dönüş Değeri

Dizi [System::String](../../../system/string/)
## Açıklamalar



```cpp
// Bir yazı tipi listesi içeren bir kural oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tüm yazı tipi adlarını dizi olarak al.
ArrayPtr<String> fontNames = newRule->ToArray();
```


## FontFallBackRule::ToArray(int32_t, int32_t) metod


Belirtilen aralıktaki tüm FallBack yazı tipleriyle bir dizi oluşturur ve döndürür.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | **int32_t** | Eklenecek ilk fontun dizini. |
| count | **int32_t** | Eklenmek üzere font sayısı. |

### Dönüş Değeri

Dizi [System::String](../../../system/string/)
## Açıklamalar



```cpp
// Bir yazı tipi listesi içeren bir kural oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Son iki yazı tipi adını dizi olarak al.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [FontFallBackRule](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)