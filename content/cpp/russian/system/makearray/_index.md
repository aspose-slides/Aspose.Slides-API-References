---
title: MakeArray()
second_title: Справка API Aspose.Slides для C++
description: Фабричная функция, создающая новый объект Array, заполняет его элементами из указанного списка инициализации и возвращает умный указатель, указывающий на объект Array.
type: docs
weight: 2003
url: /ru/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) функция

Фабричная функция, создающая новый объект [Array](../array/), заполняет его элементами из указанного списка инициализации и возвращает умный указатель, указывающий на объект [Array](../array/).

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип элементов объекта [Array](../array/), создаваемого функцией |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| init | std::initializer_list\<T\> | Список инициализации, содержащий элементы, которыми следует заполнить массив |

### Возвращаемое значение

Умный указатель, указывающий на созданный объект [Array](../array/)

## System::MakeArray(Args\&&...) функция

Фабричная функция, создающая новый объект [Array](../array/), передавая указанные аргументы его конструктору.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип элементов объекта [Array](../array/), создаваемого функцией |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Аргументы, передаваемые конструктору создаваемого объекта [Array](../array/) |

### Возвращаемое значение

Умный указатель, указывающий на созданный объект [Array](../array/)

## System::MakeArray(Integral, Args\&&...) функция

Фабричная функция, создающая новый объект [Array](../array/), передавая указанные аргументы его конструктору.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип элементов объекта [Array](../array/), создаваемого функцией |
| Integral | Тип размера массива. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| size | Integral | Размер создаваемого массива. |
| args | Args\&&... | Аргументы, передаваемые конструктору создаваемого объекта [Array](../array/) |

### Возвращаемое значение

Умный указатель, указывающий на созданный объект [Array](../array/)

## См. также

* Typedef [ArrayPtr](../arrayptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)