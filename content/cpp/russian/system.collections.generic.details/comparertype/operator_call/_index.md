---
title: operator()()
second_title: Aspose.Slides для C++ справочник API
description: Сравнивает типы значений, реализующие интерфейс IComparable.
type: docs
weight: 1
url: /ru/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const метод

Сравнивает типы значений, реализующие [IComparable](../../../system/icomparable/) interface.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| Q | Type to compare. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | LHS value. |
| b | const Q\& | RHS value. |

### Возвращаемое значение

Истина, если **a** считается меньше **b**, иначе ложь.

## ComparerType::operator()(const Q\&, const Q\&) const метод

Сравнивает примитивные типы значений и объекты, не реализующие [IComparable](../../../system/icomparable/) interface.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| Q | Type to compare. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | LHS value. |
| b | const Q\& | RHS value. |

### Возвращаемое значение

Истина, если **a** считается меньше **b**, иначе ложь.

## ComparerType::operator()(const Q\&, const Q\&) const метод

Сравнивает типы с плавающей запятой.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| Q | Type to compare. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| a | const Q\& | LHS value. |
| b | const Q\& | RHS value. |

### Возвращаемое значение

Истина, если **a** считается меньше **b**, иначе ложь.

## См. также

* Класс [IComparable](../../../system/icomparable/)
* Структура [has_method_compareto](../../has_method_compareto/)
* Структура [ComparerType](../)
* Пространство имён [System::Collections::Generic::Details](../../)
* Библиотека [Aspose.Slides](../../../)