---
title: Create()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: สร้างอ็อบเจ็กต์ tuple ใหม่.
type: docs
weight: 1
url: /th/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) เมธอด


สร้างอ็อบเจ็กต์ tuple ใหม่.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) เมธอด


สร้าง 8-tuple ใหม่. องค์ประกอบที่ 8 ถูกจัดเก็บไว้ใน [Tuple](../../tuple/).

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## ดูเพิ่มเติม

* การกำหนดชนิด [SharedPtr](../../sharedptr/)
* คลาส [Tuple](../../tuple/)
* คลาส [TupleFactory](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)