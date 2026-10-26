---
title: Replace()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengganti semua kecocokan regex dalam string dengan string pengganti.
type: docs
weight: 92
url: /id/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) metode


Mengganti semua kecocokan regex dalam string dengan string pengganti.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| replacement | const [String](../../../system/string/)\& | String pengganti. |

### Nilai Kembali

String masukan dengan semua kecocokan regex diganti dengan string pengganti.

## Regex::Replace(const String\&, const char_t *) metode


Mengganti semua kecocokan regex dalam string dengan string pengganti.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| replacement | const char_t * | String pengganti. |

### Nilai Kembali

String masukan dengan semua kecocokan regex diganti dengan string pengganti.

## Regex::Replace(const String\&, const MatchEvaluator\&) metode


Mengganti semua kecocokan dalam string dengan string pengganti yang dihasilkan oleh delegasi.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegasi untuk menghasilkan string pengganti berdasarkan kecocokan. |

### Nilai Kembali

String masukan dengan semua kecocokan diganti.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) metode


Mengganti semua kecocokan dalam string dengan string pengganti yang dihasilkan oleh delegasi.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegasi untuk menghasilkan string pengganti berdasarkan kecocokan. |
| count | int | Batas jumlah penggantian. |

### Nilai Kembali

String masukan dengan semua kecocokan diganti.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) metode


Mengganti semua kecocokan dalam string dengan string pengganti yang dihasilkan oleh delegasi.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegasi untuk menghasilkan string pengganti berdasarkan kecocokan. |
| count | int | Batas jumlah penggantian. |
| startat | int | [Index](../../../system/index/) dalam string masukan untuk memulai penggantian pada. |

### Nilai Kembali

String masukan dengan semua kecocokan diganti.

## Regex::Replace(const String\&, const String\&, int) metode


Mengganti substring dalam string. Tidak diimplementasikan.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) metode


Mengganti substring dalam string. Tidak diimplementasikan.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) metode


Mengganti semua kecocokan regex dalam string dengan string pengganti.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| pattern | const char_t * | [Regex](../) pola. |
| replacement | const char_t * | String pengganti. |

### Nilai Kembali

String masukan dengan semua kecocokan regex diganti dengan string pengganti.

## Regex::Replace(const String\&, const String\&, const char_t *) metode


Mengganti semua kecocokan regex dalam string dengan string pengganti.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) pola. |
| replacement | const char_t * | String pengganti. |

### Nilai Kembali

String masukan dengan semua kecocokan regex diganti dengan string pengganti.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) metode


Mengganti semua kecocokan dalam string dengan string pengganti yang dihasilkan oleh delegasi (fungsi statis).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) pola. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegasi untuk menghasilkan string pengganti berdasarkan kecocokan. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opsi. |

### Nilai Kembali

String masukan dengan semua kecocokan diganti.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) metode


Mengganti semua kecocokan regex dalam string dengan string pengganti.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) pola. |
| replacement | const [String](../../../system/string/)\& | String pengganti. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opsi. |

### Nilai Kembali

String masukan dengan semua kecocokan regex diganti dengan string pengganti.

## Regex::Replace(const String\&, const String\&, const String\&) metode


Mengganti kecocokan regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| pattern | const [String](../../../system/string/)\& | Pola regexp. |
| replacement | const [String](../../../system/string/)\& | String pengganti. |

### Nilai Kembali

[String](../../../system/string/) dengan semua kecocokan diganti.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) metode


Mengganti kecocokan regex.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | String masukan. |
| pattern | const [String](../../../system/string/)\& | Pola regexp. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegasi untuk menghasilkan string pengganti untuk setiap kecocokan. |

### Nilai Kembali

[String](../../../system/string/) dengan semua kecocokan diganti.

## Lihat Juga

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)