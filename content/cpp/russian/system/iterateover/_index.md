---
title: IterateOver()
second_title: Справочник API Aspose.Slides для C++
description: "Это свойство-функция оборачивает перечислимый (или итерируемый) объект, чтобы его можно было использовать в цикле range-based for. Эта перегрузка для Enumerable без методов begin(), end() с аргументом типа-цели для (auto& value : IterateOver<SomeType>(enumerable))."
type: docs
weight: 2432
url: /ru/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) функция


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable without begin(), end() methods with target type argument for (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The target type, it has to be returned from iterator |
| Enumerable | The type of a wrapped object |

## System::IterateOver(System::SmartPtr\<Enumerable\>) функция


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable without begin(), end() methods with default target type argument for (auto& value : IterateOver(enumerable)) analog to the following C# code foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Enumerable | The type of a wrapped object |

## System::IterateOver(System::SmartPtr\<Enumerable\>) функция


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable with begin(), end() methods with default target type argument for (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Enumerable | The type of a wrapped object |

## System::IterateOver(System::SmartPtr\<Enumerable\>) функция


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable with begin(), end() methods with target type same as original value_type of iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Enumerable | The type of a wrapped object |
| T | The target type which has to returned from iterator |

## System::IterateOver(System::SmartPtr\<Enumerable\>) функция


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable with begin(), end() methods with different target type and original value_type of iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Enumerable | The type of a wrapped object |
| T | The target type which has to returned from iterator |

## System::IterateOver(const Enumerable *) функция


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable this with default target type.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Enumerable | The type of a wrapped object |

## System::IterateOver(const Enumerable *) функция


This function property wraps enumerable (or iterable) object so it can be used with range-based for loop This overload for Enumerable without begin(), end() methods with target type argument for (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The target type, it has to be returned from iterator |
| Enumerable | The type of a wrapped object |

## См. также

* Класс [SmartPtr](../smartptr/)
* Структура [IsSmartPtr](../issmartptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)