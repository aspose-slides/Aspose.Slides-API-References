---
title: CompareOrdinal()
second_title: Aspose.Slides для C++ справочник API
description: Сравнивает две строки в ординальном режиме, возвращая значение меньше, равно или больше.
type: docs
weight: 833
url: /ru/system/string/compareordinal/
---
## String::CompareOrdinal(const String&, const String&) метод

Сравнивает две строки в ординальном режиме, возвращая значение меньше, равно или больше.

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| strA | const [String](../)\& | Первая строка для сравнения. |
| strB | const [String](../)\& | Вторая строка для сравнения. |

### Возвращаемое значение

Отрицательное значение, если первая подстрока меньше второй; ноль, если они совпадают; положительное значение в остальных случаях.

## String::CompareOrdinal(const String&, int, const String&, int, int) метод

Сравнивает две строки в ординальном режиме, возвращая значение меньше, равно или больше.

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| strA | const [String](../)\& | Первая строка для сравнения. |
| indexA | int | Начало подстроки первой строки. |
| strB | const [String](../)\& | Вторая строка для сравнения. |
| indexB | int | Начало подстроки второй строки. |
| length | int | Количество символов для сравнения. |

### Возвращаемое значение

Отрицательное значение, если первая подстрока меньше второй; ноль, если они совпадают; положительное значение в остальных случаях.

## Смотрите также

* Класс [String](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)