---
title: Create()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ كائن tuple جديد.
type: docs
weight: 1
url: /ar/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) طريقة

ينشئ كائن tuple جديد.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) طريقة

ينشئ 8-tuple جديد. يتم تخزين العنصر الثامن داخل [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## انظر أيضًا

* Typedef [SharedPtr](../../sharedptr/)
* الفئة [Tuple](../../tuple/)
* الفئة [TupleFactory](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)