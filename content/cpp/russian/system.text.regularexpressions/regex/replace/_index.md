---
title: Replace()
second_title: Справочник API Aspose.Slides для C++
description: Заменяет все совпадения регулярного выражения в строке строкой-заменой.
type: docs
weight: 92
url: /ru/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) метод


Заменяет все совпадения регулярного выражения в строке строкой-заменой.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| replacement | const [String](../../../system/string/)\& | Строка замены. |

### Возвращаемое значение

Входная строка, в которой все совпадения регулярного выражения заменены строкой-заменой.

## Regex::Replace(const String\&, const char_t *) метод


Заменяет все совпадения регулярного выражения в строке строкой-заменой.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| replacement | const char_t * | Строка замены. |

### Возвращаемое значение

Входная строка, в которой все совпадения регулярного выражения заменены строкой-заменой.

## Regex::Replace(const String\&, const MatchEvaluator\&) метод


Заменяет все совпадения в строке строками-заменами, генерируемыми делегатом.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Делегат для генерации строк-замен на основе совпадений. |

### Возвращаемое значение

Входные строки, в которых все совпадения заменены.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) метод


Заменяет все совпадения в строке строками-заменами, генерируемыми делегатом.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Делегат для генерации строк-замен на основе совпадений. |
| count | int | Лимит количества замен. |

### Возвращаемое значение

Входные строки, в которых все совпадения заменены.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) метод


Заменяет все совпадения в строке строками-заменами, генерируемыми делегатом.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Делегат для генерации строк-замен на основе совпадений. |
| count | int | Лимит количества замен. |
| startat | int | Индекс во входной строке, с которого начинать замену. |

### Возвращаемое значение

Входные строки, в которых все совпадения заменены.

## Regex::Replace(const String\&, const String\&, int) метод


Заменяет подстроки в строке. Не реализовано.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) метод


Заменяет подстроки в строке. Не реализовано.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) метод


Заменяет все совпадения регулярного выражения в строке строкой-заменой.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| pattern | const char_t * | [Regex](../) шаблон. |
| replacement | const char_t * | Строка замены. |

### Возвращаемое значение

Входная строка, в которой все совпадения регулярного выражения заменены строкой-заменой.

## Regex::Replace(const String\&, const String\&, const char_t *) метод


Заменяет все совпадения регулярного выражения в строке строкой-заменой.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) шаблон. |
| replacement | const char_t * | Строка замены. |

### Возвращаемое значение

Входная строка, в которой все совпадения регулярного выражения заменены строкой-заменой.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) метод


Заменяет все совпадения в строке строками-заменами, генерируемыми делегатом (статическая функция).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) шаблон. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Делегат для генерации строк-замен на основе совпадений. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) параметры. |

### Возвращаемое значение

Входные строки, в которых все совпадения заменены.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) метод


Заменяет все совпадения регулярного выражения в строке строкой-заменой.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) шаблон. |
| replacement | const [String](../../../system/string/)\& | Строка замены. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) параметры. |

### Возвращаемое значение

Входная строка, в которой все совпадения регулярного выражения заменены строкой-заменой.

## Regex::Replace(const String\&, const String\&, const String\&) метод


Заменяет совпадения регулярного выражения.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| pattern | const [String](../../../system/string/)\& | Шаблон Regexp. |
| replacement | const [String](../../../system/string/)\& | Строка замены. |

### Возвращаемое значение

[String](../../../system/string/) со всеми заменёнными совпадениями.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) метод


Заменяет совпадения регулярного выражения.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| pattern | const [String](../../../system/string/)\& | Шаблон Regexp. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Делегат для генерации строки-замены для каждого совпадения. |

### Возвращаемое значение

[String](../../../system/string/) со всеми заменёнными совпадениями.

## См. также

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)