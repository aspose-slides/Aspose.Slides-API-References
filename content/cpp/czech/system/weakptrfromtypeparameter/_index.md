---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides pro C++ referenci API
description: Trait struktura pro převod typu argumentu na slabý ukazatel, pokud se jedná o typ ukazatele.
type: docs
weight: 2016
url: /cs/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struktura

Trait struktura pro převod typu argumentu na slabý ukazatel, pokud se jedná o typ ukazatele.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Viz také

* jmenný prostor [System](../)
* knihovna [Aspose.Slides](../../)