---
title: GetDecimalDigitValue()
second_title: Справочник API Aspose.Slides для C++
description: Получает десятичное значение цифры указанного символа.
type: docs
weight: 1
url: /ru/system.globalization/charunicodeinfo/getdecimaldigitvalue/
---
## CharUnicodeInfo::GetDecimalDigitValue(char16_t) метод

Получает десятичное значение цифры указанного символа.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(char16_t ch)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ch | char16_t | Unicode-символ. |

### Возвращаемое значение

Десятичное значение цифры или -1, если указанный символ не является десятичной цифрой.

## CharUnicodeInfo::GetDecimalDigitValue(const String\&, int) метод

Получает десятичное значение цифры символа по указанному индексу строки.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(const String &str, int index)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Строка, содержащая символ Unicode. |
| index | int | Индекс символа Unicode. |

### Возвращаемое значение

Десятичное значение цифры или -1, если указанный символ не является десятичной цифрой.

## См. также

* Класс [CharUnicodeInfo](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Globalization](../../)
* Библиотека [Aspose.Slides](../../../)