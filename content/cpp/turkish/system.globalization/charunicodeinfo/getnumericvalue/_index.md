---
title: GetNumericValue()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen karakterle ilişkili sayısal değeri alır.
type: docs
weight: 27
url: /tr/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) metodu

Belirtilen karakterle ilişkili sayısal değeri alır.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ch | char16_t | Unicode karakteri. |

### Dönüş Değeri

Sayısal değer veya belirtilen karakter bir sayısal karakter değilse -1.

## CharUnicodeInfo::GetNumericValue(const String\&, int) metodu

Belirtilen dizgedeki karakterin belirtilen indeksindeki sayısal değeri alır.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Unicode karakteri içeren dize. |
| index | int | Unicode karakterinin indeksi. |

### Dönüş Değeri

Sayısal değer veya belirtilen karakter bir sayısal karakter değilse -1.

## İlgili

* Sınıf [CharUnicodeInfo](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Globalization](../../)
* Kütüphane [Aspose.Slides](../../../)