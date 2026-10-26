---
title: WeakPtrFromTypeParameter
second_title: Справочник API Aspose.Slides для C++
description: Трейт-структура для преобразования типа аргумента в weak-pointer, если это тип указателя.
type: docs
weight: 1990
url: /ru/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct

Трейт-структура для преобразования типа аргумента в weak-pointer, если это тип указателя.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)