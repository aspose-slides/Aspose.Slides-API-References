---
title: Create()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo oggetto tuple.
type: docs
weight: 1
url: /it/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) metodo

Crea un nuovo oggetto tuple.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) metodo

Crea una nuova 8-tupla. L'ottavo elemento è memorizzato all'interno di [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Tuple](../../tuple/)
* Classe [TupleFactory](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)