---
title: Matches()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan semua kecocokan regex dalam string yang diberikan dengan mencocokkan berulang kali.
type: docs
weight: 79
url: /id/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) metode

Mendapatkan semua kecocokan regex dalam string yang diberikan dengan mencocokkan berulang kali.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| startat | int | [Index](../../../system/index/) untuk memulai pencocokan pada. |

### Nilai Kembalian

Koleksi semua kecocokan yang ditemukan.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) metode

Mendapatkan semua kecocokan antara string dan pola.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| pattern | const [String](../../../system/string/)\& | Pola Regexp. |
| options | [RegexOptions](../../regexoptions/) | Opsi pencocokan. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Batas waktu. |
| startat | int | [Match](../../match/) posisi awal. |
| length | int | Jumlah karakter yang akan diperiksa (0 menonaktifkan batas). |

### Nilai Kembalian

Semua kecocokan yang ditemukan dengan mencocokkan berulang kali.

## Lihat Juga

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)