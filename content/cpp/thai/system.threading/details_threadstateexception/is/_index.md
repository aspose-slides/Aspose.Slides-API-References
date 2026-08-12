---
title: Is()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system.threading/details_threadstateexception/is/
---
## Details_ThreadStateException::Is(const System::TypeInfo\&) const เมธอด




```cpp
bool System::Threading::Details_ThreadStateException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | โครงสร้าง [TypeInfo](../../../system/typeinfo/) ที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันเทียบกับ |

### ค่าที่ส่งคืน

True if object is of tagged type or its subclass, false otherwise.

## หมายเหตุ

ตรวจสอบว่วัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการทำงานที่คล้ายกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [Details_ThreadStateException](../)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)