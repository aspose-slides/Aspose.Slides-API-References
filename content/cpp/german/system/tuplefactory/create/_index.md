---
title: Create()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Tupelobjekt.
type: docs
weight: 1
url: /de/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) Methode

Erstellt ein neues Tupelobjekt.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) Methode

Erstellt ein neues 8-Tupel. Das 8. Element wird innerhalb von [Tuple](../../tuple/) gespeichert.

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Tuple](../../tuple/)
* Klasse [TupleFactory](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)