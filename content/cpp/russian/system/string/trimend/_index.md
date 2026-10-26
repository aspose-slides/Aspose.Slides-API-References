---
title: TrimEnd()
second_title: Aspose.Slides для C++ API
description: Удаляет все пробельные символы с конца строки.
type: docs
weight: 703
url: /ru/system/string/trimend/
---
## String::TrimEnd() const метод

Удаляет все пробельные символы с конца строки.

```cpp
String System::String::TrimEnd() const
```

### Возвращаемое значение

[String](../) без пробелов в начале.

## String::TrimEnd(char_t) const метод

Удаляет все вхождения переданного символа с конца строки.

```cpp
String System::String::TrimEnd(char_t ch) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ch | char_t | Символ для удаления. |

### Возвращаемое значение

Результат удаления.

## String::TrimEnd(const String\&) const метод

Удаляет все вхождения переданных символов с конца строки.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) символов для удаления. |

### Возвращаемое значение

[String](../) без удалённых символов.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const метод

Удаляет все вхождения переданных символов с конца строки.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) символов для удаления. |

### Возвращаемое значение

[String](../) без удалённых символов.

## См. также

* Тип [ArrayPtr](../../arrayptr/)
* Класс [String](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)