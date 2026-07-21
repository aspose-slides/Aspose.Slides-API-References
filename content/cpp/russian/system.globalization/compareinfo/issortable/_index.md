---
title: IsSortable()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, является ли указанный символ сортируемым.
type: docs
weight: 196
url: /ru/system.globalization/compareinfo/issortable/
---
## CompareInfo::IsSortable(char16_t) метод

Проверяет, является ли указанный символ сортируемым.

```cpp
static bool System::Globalization::CompareInfo::IsSortable(char16_t ch)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ch | char16_t | Unicode-символ. |

### Возвращаемое значение

True, если **ch** сортируем; иначе false.

## CompareInfo::IsSortable(const String\&) метод

Проверяет, является ли указанная строка сортируемой.

```cpp
static bool System::Globalization::CompareInfo::IsSortable(const String &text)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | Строка. |

### Возвращаемое значение

True, если **text** не пустой и все символы в **text** сортируемы; иначе false.

## Смотрите также

* Класс [CompareInfo](../)
* Класс [String](../../../system/string/)
* Пример пространства имён [System::Globalization](../../)
* Библиотека [Aspose.Slides](../../../)