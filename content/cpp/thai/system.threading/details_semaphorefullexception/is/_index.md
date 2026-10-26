---
title: Is()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: 
type: docs
weight: 27
url: /th/system.threading/details_semaphorefullexception/is/
---
## รายละเอียด_SemaphoreFullException::Is(const System::TypeInfo\&) const เมธอด




```cpp
bool System::Threading::Details_SemaphoreFullException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อใช้ทดสอบวัตถุปัจจุบันกับ |

### ค่าที่ส่งคืน

True หากวัตถุเป็นประเภทที่ทำเครื่องหมายหรือเป็นคลาสย่อยของประเภทนั้น, false ในกรณีอื่น

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการทำงานที่คล้ายกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [Details_SemaphoreFullException](../)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)