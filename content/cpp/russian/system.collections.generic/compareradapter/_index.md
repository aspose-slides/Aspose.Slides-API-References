---
title: ComparerAdapter
second_title: Aspose.Slides для C++ справочник API
description: Адаптер для использования IComparer в среде STL. Использует IComparer, если установлен; в противном случае использует оператор < (если доступен) или возвращает false (если нет).
type: docs
weight: 638
url: /ru/system.collections.generic/compareradapter/
---
## ComparerAdapter структура

Adapter to use [IComparer](../icomparer/) within STL environment. Uses [IComparer](../icomparer/) if set; otherwise, uses operator < (if available) or returns false (if not).

```cpp
template<class T>class ComparerAdapter
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Type being compared. |

## Методы

| Метод | Описание |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Constructs adapter without any comparator available. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Constructs adapter. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) функция для типов, у которых доступен оператор <. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) функция для типов, у которых оператор < недоступен. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Sets comparator object. |

## См. также

* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)