---
title: IsMatch()
second_title: Справочник API Aspose.Slides для C++
description: Сопоставляет регулярное выражение со строкой.
type: docs
weight: 53
url: /ru/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) method


Сопоставляет регулярное выражение со строкой.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Целевая строка. |
| startat | int | Начальный индекс. |

### Возвращаемое значение

True если строка соответствует регулярному выражению, false в противном случае.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) method


Проверяет, соответствует ли строка шаблону.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| pattern | const [String](../../../system/string/)\& | Шаблон регулярного выражения. |
| options | [RegexOptions](../../regexoptions/) | Параметры сопоставления. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Таймаут. |
| startat | int | [Match](../../match/) начальная позиция. |

### Возвращаемое значение

True если найдено совпадение, false в противном случае.

## См. также

* Enum [RegexOptions](../../regexoptions/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)