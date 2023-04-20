---
title: cbegin()
second_title: Aspose.Slides for C++ API Reference
description: Accessor for cbegin() method of an underling collection. Only compiles if SmartPtr_ is specialization type with cbegin() method.
type: docs
weight: 404
url: /cpp/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const method


Accessor for [cbegin()](./) method of an underling collection. Only compiles if SmartPtr_ is specialization type with [cbegin()](./) method.

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```


### Return Value

iterator to the begin of collection

## See Also

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)