---
title: Trim()
second_title: Aspose.Slides для C++ API справка
description: Удаляет все пробельные символы в начале и в конце строки.
type: docs
weight: 677
url: /ru/system/string/trim/
---
## String::Trim() const метод


Удаляет все пробельные символы как в начале, так и в конце строки.

```cpp
String System::String::Trim() const
```


### Возвращаемое значение

[String](../) без пробелов в начале и в конце.

## String::Trim(char_t) const метод


Удаляет все вхождения переданного символа как в начале, так и в конце строки.

```cpp
String System::String::Trim(char_t ch) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ch | char_t | Символ для удаления. |

### Возвращаемое значение

Результат удаления.

## String::Trim(const String\&) const метод


Удаляет все вхождения переданных символов как в начале, так и в конце строки.

```cpp
String System::String::Trim(const String &anyOf) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) символов для удаления. |

### Возвращаемое значение

[String](../) без удалённых символов.

## String::Trim(const ArrayPtr\<char_t\>\&) const метод


Удаляет все вхождения переданных символов как в начале, так и в конце строки.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) символов для удаления. |

### Возвращаемое значение

[String](../) без удалённых символов.

## См. также

* Типовое определение [ArrayPtr](../../arrayptr/)
* Класс [String](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)