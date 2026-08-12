---
title: LINQ_All()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าทุกองค์ประกอบของลำดับใด ๆ ตรงตามเงื่อนไขหรือไม่.
type: docs
weight: 144
url: /th/system.collections.generic/ienumerable/linq_all/
---
## IEnumerable::LINQ_All(std::function\<bool(T)>) เมธอด


กำหนดว่าทุกองค์ประกอบของลำดับใด ๆ ตรงตามเงื่อนไขหรือไม่.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_All(std::function<bool(T)> predicate)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | ฟังก์ชันที่ใช้ทดสอบแต่ละองค์ประกอบตามเงื่อนไข. |

### ค่าที่ส่งคืน

true หากทุกองค์ประกอบของลำดับต้นฉบับผ่านการทดสอบตามตัวทำนายที่ระบุ, หรือหากลำดับว่าง; มิฉะนั้น, false.

## ดูเพิ่มเติม

* คลาส [IEnumerable](../)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)