---
title: Create()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt tupelobjekt.
type: docs
weight: 1
url: /sv/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) metod

Skapar ett nytt tupelobjekt.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) metod

Skapar en ny 8-tupel. Det åttonde elementet lagras inuti [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* klass [Tuple](../../tuple/)
* klass [TupleFactory](../)
* namnrymd [System](../../)
* Library [Aspose.Slides](../../../)