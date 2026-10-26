---
title: ValueType
second_title: Riferimento API di Aspose.Slides per C++
description: "Tipo di memorizzazione dell'array puntato. Ha senso solo se T è una specializzazione di System::Array."
type: docs
weight: 508
url: /it/system/smartptr/valuetype/
---
## ValueType typedef

Tipo di memorizzazione dell'array puntato. Ha senso solo se T è una specializzazione di [System::Array](../../array/).

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## Vedi anche

* Classe [SmartPtr](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)