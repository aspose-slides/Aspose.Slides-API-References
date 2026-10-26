---
title: IsSurrogatePair()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, являются ли два указанных символа парой суррогатов UTF-16.
type: docs
weight: 27
url: /ru/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) method

Определяет, являются ли два указанных символа парой суррогатов UTF-16.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| highSurrogate | char_t | Символ, проверяемый на то, является ли он старшим суррогатом |
| lowSurrogate | char_t | Символ, проверяемый на то, является ли он младшим суррогатом |

### Возвращаемое значение

True, если указанные символы образуют пару суррогатов, иначе — false

## Char::IsSurrogatePair(const String\&, int) method

Определяет, являются ли две последовательные позиции в указанном буфере символов парой суррогатов.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../string/)\& | Строка |
| index | int | Нулевой индекс в указанном буфере, с которого начинается последовательность символов для проверки |

### Возвращаемое значение

True, если указанные символы образуют пару суррогатов, иначе — false

## См. также

* Класс [Char](../)
* Класс [String](../../string/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)