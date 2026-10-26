---
title: Create()
second_title: Aspose.Slides para Referência da API C++
description: Cria um novo objeto de tupla.
type: docs
weight: 1
url: /pt/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) método

Cria um novo objeto de tupla.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) método

Cria um novo 8-tupla. O 8º elemento é armazenado dentro de [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Ver também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Tuple](../../tuple/)
* Classe [TupleFactory](../)
* Espaço de nomes [System](../../)
* Library [Aspose.Slides](../../../)