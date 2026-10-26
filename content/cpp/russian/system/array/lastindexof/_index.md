---
title: LastIndexOf()
second_title: Справочник API Aspose.Slides для C++
description: Определяет индекс последнего вхождения указанного элемента в диапазон элементов массива, заданного начальным индексом и количеством элементов в диапазоне.
type: docs
weight: 703
url: /ru/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) метод

Определяет индекс последнего вхождения указанного элемента в диапазон элементов массива, заданного начальным индексом и количеством элементов в диапазоне.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ArrayType | Тип элементов в целевом массиве |
| ValueType | тип элемента, который следует искать в массиве |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) для поиска указанного элемента в |
| value | const [ValueType](../valuetype/)\& | Индекс элемента, который необходимо определить |
| startIndex | int | Индекс, с которого начинается поиск |
| count | int | Количество элементов диапазона, в котором производится поиск |

### Возвращаемое значение

Индекс последнего вхождения указанного элемента, если элемент найден, иначе -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) метод

Определяет индекс последнего вхождения указанного элемента в массив, начиная с указанного индекса.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ArrayType | Тип элементов в целевом массиве |
| ValueType | тип элемента, который следует искать в массиве |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) для поиска указанного элемента в |
| value | const [ValueType](../valuetype/)\& | Индекс элемента, который необходимо определить |
| startIndex | int | Индекс, с которого начинается поиск |

### Возвращаемое значение

Индекс последнего вхождения указанного элемента, если элемент найден, иначе -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) метод

Определяет индекс последнего вхождения указанного элемента в массив.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ArrayType | Тип элементов в целевом массиве |
| ValueType | тип элемента, который следует искать в массиве |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) для поиска указанного элемента в |
| value | const [ValueType](../valuetype/)\& | Индекс элемента, который необходимо определить |

### Возвращаемое значение

Индекс последнего вхождения указанного элемента, если элемент найден, иначе -1

## См. также

* Тип [ArrayPtr](../../arrayptr/)
* Тип [ValueType](../valuetype/)
* Класс [Array](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)