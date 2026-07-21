---
title: LastIndexOf()
second_title: Aspose.Slides для C++ справочник API
description: Обратный поиск подстроки.
type: docs
weight: 651
url: /ru/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const метод

Обратный поиск подстроки.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | Подстрока для поиска. |
| startIndex | int | Позиция в исходной строке, с которой начинать поиск. |

### Возвращаемое значение

Индекс последней найденной подстроки или -1, если не найдено. Для пустой строки поиска всегда возвращает длину строки.

## String::LastIndexOf(const String\&, System::StringComparison) const метод

Обратный поиск подстроки.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | Подстрока для поиска. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) режим. |

### Возвращаемое значение

Индекс последней найденной подстроки или -1, если не найдено. Для пустой строки поиска всегда возвращает длину строки.

## String::LastIndexOf(const String\&, int, System::StringComparison) const метод

Обратный поиск подстроки.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../)\& | Подстрока для поиска. |
| startIndex | int | Позиция в исходной строке, с которой начинать поиск. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) режим. |

### Возвращаемое значение

Индекс последней найденной подстроки или -1, если не найдено. Для пустой строки поиска всегда возвращает длину строки.

## String::LastIndexOf(const String\&, int, int, StringComparison) const метод

Обратный поиск подстроки.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../)\& | Подстрока для поиска. |
| startIndex | int | Позиция в исходной строке, с которой начинать поиск. |
| count | int | Количество символов для просмотра. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) режим. |

### Возвращаемое значение

Индекс последней найденной подстроки или -1, если не найдено. Для пустой строки поиска всегда возвращает startIndex+count.

## String::LastIndexOf(char_t) const метод

Обратный поиск символа.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Символ для поиска. |

### Возвращаемое значение

Индекс последней позиции символа или -1, если не найдено.

## String::LastIndexOf(char_t, int32_t) const метод

Обратный поиск символа.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Символ для поиска. |
| startIndex | **int32_t** | Индекс, с которого начинать поиск. |

### Возвращаемое значение

Индекс последней позиции символа, начиная с startIndex, или -1, если не найдено.

## String::LastIndexOf(char_t, int32_t, int32_t) const метод

Обратный поиск символа.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Символ для поиска. |
| startIndex | **int32_t** | Индекс, с которого начинать поиск. |
| count | **int32_t** | Количество символов для просмотра |

### Возвращаемое значение

Индекс последней позиции символа, начиная с startIndex, или -1, если не найдено.

## См. также

* Перечисление [StringComparison](../../stringcomparison/)
* Класс [String](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)