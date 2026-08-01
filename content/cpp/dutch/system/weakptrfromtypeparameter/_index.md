---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides voor C++ API-referentie
description: Trait struct om het argumenttype te converteren naar een zwakke-pointer, als het een pointertype is.
type: docs
weight: 2016
url: /nl/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct


Trait struct om het argumenttype te converteren naar een zwakke-pointer, als het een pointertype is.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)