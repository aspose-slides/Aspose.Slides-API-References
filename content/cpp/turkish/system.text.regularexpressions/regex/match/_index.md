---
title: Match()
second_title: Aspose.Slides için C++ API Referansı
description: Regex'i dizeye karşı eşleştirir.
type: docs
weight: 66
url: /tr/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) yöntemi

Regex'i dizeye karşı eşleştirir.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Hedef dize. |

### Dönüş Değeri

[Match](../../match/) değeri, eşleşme durumu ve alt eşleşmeler içerir.

## Regex::Match(const String\&, int, int) yöntemi

Regex'i dizeye karşı eşleştirir.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Hedef dize. |
| startat | int | Başlangıç indeksi. |
| length | int | Gözden geçirilecek karakter sayısı (0 tüm dizeyi gözden geçirmek için). |

### Dönüş Değeri

[Match](../../match/) değeri, eşleşme durumu ve alt eşleşmeler içerir.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) yöntemi

Dize ve desen eşleştirir.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Girdi dizesi. |
| pattern | const [String](../../../system/string/)\& | Regexp deseni. |
| options | [RegexOptions](../../regexoptions/) | Eşleştirme seçenekleri. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Zaman aşımı. |
| startat | int | [Match](../../match/) başlangıç konumu. |
| length | int | Gözden geçirilecek karakter sayısı (0 sınırlamayı devre dışı bırakır). |

### Dönüş Değeri

İlk eşleşme bulundu.

## Ayrıca Bakınız

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Regex](../)
* Sınıf [TimeSpan](../../../system/timespan/)
* Ad alanı [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)