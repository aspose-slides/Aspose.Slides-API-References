---
title: Is()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system/details_platformnotsupportedexception/is/
---
## รายละเอียด_PlatformNotSupportedException::Is(const System::TypeInfo\&) const เมธอด




```cpp
bool System::Details_PlatformNotSupportedException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันกับ |

### ค่าที่ส่งคืน

True หากวัตถุเป็นประเภทที่กำหนดหรือคลาสย่อยของมัน, false ในกรณีอื่น
## หมายเหตุ


ตรวจสอบว่าวัตถุเป็นอินสแทนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการจำลองของตัวดำเนินการ 'is' ของ C#.
## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_PlatformNotSupportedException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)