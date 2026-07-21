---
title: Match()
second_title: Справочник API Aspose.Slides для C++
description: Сопоставляет регулярное выражение со строкой.
type: docs
weight: 66
url: /ru/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) метод

Сопоставляет регулярное выражение со строкой.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Целевая строка. |

### Возвращаемое значение

[Match](../../match/) значение, содержащее статус совпадения и подсовпадения.

## Regex::Match(const String\&, int, int) метод

Сопоставляет регулярное выражение со строкой.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Целевая строка. |
| startat | int | Начальный индекс. |
| length | int | Количество символов для просмотра (0 — просмотреть всю строку). |

### Возвращаемое значение

[Match](../../match/) значение, содержащее статус совпадения и подсовпадения.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) метод

Сопоставляет строку и шаблон.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| pattern | const [String](../../../system/string/)\& | Шаблон регулярного выражения. |
| options | [RegexOptions](../../regexoptions/) | Параметры сопоставления. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Тайм-аут. |
| startat | int | [Match](../../match/) начальная позиция. |
| length | int | Количество символов для просмотра (0 отключает ограничение). |

### Возвращаемое значение

Найдено первое совпадение.

## См. также

* Перечисление [RegexOptions](../../regexoptions/)
* Типовое определение [MatchPtr](../../matchptr/)
* Класс [String](../../../system/string/)
* Класс [Regex](../)
* Класс [TimeSpan](../../../system/timespan/)
* Пространство имён [System::Text::RegularExpressions](../../)
* Библиотека [Aspose.Slides](../../../)