---
title: Is()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system.threading/details_synchronizationlockexception/is/
---
## รายละเอียด_SynchronizationLockException::Is(const System::TypeInfo\&) const เมธอด

```cpp
bool System::Threading::Details_SynchronizationLockException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบัน |

### ค่าที่ส่งคืน

True หากวัตถุเป็นประเภทที่แท็กหรือคลาสย่อยของมัน, false ในกรณีอื่น.

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่ targetType บรรยายหรือไม่. ความคล้ายคลึงกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [Details_SynchronizationLockException](../)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)