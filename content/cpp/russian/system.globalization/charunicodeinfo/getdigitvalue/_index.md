---
title: GetDigitValue()
second_title: Справочник API Aspose.Slides для C++
description: Получает числовое значение указанного символа.
type: docs
weight: 14
url: /ru/system.globalization/charunicodeinfo/getdigitvalue/
---
## CharUnicodeInfo::GetDigitValue(char16_t) метод


Получает числовое значение указанного символа.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(char16_t ch)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ch | char16_t | Unicode-символ. |

### Возвращаемое значение

Числовое значение или -1, если указанный символ не является цифрой.

## CharUnicodeInfo::GetDigitValue(const String\&, int) метод


Получает числовое значение символа по указанному индексу строки.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(const String &str, int index)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Строка, содержащая символ Unicode. |
| index | int | Индекс символа Unicode. |

### Возвращаемое значение

Числовое значение или -1, если указанный символ не является цифрой.

## См. также

* Класс [CharUnicodeInfo](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Globalization](../../)
* Библиотека [Aspose.Slides](../../../)