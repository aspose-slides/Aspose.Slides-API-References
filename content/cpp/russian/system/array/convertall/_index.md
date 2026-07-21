---
title: ConvertAll()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый объект Array и заполняет его элементами указанного массива, преобразованными в тип OutputType с использованием указанного делегата-конвертера.
type: docs
weight: 625
url: /ru/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) метод

Создаёт новый объект [Array](../) и заполняет его элементами указанного массива, преобразованными в тип **OutputType** с использованием указанного делегата-конвертера.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| InputType | Тип элементов входного массива |
| OutputType | Тип элементов результирующего массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Объект [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Объект Converter, используемый для преобразования каждого элемента входного массива в эквивалентные значения типа **OutputType** |

### Возвращаемое значение

Новый массив, содержащий значения типа **OutputType**, эквивалентные значениям **input_array**.

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) метод

Создаёт новый объект [Array](../) и заполняет его элементами указанного массива, преобразованными в тип **OutputType** с использованием указанного объект-функции-конвертера.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| InputType | Тип элементов входного массива |
| OutputType | Тип элементов результирующего массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Объект [Array](../) |
| converter | std::function\<OutputType(InputType)> | Объект-функция, используемый для преобразования каждого элемента входного массива в эквивалентные значения типа **OutputType** |

### Возвращаемое значение

Новый массив, содержащий значения типа **OutputType**, эквивалентные значениям **input_array**.

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)