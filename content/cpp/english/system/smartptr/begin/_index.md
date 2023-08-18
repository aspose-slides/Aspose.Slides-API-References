---
title: begin()
second_title: Aspose.Slides for C++ API Reference
description: Accessor for begin() method of an underling collection. Only compiles if SmartPtr_ is specialization type with begin() method.
type: docs
weight: 378
url: /system/smartptr/begin/
---
## SmartPtr::begin() method


Accessor for [begin()](./) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [begin()](./) method.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### Return Value

iterator to the begin of collection

## SmartPtr::begin() const method


Accessor for [begin()](./) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [begin()](./) method.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### Return Value

iterator to the begin of collection

## See Also

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)