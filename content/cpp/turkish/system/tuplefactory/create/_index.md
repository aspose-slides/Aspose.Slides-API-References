---
title: Create()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir tuple nesnesi oluşturur.
type: docs
weight: 1
url: /tr/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) metot


Yeni bir tuple nesnesi oluşturur.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) metot


Yeni bir 8-tuple oluşturur. 8. öğe [Tuple](../../tuple/) içinde depolanır.

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Ayrıca bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Tuple](../../tuple/)
* Sınıf [TupleFactory](../)
* Ad alanı [System](../../)
* Library [Aspose.Slides](../../../)