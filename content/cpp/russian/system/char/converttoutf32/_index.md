---
title: ConvertToUtf32()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует указанную пару суррогатов UTF-16 в кодовую единицу UTF-32.
type: docs
weight: 287
url: /ru/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) метод

Преобразует указанный пару суррогатов UTF-16 в кодовую единицу UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| highSurrogate | char_t | Высокий суррогат UTF-16-пары, которую нужно преобразовать |
| lowSurrogate | char_t | Низкий суррогат UTF-16-пары, которую нужно преобразовать |

### Возвращаемое значение

Кодовая единица UTF-32, полученная в результате преобразования

## Char::ConvertToUtf32(const String\&, int) метод

Преобразует значение символа UTF-16 или пары суррогатов в указанной позиции строки в кодовую единицу UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../string/)\& | Строка, содержащая символ или пару суррогатов |
| index | int | Позиция индекса символа или пары суррогатов в указанной строке |

### Возвращаемое значение

Кодовая единица UTF-32, полученная в результате преобразования

## См. также

* Класс [Char](../)
* Класс [String](../../string/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)