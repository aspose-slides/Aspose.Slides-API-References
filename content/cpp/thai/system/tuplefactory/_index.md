---
title: TupleFactory
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้เมธอดสเตติกสำหรับสร้างอ็อบเจ็กต์ tuple.
type: docs
weight: 1366
url: /th/system/tuplefactory/
---
## คลาส TupleFactory


ให้เมธอดสเตติกสำหรับสร้างอ็อบเจ็กต์ tuple

```cpp
class TupleFactory
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<Args...\>\> [Create](./create/)(Args...) | สร้างอ็อบเจ็กต์ tuple ใหม่ |
| static [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<T1, T2, T3, T4, T5, T6, T7, [SharedPtr](../sharedptr/)\<[Tuple](../tuple/)\<TRest\>\>\>\> [Create](./create/)(T1, T2, T3, T4, T5, T6, T7, TRest) | สร้าง 8-tuple ใหม่. องค์ประกอบที่ 8 จะถูกจัดเก็บไว้ภายใน [Tuple](../tuple/). |
## หมายเหตุ



```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::TupleFactory::Create(256, 16, 64);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
รายการที่ 1: 256
รายการที่ 2: 16
รายการที่ 3: 64
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)