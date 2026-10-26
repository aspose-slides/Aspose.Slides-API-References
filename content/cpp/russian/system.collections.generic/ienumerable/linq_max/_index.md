---
title: LINQ_Max()
second_title: Справочник API Aspose.Slides для C++
description: Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает максимальное полученное значение.
type: docs
weight: 339
url: /ru/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) метод


Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает максимальное полученное значение.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ResultType | Тип значения, возвращаемого селектором. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Функция преобразования, применяемая к каждому элементу. |

### Возвращаемое значение

Максимальное значение в последовательности.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) метод




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## См. также

* Класс [Func](../../../system/func/)
* Класс [IEnumerable](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)