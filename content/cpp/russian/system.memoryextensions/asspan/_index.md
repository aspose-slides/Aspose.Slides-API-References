---
title: AsSpan()
second_title: Справочник API Aspose.Slides для C++
description: Создает спан из массива.
type: docs
weight: 1
url: /ru/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) функция


Создает спан из массива.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в массиве. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | Исходный массив. |
| start | **int32_t** | Начальный индекс в массиве. |
| length | **int32_t** | Длина спана. |

### Возвращаемое значение

Span<T>, охватывающий указанную часть массива.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) функция


Создает только для чтения спан из строки.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | Исходная строка. |
| start | **int32_t** | Начальный индекс в строке. |
| length | **int32_t** | Длина спана. |

### Возвращаемое значение

ReadOnlySpan<char16_t>, охватывающий указанную часть строки.

## См. также

* Тип-определение [ArrayPtr](../../system/arrayptr/)
* Класс [Span](../../system/span/)
* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [String](../../system/string/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)