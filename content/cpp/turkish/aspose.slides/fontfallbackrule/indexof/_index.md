---
title: IndexOf()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen kuralın koleksiyondaki indeksini döndürür.
type: docs
weight: 157
url: /tr/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) yöntemi


Belirtilen kuralın koleksiyondaki indeksini döndürür.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Bulunacak fontun adı. |

### Dönüş Değeri

Listedeki bir fontun indeksi veya font bulunamazsa -1.

## Açıklamalar



```cpp
// Bir font listesi içeren bir kural oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tahoma'nın indeksini al.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## İlgili

* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)