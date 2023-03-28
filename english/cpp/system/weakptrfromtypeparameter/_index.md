---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides for C++ API Reference
description: Trait struct to convert argument type to a weak-pointer, if it is a pointer type.
type: docs
weight: 1847
url: /cpp/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct


Trait struct to convert argument type to a weak-pointer, if it is a pointer type.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
