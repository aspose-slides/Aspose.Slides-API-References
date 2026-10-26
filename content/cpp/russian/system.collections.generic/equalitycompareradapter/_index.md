---
title: EqualityComparerAdapter
second_title: Aspose.Slides для C++ справочник API
description: "Адаптер, позволяющий использовать IEqualityComparer с коллекциями и алгоритмами в стиле STL. Использует IEqualityComparer, если он установлен. Если не установлен, использует оператор ==, Object::Equals или T::Equals, в зависимости от того, что доступно."
type: docs
weight: 664
url: /ru/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter структура

Адаптер, позволяющий использовать [IEqualityComparer](../iequalitycomparer/) с коллекциями и алгоритмами в стиле STL. Использует [IEqualityComparer](../iequalitycomparer/), если он установлен. Если не установлен, используется оператор ==, [Object::Equals](../../system/object/equals/) или T::Equals, в зависимости от того, что доступно.

```cpp
template<class T>class EqualityComparerAdapter
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип, который сравнивается. |
## Методы

| Метод | Описание |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Создаёт адаптер без использования какого-либо компаратора. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Создаёт адаптер с заданным компаратором. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Сравнивает два объекта. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Устанавливает компаратор. |

## См. также

* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)