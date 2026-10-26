---
title: operator()()
second_title: Aspose.Slides для C++ API Reference
description: Функция сравнения для типов, у которых доступен оператор <.
type: docs
weight: 27
url: /ru/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const метод


[Comparison](../../../system/comparison/) функция для типов с доступным оператором <.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Q | Тип сравниваемых объектов; шаблон для проверки доступности преобразования типа. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const Q\& | Первое значение для сравнения. |
| y | const Q\& | Второе значение для сравнения. |

### Возвращаемое значение

True если **x** считается меньшим, чем **y**, иначе false.

## ComparerAdapter::operator()(const Q\&, const Q\&) const метод


[Comparison](../../../system/comparison/) функция для типов без доступного оператора <.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Q | Тип сравниваемых объектов; шаблон для проверки доступности преобразования типа. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | const Q\& | Первое значение для сравнения. |
| y | const Q\& | Второе значение для сравнения. |

### Возвращаемое значение

True если компаратор установлен и **x** считается меньшим, чем **y**, иначе false.

## См. также

* Структура [ComparerAdapter](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)