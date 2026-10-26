---
title: Split()
second_title: Aspose.Slides için C++ API Referansı
description: Dizeyi regex eşleşmeleriyle bölür.
type: docs
weight: 105
url: /tr/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) metodu

Dizeyi regex eşleşmeleriyle böler.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) bölmek için. |

### Return Value

[Array](../../../system/array/) eşleşmeler arasındaki alt dizeler.

## Regex::Split(const String\&, int) metodu

Dizeyi regex eşleşmeleriyle böler.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) bölmek için. |
| count | int | Alt dize sayısı limiti. |

### Return Value

[Array](../../../system/array/) eşleşmeler arasındaki alt dizeler.

## Regex::Split(const String\&, int, int) metodu

Girdi dizesini belirli bir maksimum sayıda bölerek bir dizi alt dizeye ayırır; bu konumlar, [Regex](../) yapıcısında belirtilen bir düzenli ifadeyle tanımlanır. Düzenli ifade deseninin araması, girdi dizesindeki belirtilen karakter konumundan başlar.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bölünecek dize. |
| count | int | Bölmenin gerçekleşebileceği maksimum sayı. |
| startat | int | Aramanın başlayacağı girdi dizesindeki karakter konumu. |

### Return Value

Dizeler dizisi.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) metodu

Dizeyi regexp ile böler.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Girdi dizesi. |
| pattern | const [String](../../../system/string/)\& | Regexp deseni. |
| options | [RegexOptions](../../regexoptions/) | Eşleme seçenekleri. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Zaman aşımı. |

### Return Value

[Array](../../../system/array/) eşleşmeler arasındaki dizeler.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) metodu

Dizeyi regexp ile böler.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Girdi dizesi. |
| pattern | const [String](../../../system/string/)\& | Regexp deseni. |
| count | int | [Match](../../match/) sayı limiti. |
| options | [RegexOptions](../../regexoptions/) | Eşleme seçenekleri. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Zaman aşımı. |

### Return Value

[Array](../../../system/array/) eşleşmeler arasındaki dizeler.

## Ayrıca Bakınız

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)