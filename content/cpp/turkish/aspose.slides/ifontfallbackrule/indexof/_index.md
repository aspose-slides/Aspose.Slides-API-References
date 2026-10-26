---
title: IndexOf()
second_title: Aspose.Slides için C++ API Referansı
description: Koleksiyondaki belirtilen kuralın indeksini döndürür.
type: docs
weight: 118
url: /tr/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) method


Koleksiyondaki belirtilen kuralın indeksini döndürür.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Bulunacak yazı tipinin adı. |

### Dönüş Değeri

Bir yazı tipinin indeksi ya da listede bulunamazsa -1.

## Notlar



```cpp
//Yazı tiplerinin bir listesini içeren bir kural oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Tahoma'nın indeksini al
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [IFontFallBackRule](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)