---
title: LINQ_Select()
second_title: Справка API Aspose.Slides для C++
description: Преобразует элементы последовательности.
type: docs
weight: 248
url: /ru/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) method

Преобразует элементы последовательности.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ResultType | Тип значения, возвращаемого **selector**. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Функция преобразования. |

### Возвращаемое значение

[IEnumerable](../), содержащий элементы, возвращённые функцией **selector**.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) method

Преобразует каждый элемент последовательности в новую форму, учитывая индекс элемента.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ResultType | Тип значения, возвращаемого **selector**. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | Функция преобразования. |

### Возвращаемое значение

[IEnumerable](../), содержащий элементы, возвращённые функцией **selector**.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IEnumerable](../)
* Класс [Func](../../../system/func/)
* Пространство имён [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)