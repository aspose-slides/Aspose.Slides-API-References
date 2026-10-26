---
title: IndexOf()
second_title: Aspose.Slides для C++ справочник API
description: Определяет индекс первого вхождения указанного элемента в массив.
type: docs
weight: 131
url: /ru/system/array/indexof/
---
## Array::IndexOf(const T\&) const метод

Определяет индекс первого вхождения указанного элемента в массив.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | const T\& | Индекс элемента, который необходимо определить |

### Возвращаемое значение

Индекс первого вхождения указанного элемента, если элемент найден; в противном случае -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) метод

Определяет индекс первого вхождения указанного элемента в массив.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ArrayType | Тип элементов в целевом массиве |
| ValueType | Тип элемента, который следует искать в массиве |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) для поиска указанного элемента в |
| value | const [ValueType](../valuetype/)\& | Индекс элемента, который необходимо определить |

### Возвращаемое значение

Индекс первого вхождения указанного элемента, если элемент найден; в противном случае -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) метод

Определяет индекс первого вхождения указанного элемента в массив, начиная с указанного индекса.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ArrayType | Тип элементов в целевом массиве |
| ValueType | Тип элемента, который следует искать в массиве |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) для поиска указанного элемента в |
| value | const [ValueType](../valuetype/)\& | Индекс элемента, который необходимо определить |
| startIndex | int | Индекс, с которого начинается поиск |

### Возвращаемое значение

Индекс первого вхождения указанного элемента, если элемент найден; в противном случае -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) метод

Определяет индекс первого вхождения указанного элемента в диапазон элементов массива, определяемый начальным индексом и количеством элементов в диапазоне.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ArrayType | Тип элементов в целевом массиве |
| ValueType | Тип элемента, который следует искать в массиве |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) для поиска указанного элемента в |
| value | const [ValueType](../valuetype/)\& | Индекс элемента, который необходимо определить |
| startIndex | int | Индекс, с которого начинается поиск |
| count | int | Количество элементов диапазона, в котором производится поиск |

### Возвращаемое значение

Индекс первого вхождения указанного элемента, если элемент найден; в противном случае -1

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Класс [Array](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)