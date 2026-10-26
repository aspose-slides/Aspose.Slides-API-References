---
title: IndexOf()
second_title: Aspose.Slides для C++ API справочника
description: Поиск подстроки вперёд.
type: docs
weight: 625
url: /ru/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const метод

Поиск подстроки вперёд.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | Подстрока для поиска. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) режим. |

### Возвращаемое значение

Индекс первой найденной подстроки или -1, если не найдено. Для пустой строки поиска всегда возвращает 0.

## String::IndexOf(char_t, int) const метод

Поиск символа вперёд.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Символ для поиска. |
| startIndex | int | Индекс, с которого начинать поиск. |

### Возвращаемое значение

Индекс первой позиции символа, начиная с startIndex, или -1, если не найдено.

## String::IndexOf(char_t, int, int) const метод

Поиск символа вперёд в подстроке.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | char_t | Символ для поиска. |
| startIndex | int | Индекс, с которого начинать поиск. |
| count | int | Количество символов для поиска. |

### Возвращаемое значение

Индекс первой позиции символа, начиная с startIndex, или -1, если не найдено.

## String::IndexOf(const String\&, int) const метод

Поиск подстроки вперёд.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | Подстрока для поиска. |
| startIndex | int | Позиция в исходной строке, с которой начинать поиск. |

### Возвращаемое значение

Индекс первой найденной подстроки или -1, если не найдено. Для пустой строки поиска всегда возвращает startIndex.

## String::IndexOf(const String\&, int, System::StringComparison) const метод

Поиск подстроки вперёд.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | Подстрока для поиска. |
| startIndex | int | Позиция в исходной строке, с которой начинать поиск. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) режим. |

### Возвращаемое значение

Индекс первой найденной подстроки или -1, если не найдено. Для пустой строки поиска всегда возвращает startIndex.

## String::IndexOf(const String\&, int, int, System::StringComparison) const метод

Поиск подстроки вперёд.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../)\& | Подстрока для поиска. |
| startIndex | int | Позиция в исходной строке, с которой начинать поиск. |
| count | int | количество символов для поиска. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) режим. |

### Возвращаемое значение

Индекс первой найденной подстроки или -1, если не найдено. Для пустой строки поиска всегда возвращает startIndex.

## String::IndexOf(const String\&, int, int) const метод

Поиск подстроки вперёд.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | Подстрока для поиска. |
| startIndex | int | Позиция в исходной строке, с которой начинать поиск. |
| count | int | количество символов для поиска. |

### Возвращаемое значение

Индекс первой найденной подстроки или -1, если не найдено. Для пустой строки поиска всегда возвращает startIndex.

## См. также

* Перечисление [StringComparison](../../stringcomparison/)
* Класс [String](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)