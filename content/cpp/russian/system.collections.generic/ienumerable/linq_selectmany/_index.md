---
title: LINQ_SelectMany()
second_title: Справочник API Aspose.Slides для C++
description: Проецирует каждый элемент последовательности и объединяет полученные последовательности в одну последовательность.
type: docs
weight: 300
url: /ru/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) метод

Проецирует каждый элемент последовательности и объединяет полученные последовательности в одну последовательность.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| ResultType | Тип значения, возвращаемого **selector**. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Функция преобразования. |

### Возвращаемое значение

Объект [IEnumerable](../), содержащий результат вызова функции проекции один-к-многим для каждого элемента входной последовательности.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) метод

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IEnumerable](../)
* Класс [Func](../../../system/func/)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)