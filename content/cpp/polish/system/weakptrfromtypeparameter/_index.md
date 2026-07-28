---
title: WeakPtrFromTypeParameter
second_title: Referencja API Aspose.Slides dla C++
description: Struktura cech służąca do konwersji typu argumentu na słaby wskaźnik, jeśli jest to typ wskaźnika.
type: docs
weight: 2016
url: /pl/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct


Struktura cech do konwertowania typu argumentu na słaby wskaźnik, jeśli jest to typ wskaźnika.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)