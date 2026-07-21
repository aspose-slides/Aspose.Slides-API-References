---
title: Array()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт пустой массив.
type: docs
weight: 1
url: /ru/system/array/array/
---
## Array::Array() конструктор

Создаёт пустой массив.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) конструктор

Конструктор заполнения.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| count | int | Начальный размер массива |
| init | const T\& | Начальное значение, используемое для заполнения массива |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) конструктор

Конструктор заполнения.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ValueType | Тип начального значения |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Начальный размер массива |
| init | [ValueType](../valuetype/) | Начальное значение, используемое для заполнения массива |

## Array::Array(int, const T) конструктор

Конструктор заполнения.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| count | int | Начальный размер массива |
| inits | const T | Значения для заполнения массива |

## Array::Array(vector_t\&&) конструктор

Конструктор перемещения.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, элементы которого будут захвачены массивом |

## Array::Array(const vector_t\&) конструктор

Конструктор копирования.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector, из которого копируются значения |

## Array::Array(const std::vector\<Q\>\&) конструктор

Создаёт объект [Array](../) и заполняет его значениями, скопированными из объекта std::vector, тип элементов которого совпадает с **T**, но отличается от **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Q | Тип элементов объекта std::vector, из которого копируются элементы |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector, из которого копируются значения |

## Array::Array(std::vector\<Q\>\&&) конструктор

Создаёт объект [Array](../) и заполняет его значениями, перемещёнными из объекта std::vector, тип элементов которого совпадает с **T**, но отличается от **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Q | Тип элементов объекта std::vector, из которого перемещаются элементы |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector, из которого перемещаются значения |

## Array::Array(std::initializer_list\<UnderlyingType\>) конструктор

Создаёт объект [Array](../) и заполняет его значениями из указанного списка инициализации, содержащего элементы типа **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Список инициализации, содержащий элементы для заполнения массива |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) конструктор

Создаёт объект [Array](../) и заполняет его значениями из указанного массива, содержащего элементы типа **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| InitArraySize | Количество элементов массива **init**. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) для копирования в создаваемый массив. |

## Array::Array(std::initializer_list\<bool\>, int) конструктор

Создаёт объект [Array](../) и заполняет его значениями из указанного списка инициализации, содержащего элементы типа bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Список инициализации, содержащий элементы для заполнения массива |

## См. также

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Класс [Array](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)