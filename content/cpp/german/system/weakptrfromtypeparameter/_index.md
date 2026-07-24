---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides für C++ API-Referenz
description: Trait-Struct, um den Argumenttyp in einen schwachen Zeiger zu konvertieren, wenn es ein Zeigertyp ist.
type: docs
weight: 2016
url: /de/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct

Trait-Struct, um den Argumenttyp in einen schwachen Zeiger zu konvertieren, wenn es ein Zeigertyp ist.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)