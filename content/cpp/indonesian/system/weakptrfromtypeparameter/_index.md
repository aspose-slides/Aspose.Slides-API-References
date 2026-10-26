---
title: WeakPtrFromTypeParameter
second_title: Referensi API Aspose.Slides untuk C++
description: Trait struct untuk mengonversi tipe argumen menjadi weak-pointer, jika itu tipe pointer.
type: docs
weight: 2016
url: /id/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct

Struct trait untuk mengonversi tipe argumen menjadi weak-pointer, jika itu tipe pointer.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Lihat Juga

* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)