---
title: Create()
second_title: Aspose.Slides pro referenci API C++
description: Vytvoří nový objekt n-tice.
type: docs
weight: 1
url: /cs/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) metoda


Vytvoří nový objekt n-tice.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) metoda


Vytvoří novou 8-n-tici. 8. prvek je uložen uvnitř [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [Tuple](../../tuple/)
* Třída [TupleFactory](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)