---
title: Create()
second_title: Aspose.Slides for C++ API referenciája
description: Új tuple objektumot hoz létre.
type: docs
weight: 1
url: /hu/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) metódus


Új tuple objektumot hoz létre.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) metódus


Új 8-tuple-t hoz létre. A 8. elem a [Tuple](../../tuple/) belsejében van tárolva.

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Tuple](../../tuple/)
* Osztály [TupleFactory](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)