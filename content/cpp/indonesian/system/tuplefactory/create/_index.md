---
title: Create()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek tuple baru.
type: docs
weight: 1
url: /id/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) metode

Membuat objek tuple baru.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) metode

Membuat 8-tuple baru. Elemen ke-8 disimpan di dalam [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Class [Tuple](../../tuple/)
* Class [TupleFactory](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)