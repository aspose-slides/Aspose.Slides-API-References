---
title: Compare()
second_title: Aspose.Slides для C++ справка API
description: Сравнивает строки. Не реализовано.
type: docs
weight: 66
url: /ru/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String&, const String&) const метод

Сравнивает строки. Не реализовано.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)& | LHS строка. |
| string2 | const [String](../../../system/string/)& | RHS строка. |

### Возвращаемое значение

Отрицательное значение, если строка LHS предшествует строке RHS, ноль, если они совпадают, положительное значение в остальных случаях.

## CompareInfo::Compare(const String&, const String&, CompareOptions) const метод

Сравнивает строки. Поддерживаются только режимы Ordinal и OrdinalIgnoreCase.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const [String](../../../system/string/)& | LHS строка. |
| b | const [String](../../../system/string/)& | RHS строка. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) тип сравнения. |

### Возвращаемое значение

Отрицательное значение, если строка LHS предшествует строке RHS, ноль, если они совпадают, положительное значение в остальных случаях.

## CompareInfo::Compare(const String&, int, int, const String&, int, int) const метод

Сравнивает часть одной строки с частью второй строки. Не реализовано.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)& | Первая строка. |
| offset1 | int | Начальный индекс символов в **string1**. |
| length1 | int | Количество символов в **string1**, которые нужно сравнить. |
| string2 | const [String](../../../system/string/)& | Вторая строка. |
| offset2 | int | Начальный индекс символов в **string2**. |
| length2 | int | Количество символов в **string2**, которые нужно сравнить. |

### Возвращаемое значение

Отрицательное значение, если часть первой строки предшествует части второй строки, ноль, если они совпадают, положительное значение в остальных случаях.

## CompareInfo::Compare(const String&, int, const String&, int, CompareOptions) const метод

Сравнивает конечную часть одной строки с конечной частью второй строки, используя методы сравнения строк. Не реализовано.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)& | Первая строка. |
| offset1 | int | Начальный индекс символов в **string1**. |
| string2 | const [String](../../../system/string/)& | Вторая строка. |
| offset2 | int | Начальный индекс символов в **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) параметры сравнения. |

### Возвращаемое значение

Отрицательное значение, если часть первой строки предшествует части второй строки, ноль, если они совпадают, положительное значение в остальных случаях.

## CompareInfo::Compare(const String&, int, const String&, int) const метод

Сравнивает конечную часть одной строки с конечной частью второй строки. Не реализовано.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)& | Первая строка. |
| offset1 | int | Начальный индекс символов в **string1**. |
| string2 | const [String](../../../system/string/)& | Вторая строка. |
| offset2 | int | Начальный индекс символов в **string2**. |

### Возвращаемое значение

Отрицательное значение, если часть первой строки предшествует части второй строки, ноль, если они совпадают, положительное значение в остальных случаях.

## CompareInfo::Compare(const String&, int, int, const String&, int, int, CompareOptions) const метод

Сравнивает часть одной строки с частью второй строки, используя методы сравнения строк. Не реализовано.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)& | Первая строка. |
| offset1 | int | Начальный индекс символов в **string1**. |
| length1 | int | Количество символов в **string1**, которые нужно сравнить. |
| string2 | const [String](../../../system/string/)& | Вторая строка. |
| offset2 | int | Начальный индекс символов в **string2**. |
| length2 | int | Количество символов в **string2**, которые нужно сравнить. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) параметры сравнения. |

### Возвращаемое значение

Отрицательное значение, если часть первой строки предшествует части второй строки, ноль, если они совпадают, положительное значение в остальных случаях.

## См. также

* Enum [CompareOptions](../../compareoptions/)
* Класс [String](../../../system/string/)
* Класс [CompareInfo](../)
* Пространство имён [System::Globalization](../../)
* Библиотека [Aspose.Slides](../../../)