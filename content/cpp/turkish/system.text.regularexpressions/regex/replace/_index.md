---
title: Replace()
second_title: Aspose.Slides for C++ API Referansı
description: Dizedeki regex'in tüm eşleşmelerini yerine koyma dizesiyle değiştirir.
type: docs
weight: 92
url: /tr/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) metodu

Dizedeki regex'in tüm eşleşmelerini yerine koyma dizesiyle değiştirir.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Giriş dizesi. |
| replacement | const [String](../../../system/string/)\& | Yerine koyma dizesi. |

### Dönüş Değeri

Tüm regex eşleşmeleri yerine koyma dizesiyle değiştirilen giriş dizesi.

## Regex::Replace(const String\&, const char_t *) metodu

Dizedeki regex'in tüm eşleşmelerini yerine koyma dizesiyle değiştirir.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Giriş dizesi. |
| replacement | const char_t * | Yerine koyma dizesi. |

### Dönüş Değeri

Tüm regex eşleşmeleri yerine koyma dizesiyle değiştirilen giriş dizesi.

## Regex::Replace(const String\&, const MatchEvaluator\&) metodu

String içindeki tüm eşleşmeleri temsilci tarafından oluşturulan yerine koyma dizeleriyle değiştirir.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Giriş dizesi. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Eşleşmelere dayalı yerine koyma dizeleri üretmek için temsilci. |

### Dönüş Değeri

Tüm eşleşmeler yerine konulmuş giriş dizesi.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) metodu

String içindeki tüm eşleşmeleri temsilci tarafından oluşturulan yerine koyma dizeleriyle değiştirir.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Giriş dizesi. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Eşleşmelere dayalı yerine koyma dizeleri üretmek için temsilci. |
| count | int | Değiştirme sayısı sınırı. |

### Dönüş Değeri

Tüm eşleşmeler yerine konulmuş giriş dizesi.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) metodu

String içindeki tüm eşleşmeleri temsilci tarafından oluşturulan yerine koyma dizeleriyle değiştirir.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Giriş dizesi. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Eşleşmelere dayalı yerine koyma dizeleri üretmek için temsilci. |
| count | int | Değiştirme sayısı sınırı. |
| startat | int | [Index](../../../system/index/) giriş dizesinde değiştirmeye başlanacak konum. |

### Dönüş Değeri

Tüm eşleşmeler yerine konulmuş giriş dizesi.

## Regex::Replace(const String\&, const String\&, int) metodu

String içinde alt dizeleri değiştirir. Henüz uygulanmadı.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) metodu

String içinde alt dizeleri değiştirir. Henüz uygulanmadı.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) metodu

Dizedeki regex'in tüm eşleşmelerini yerine koyma dizesiyle değiştirir.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Giriş dizesi. |
| pattern | const char_t * | [Regex](../) deseni. |
| replacement | const char_t * | Yerine koyma dizesi. |

### Dönüş Değeri

Tüm regex eşleşmeleri yerine koyma dizesiyle değiştirilen giriş dizesi.

## Regex::Replace(const String\&, const String\&, const char_t *) metodu

Dizedeki regex'in tüm eşleşmelerini yerine koyma dizesiyle değiştirir.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Giriş dizesi. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) deseni. |
| replacement | const char_t * | Yerine koyma dizesi. |

### Dönüş Değeri

Tüm regex eşleşmeleri yerine koyma dizesiyle değiştirilen giriş dizesi.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) metodu

String içindeki tüm eşleşmeleri temsilci tarafından oluşturulan yerine koyma dizeleriyle (statik fonksiyon) değiştirir.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Giriş dizesi. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) deseni. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Eşleşmelere dayalı yerine koyma dizeleri üretmek için temsilci. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) seçenekleri. |

### Dönüş Değeri

Tüm eşleşmeler yerine konulmuş giriş dizesi.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) metodu

Dizedeki regex'in tüm eşleşmelerini yerine koyma dizesiyle değiştirir.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Giriş dizesi. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) deseni. |
| replacement | const [String](../../../system/string/)\& | Yerine koyma dizesi. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) seçenekleri. |

### Dönüş Değeri

Tüm regex eşleşmeleri yerine koyma dizesiyle değiştirilen giriş dizesi.

## Regex::Replace(const String\&, const String\&, const String\&) metodu

Regex eşleşmelerini değiştirir.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Giriş dizesi. |
| pattern | const [String](../../../system/string/)\& | Regexp deseni. |
| replacement | const [String](../../../system/string/)\& | Yerine koyma dizesi. |

### Dönüş Değeri

[String](../../../system/string/) tüm eşleşmeler yerine konulmuş hali.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) metodu

Regex eşleşmelerini değiştirir.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Giriş dizesi. |
| pattern | const [String](../../../system/string/)\& | Regexp deseni. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Her eşleşme için yerine koyma dizesi üreten temsilci. |

### Dönüş Değeri

[String](../../../system/string/) tüm eşleşmeler yerine konulmuş hali.

## Ayrıca Bakınız

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)