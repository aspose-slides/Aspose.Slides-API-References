---
title: Split()
second_title: Справочник API Aspose.Slides для C++
description: Разбивает строку по совпадениям регулярного выражения.
type: docs
weight: 105
url: /ru/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) метод

Разбивает строку по совпадениям регулярного выражения.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) для разделения. |

### Возвращаемое значение

[Array](../../../system/array/) подстрок между совпадениями.

## Regex::Split(const String\&, int) метод

Разбивает строку по совпадениям регулярного выражения.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) для разделения. |
| count | int | Ограничение количества подстрок. |

### Возвращаемое значение

[Array](../../../system/array/) подстрок между совпадениями.

## Regex::Split(const String\&, int, int) метод

Разбивает входную строку заданное максимальное количество раз на массив подстрок в позициях, определённых регулярным выражением, указанным в конструкторе [Regex](../). Поиск шаблона регулярного выражения начинается с указанной позиции символа во входной строке.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Строка для разделения. |
| count | int | Максимальное количество раз, которое может произойти разделение. |
| startat | int | Позиция символа во входной строке, с которой начинается поиск. |

### Возвращаемое значение

Массив строк.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) метод

Разбивает строку по регулярному выражению.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| pattern | const [String](../../../system/string/)\& | Шаблон регулярного выражения. |
| options | [RegexOptions](../../regexoptions/) | Параметры сопоставления. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Время ожидания. |

### Возвращаемое значение

[Array](../../../system/array/) строк между совпадениями.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) метод

Разбивает строку по регулярному выражению.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| pattern | const [String](../../../system/string/)\& | Шаблон регулярного выражения. |
| count | int | [Match](../../match/) ограничение количества. |
| options | [RegexOptions](../../regexoptions/) | Параметры сопоставления. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Время ожидания. |

### Возвращаемое значение

[Array](../../../system/array/) строк между совпадениями.

## См. также

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)