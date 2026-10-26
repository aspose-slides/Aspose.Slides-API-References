---
title: Replace()
second_title: Aspose.Slides C++ API referenciája
description: Az összes regex-illeszkedést a karakterláncban a helyettesítő karakterláncra cseréli.
type: docs
weight: 92
url: /hu/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) method

Az összes regex-illeszkedést a karakterláncban a helyettesítő karakterláncra cseréli.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| replacement | const [String](../../../system/string/)\& | Helyettesítő karakterlánc. |

### Visszatérési érték

Bemeneti karakterlánc, amelyben az összes regex-illeszkedés a helyettesítő karakterláncra lett cserélve.

## Regex::Replace(const String\&, const char_t *) method

Az összes regex-illeszkedést a karakterláncban a helyettesítő karakterláncra cseréli.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| replacement | const char_t * | Helyettesítő karakterlánc. |

### Visszatérési érték

Bemeneti karakterlánc, amelyben az összes regex-illeszkedés a helyettesítő karakterláncra lett cserélve.

## Regex::Replace(const String\&, const MatchEvaluator\&) method

Az összes egyezést a karakterláncban a delegált által generált helyettesítő karakterláncokra cseréli.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegált, amely a egyezések alapján generálja a helyettesítő karakterláncokat. |

### Visszatérési érték

Bemeneti karakterláncok, amelyekben az összes egyezés le van cserélve.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) method

Az összes egyezést a karakterláncban a delegált által generált helyettesítő karakterláncokra cseréli.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegált, amely a egyezések alapján generálja a helyettesítő karakterláncokat. |
| count | int | A helyettesítések számának korlátja. |

### Visszatérési érték

Bemeneti karakterláncok, amelyekben az összes egyezés le van cserélve.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) method

Az összes egyezést a karakterláncban a delegált által generált helyettesítő karakterláncokra cseréli.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegált, amely a egyezések alapján generálja a helyettesítő karakterláncokat. |
| count | int | A helyettesítések számának korlátja. |
| startat | int | [Index](../../../system/index/) a bemeneti karakterláncban a csere megkezdéséhez. |

### Visszatérési érték

Bemeneti karakterláncok, amelyekben az összes egyezés le van cserélve.

## Regex::Replace(const String\&, const String\&, int) method

Alkarakterláncokat cserél a karakterláncban. Nincs megvalósítva.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) method

Alkarakterláncokat cserél a karakterláncban. Nincs megvalósítva.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) method

Az összes regex-illeszkedést a karakterláncban a helyettesítő karakterláncra cseréli.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| pattern | const char_t * | [Regex](../) minta. |
| replacement | const char_t * | Helyettesítő karakterlánc. |

### Visszatérési érték

Bemeneti karakterlánc, amelyben az összes regex-illeszkedés a helyettesítő karakterláncra lett cserélve.

## Regex::Replace(const String\&, const String\&, const char_t *) method

Az összes regex-illeszkedést a karakterláncban a helyettesítő karakterláncra cseréli.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) minta. |
| replacement | const char_t * | Helyettesítő karakterlánc. |

### Visszatérési érték

Bemeneti karakterlánc, amelyben az összes regex-illeszkedés a helyettesítő karakterláncra lett cserélve.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) method

Az összes egyezést a karakterláncban a delegált által generált helyettesítő karakterláncokra (statikus függvény) cseréli.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) minta. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegált, amely a egyezések alapján generálja a helyettesítő karakterláncokat. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opciók. |

### Visszatérési érték

Bemeneti karakterláncok, amelyekben az összes egyezés le van cserélve.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) method

Az összes regex-illeszkedést a karakterláncban a helyettesítő karakterláncra cseréli.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) minta. |
| replacement | const [String](../../../system/string/)\& | Helyettesítő karakterlánc. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opciók. |

### Visszatérési érték

Bemeneti karakterlánc, amelyben az összes regex-illeszkedés a helyettesítő karakterláncra lett cserélve.

## Regex::Replace(const String\&, const String\&, const String\&) method

Regex-illeszkedéseket cserél.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| pattern | const [String](../../../system/string/)\& | Regexp minta. |
| replacement | const [String](../../../system/string/)\& | Helyettesítő karakterlánc. |

### Visszatérési érték

[String](../../../system/string/) az összes egyezés le van cserélve.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) method

Regex-illeszkedéseket cserél.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| pattern | const [String](../../../system/string/)\& | Regexp minta. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegált, amely minden egyezéshez generál egy helyettesítő karakterláncot. |

### Visszatérési érték

[String](../../../system/string/) az összes egyezés le van cserélve.

## See Also

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)