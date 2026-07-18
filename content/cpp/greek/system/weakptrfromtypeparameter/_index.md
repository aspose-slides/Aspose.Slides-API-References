---
title: WeakPtrFromTypeParameter
second_title: Αναφορά API Aspose.Slides για C++
description: Δομή χαρακτηριστικού για μετατροπή του τύπου ορίσματος σε αδύναμο δείκτη, εάν είναι τύπος δείκτη.
type: docs
weight: 1990
url: /el/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct

Δομή χαρακτηριστικού για μετατροπή του τύπου ορίσματος σε αδύναμο δείκτη, εάν είναι τύπος δείκτη.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)