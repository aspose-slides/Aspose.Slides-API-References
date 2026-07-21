---
title: GetNumericValue()
second_title: Справочник API Aspose.Slides для C++
description: Получает числовое значение, связанное с указанным символом.
type: docs
weight: 27
url: /ru/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) метод


Получает числовое значение, связанное с указанным символом.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ch | char16_t | Unicode character. |

### Возвращаемое значение

The numeric value or -1 if the specified character is not a numeric character.

## CharUnicodeInfo::GetNumericValue(const String\&, int) метод


Получает числовое значение, связанное с символом по указанному индексу строки.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | The string containing unicode character. |
| index | int | The index of the unicode character. |

### Возвращаемое значение

The numeric value or -1 if the specified character is not a numeric character.

## См. также

* Класс [CharUnicodeInfo](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Globalization](../../)
* Библиотека [Aspose.Slides](../../../)