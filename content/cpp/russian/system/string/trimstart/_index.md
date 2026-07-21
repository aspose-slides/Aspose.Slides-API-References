---
title: TrimStart()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет все пробельные символы из начала строки.
type: docs
weight: 690
url: /ru/system/string/trimstart/
---
## String::TrimStart() const метод


Удаляет все пробельные символы из начала строки.

```cpp
String System::String::TrimStart() const
```


### Возвращаемое значение

[String](../) без пробелов в начале.

## String::TrimStart(char_t) const метод


Удаляет все вхождения переданного символа из начала строки.

```cpp
String System::String::TrimStart(char_t ch) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ch | char_t | Символ для удаления. |

### Возвращаемое значение

Результат удаления.

## String::TrimStart(const String\&) const метод


Удаляет все вхождения переданных символов из начала строки.

```cpp
String System::String::TrimStart(const String &anyOf) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) символов для удаления. |

### Возвращаемое значение

[String](../) без удалённых символов.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const метод


Удаляет все вхождения переданных символов из начала строки.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) символов для удаления. |

### Возвращаемое значение

[String](../) без удалённых символов.

## Смотрите также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [String](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)