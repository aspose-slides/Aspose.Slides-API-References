---
title: Matches()
second_title: Aspose.Slides C++ API Referansı
description: Verilen string içinde, düzenli ifadeyi tekrar tekrar eşleştirerek tüm eşleşmeleri alır.
type: docs
weight: 79
url: /tr/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) metot

Verilen string içinde, düzenli ifadeyi tekrar tekrar eşleştirerek tüm eşleşmeleri alır.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| startat | int | [Index](../../../system/index/) eşleştirmeye başlanacak konum. |

### Dönüş Değeri

Bulunan tüm eşleşmelerin koleksiyonu.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) metot

String ve desen arasındaki tüm eşleşmeleri alır.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | Regexp pattern. |
| options | [RegexOptions](../../regexoptions/) | Matching options. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |
| startat | int | [Match](../../match/) başlangıç konumu. |
| length | int | İncelenecek karakter sayısı (0 limit devre dışı bırakır). |

### Dönüş Değeri

Tekrarlanan eşleştirmelerle bulunan tüm eşleşmeler.

## Ayrıca Bakınız

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Regex](../)
* Sınıf [TimeSpan](../../../system/timespan/)
* Ad alanı [System::Text::RegularExpressions](../../)
* Kütüphane [Aspose.Slides](../../../)