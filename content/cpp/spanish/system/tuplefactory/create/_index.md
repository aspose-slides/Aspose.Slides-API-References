---
title: Create()
second_title: Aspose.Slides para la referencia de la API de C++
description: Crea un nuevo objeto de tupla.
type: docs
weight: 1
url: /es/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) método


Crea un nuevo objeto tupla.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) método


Crea una nueva 8-tupla. El octavo elemento se almacena dentro de [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [Tuple](../../tuple/)
* Clase [TupleFactory](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)