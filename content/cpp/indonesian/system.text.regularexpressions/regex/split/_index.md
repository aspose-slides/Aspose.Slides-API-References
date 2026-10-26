---
title: Split()
second_title: Referensi API Aspose.Slides untuk C++
description: Membagi string berdasarkan kecocokan regex.
type: docs
weight: 105
url: /id/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) metode

Membagi string berdasarkan kecocokan regex.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk dipisah. |

### Nilai Kembalian

[Array](../../../system/array/) dari substring di antara kecocokan.

## Regex::Split(const String\&, int) metode

Membagi string berdasarkan kecocokan regex.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk dipisah. |
| count | int | Batas jumlah substring. |

### Nilai Kembalian

[Array](../../../system/array/) dari substring di antara kecocokan.

## Regex::Split(const String\&, int, int) metode

Membagi sebuah string input menjadi array substring maksimal sejumlah kali tertentu, pada posisi yang ditentukan oleh ekspresi reguler yang ditentukan dalam konstruktor [Regex](../). Pencarian pola ekspresi reguler dimulai dari posisi karakter tertentu dalam string input.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String yang akan dipisah. |
| count | int | Jumlah maksimum kali pemisahan dapat terjadi. |
| startat | int | Posisi karakter dalam string input di mana pencarian akan dimulai. |

### Nilai Kembalian

Sebuah array string.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) metode

Membagi string berdasarkan regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String input. |
| pattern | const [String](../../../system/string/)\& | Pola regexp. |
| options | [RegexOptions](../../regexoptions/) | Opsi pencocokan. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Batas waktu. |

### Nilai Kembalian

[Array](../../../system/array/) dari string di antara kecocokan.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) metode

Membagi string berdasarkan regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String input. |
| pattern | const [String](../../../system/string/)\& | Pola regexp. |
| count | int | [Match](../../match/) batas angka. |
| options | [RegexOptions](../../regexoptions/) | Opsi pencocokan. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Batas waktu. |

### Nilai Kembalian

[Array](../../../system/array/) dari string di antara kecocokan.

## Lihat Juga

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [Regex](../)
* Kelas [TimeSpan](../../../system/timespan/)
* Ruang Nama [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)