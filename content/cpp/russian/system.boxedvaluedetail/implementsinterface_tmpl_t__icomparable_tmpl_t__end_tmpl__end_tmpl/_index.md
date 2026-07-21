---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides для C++ справка по API
description: Шаблонный предикат, который проверяет, должен ли упакованный объект сам реализовывать интерфейс IComparable.
type: docs
weight: 53
url: /ru/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


Шаблонный предикат, который проверяет, должен ли упакованный объект сам реализовывать интерфейс [IComparable](../../system/icomparable/).

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## См. также

* Пространство имён [System::BoxedValueDetail](../)
* Библиотека [Aspose.Slides](../../)