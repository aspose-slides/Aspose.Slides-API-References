---
title: LINQ_Min()
second_title: Справочник API Aspose.Slides для C++
description: Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает минимальное полученное значение.
type: docs
weight: 326
url: /ru/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) метод


Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает минимальное полученное значение.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| ResultType | Тип значения, возвращаемого selector. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Функция преобразования, применяемая к каждому элементу. |

### Возвращаемое значение

Минимальное значение в последовательности.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) метод




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## См. также

* Класс [Func](../../../system/func/)
* Класс [IEnumerable](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)