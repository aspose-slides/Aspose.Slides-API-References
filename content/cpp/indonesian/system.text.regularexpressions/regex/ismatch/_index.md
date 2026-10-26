---
title: IsMatch()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencocokkan regex dengan string.
type: docs
weight: 53
url: /id/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) metode


Mencocokkan regex dengan string.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Target string. |
| startat | int | Beginning index. |

### Nilai Kembali

True jika string cocok dengan regex, false sebaliknya.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) metode


Memeriksa apakah string cocok dengan pola.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Input string. |
| pattern | const [String](../../../system/string/)\& | Regexp pattern. |
| options | [RegexOptions](../../regexoptions/) | Matching options. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |
| startat | int | [Match](../../match/) posisi awal. |

### Nilai Kembali

True jika cocok ditemukan, false sebaliknya.

## Lihat Juga

* Enum [RegexOptions](../../regexoptions/)
* Kelas [String](../../../system/string/)
* Kelas [Regex](../)
* Kelas [TimeSpan](../../../system/timespan/)
* Ruang Nama [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)