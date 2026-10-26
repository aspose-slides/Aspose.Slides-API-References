---
title: Equals()
second_title: Aspose.Slides для C++ — справочник API
description: Сравнение строк на равенство. Поддерживается несколько режимов, предоставляемых перечислением StringComparison.
type: docs
weight: 391
url: /ru/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const метод


[String](../) сравнение на равенство. Поддерживаются несколько режимов, предоставляемых перечислением StringComparison.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) для сравнения с текущей. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) режим (см. [System::StringComparison](../../stringcomparison/) для подробностей). |

### Возвращаемое значение

true, если строки совпадают при использовании выбранного типа сравнения, иначе false.

## String::Equals(const String\&) const метод


[String](../) сравнение на равенство. Использует режим сравнения [System::StringComparison::Ordinal](../../stringcomparison/).

```cpp
bool System::String::Equals(const String &str) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) для сравнения с текущей. |

### Возвращаемое значение

true, если строки совпадают, иначе false.

## String::Equals(const String\&, const String\&) метод


Проводит сравнение двух строк с использованием режима сравнения Ordial.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| strA | const [String](../)\& | Первая строка для сравнения. |
| strB | const [String](../)\& | Вторая строка для сравнения. |

### Возвращаемое значение

true, если строки совпадают, иначе false.

## String::Equals(const String\&, const String\&, System::StringComparison) метод


Сравнивает две строки.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| strA | const [String](../)\& | Первая строка для сравнения. |
| strB | const [String](../)\& | Вторая строка для сравнения. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) режим. |

### Возвращаемое значение

true, если строки совпадают, иначе false.

## См. также

* Enum [StringComparison](../../stringcomparison/)
* Класс [String](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)