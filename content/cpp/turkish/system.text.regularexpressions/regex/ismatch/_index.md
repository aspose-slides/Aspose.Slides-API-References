---
title: IsMatch()
second_title: Aspose.Slides for C++ API Referansı
description: Dizeye karşı regex eşleştirir.
type: docs
weight: 53
url: /tr/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) metot

Regex'i dizeye karşı eşleştirir.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Hedef dize. |
| startat | int | Başlangıç indeksi. |

### Dönüş Değeri

Dize regex ile eşleşiyorsa doğru, aksi takdirde yanlış.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) metot

Dizenin desene eşleşip eşleşmediğini kontrol eder.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Girdi dizesi. |
| pattern | const [String](../../../system/string/)\& | Regex deseni. |
| options | [RegexOptions](../../regexoptions/) | Eşleme seçenekleri. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Zaman aşımı. |
| startat | int | [Match](../../match/) başlangıç konumu. |

### Dönüş Değeri

Eşleşme bulunursa doğru, aksi takdirde yanlış.

## İlgili

* Enum [RegexOptions](../../regexoptions/)
* Sınıf [String](../../../system/string/)
* Sınıf [Regex](../)
* Sınıf [TimeSpan](../../../system/timespan/)
* Ad alanı [System::Text::RegularExpressions](../../)
* Kütüphane [Aspose.Slides](../../../)