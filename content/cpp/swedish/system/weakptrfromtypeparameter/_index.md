---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides för C++ API-referens
description: Trait-struct för att konvertera argumenttypen till en svag pekare, om den är en pekartyp.
type: docs
weight: 2016
url: /sv/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct

Trait-struct för att konvertera argumenttypen till en svag pekare, om den är en pekartyp.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)