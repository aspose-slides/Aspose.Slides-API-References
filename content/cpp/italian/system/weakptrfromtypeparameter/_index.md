---
title: WeakPtrFromTypeParameter
second_title: Riferimento API di Aspose.Slides per C++
description: Struct trait per convertire il tipo dell'argomento in un puntatore debole, se è un tipo puntatore.
type: docs
weight: 2016
url: /it/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct


Struct trait per convertire il tipo dell'argomento in un puntatore debole, se è un tipo puntatore.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)