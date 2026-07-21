---
title: Matches()
second_title: Aspose.Slides для C++ API Reference
description: Получает все совпадения регулярного выражения в заданной строке, выполняя поиск повторно.
type: docs
weight: 79
url: /ru/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) method

Получает все совпадения регулярного выражения в заданной строке, выполняя поиск повторно.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| startat | int | Индекс начала сопоставления. |

### Return Value

Коллекция всех найденных совпадений.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method

Получает все совпадения между строкой и шаблоном.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Входная строка. |
| pattern | const [String](../../../system/string/)\& | Шаблон регулярного выражения. |
| options | [RegexOptions](../../regexoptions/) | Параметры сопоставления. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Тайм-аут. |
| startat | int | [Match](../../match/) начальная позиция. |
| length | int | Количество символов для просмотра (0 отключает ограничение). |

### Return Value

Все найденные совпадения, полученные повторным поиском.

## See Also

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Класс [String](../../../system/string/)
* Класс [Regex](../)
* Класс [TimeSpan](../../../system/timespan/)
* Пространство имён [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)