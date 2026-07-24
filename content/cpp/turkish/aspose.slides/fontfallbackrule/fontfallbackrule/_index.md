---
title: FontFallBackRule()
second_title: Aspose.Slides C++ API Referansı
description: Yeni bir örnek oluşturur.
type: docs
weight: 66
url: /tr/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) yapıcı

Yeni bir örnek oluşturur.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | **uint32_t** | Unicode aralığının başlangıç indeksi |
| endIndex | **uint32_t** | Unicode aralığının bitiş indeksi |
| fontNames | [System::String](../../../system/string/) | Geri Dönüş (FallBack) için virgülle ayrılmış font adı veya adları |

## Açıklamalar

```cpp
// Bir font ile FantFallBackRule yeni bir örnek oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Birden fazla font ile FantFallBackRule yeni bir örnek oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) yapıcı

Yeni bir örnek oluşturur.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | **uint32_t** | Unicode aralığının başlangıç indeksi |
| endIndex | **uint32_t** | Unicode aralığının bitiş indeksi |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Geri Dönüş (FallBack) için virgülle ayrılmış font adı veya adları |

## Açıklamalar

```cpp
// İki font ile FantFallBackRule yeni bir örnek oluşturur
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Birden fazla font ile FantFallBackRule yeni bir örnek oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [FontFallBackRule](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)