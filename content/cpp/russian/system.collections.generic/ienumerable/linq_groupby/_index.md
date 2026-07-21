---
title: LINQ_GroupBy()
second_title: Справочник API Aspose.Slides для C++
description: Группирует элементы последовательности.
type: docs
weight: 287
url: /ru/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) метод

Группирует элементы последовательности.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Key | Тип ключа, возвращаемого keyPredicate |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Функция для извлечения ключа для каждого элемента. |

### Возвращаемое значение

Объект [IEnumerable](../), содержащий последовательность объектов и ключ

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) метод

Группирует элементы последовательности.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Key | Тип ключа, возвращаемого keyPredicate |
| Element | Тип элемента, возвращаемого elementSelector |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Функция для извлечения ключа для каждого элемента. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Функция для извлечения значения ключа для каждого элемента. |

### Возвращаемое значение

Объект [IEnumerable](../), содержащий последовательность объектов и ключ

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) метод




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) метод




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IEnumerable](../)
* Класс [IGrouping](../../../system.linq/igrouping/)
* Класс [Func](../../../system/func/)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)