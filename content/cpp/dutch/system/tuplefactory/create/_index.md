---
title: Create()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw tuple-object.
type: docs
weight: 1
url: /nl/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) methode

Maakt een nieuw tuple-object.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) methode

Maakt een nieuwe 8-tuple. Het 8e element wordt opgeslagen in [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Tuple](../../tuple/)
* Klasse [TupleFactory](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)