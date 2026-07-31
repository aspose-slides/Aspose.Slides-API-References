---
title: Match()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencocokkan regex terhadap string.
type: docs
weight: 66
url: /id/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) metode

Mencocokkan regex terhadap string.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String target. |

### Nilai Kembalian

[Match](../../match/) nilai yang berisi status kecocokan dan subpencocokan.

## Regex::Match(const String\&, int, int) metode

Mencocokkan regex terhadap string.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String target. |
| startat | int | Indeks awal. |
| length | int | Jumlah karakter yang akan diperiksa (0 untuk memeriksa seluruh string). |

### Nilai Kembalian

[Match](../../match/) nilai yang berisi status kecocokan dan subpencocokan.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) metode

Mencocokkan string dan pola.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| pattern | const [String](../../../system/string/)\& | Pola regexp. |
| options | [RegexOptions](../../regexoptions/) | Opsi pencocokan. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Batas waktu. |
| startat | int | [Match](../../match/) posisi awal. |
| length | int | Jumlah karakter yang akan diperiksa (0 menonaktifkan batas). |

### Nilai Kembalian

Kecocokan pertama yang ditemukan.

## Lihat Juga

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)