---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides C++ API referencia
description: Trait struktúra az argumentum típus gyenge mutatóvá konvertálásához, ha az mutató típus.
type: docs
weight: 2016
url: /hu/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct

Trait struct az argumentum típus gyenge mutatóvá konvertálásához, ha az mutató típus.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)