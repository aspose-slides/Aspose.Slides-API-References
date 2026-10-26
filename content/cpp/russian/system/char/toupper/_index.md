---
title: ToUpper()
second_title: Справочник API Aspose.Slides for C++
description: Преобразует указанный символ в верхний регистр.
type: docs
weight: 222
url: /ru/system/char/toupper/
---
## Char::ToUpper(char_t) метод


Преобразует указанный символ в верхний регистр.

```cpp
static char_t System::Char::ToUpper(char_t c)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Символ для преобразования |

### Возвращаемое значение

Указанный символ в верхнем регистре, если указанный символ является строчной буквой, иначе — указанный символ

## Char::ToUpper(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) метод


Преобразует указанный символ в верхний регистр.

```cpp
static char_t System::Char::ToUpper(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Символ для преобразования |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Объект, предоставляющий правила изменения регистра, зависящие от культуры. |

### Возвращаемое значение

Указанный символ в верхнем регистре, если указанный символ является строчной буквой, иначе — указанный символ

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [Char](../)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)