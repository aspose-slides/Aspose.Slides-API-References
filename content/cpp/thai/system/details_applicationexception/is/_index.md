---
title: Is()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system/details_applicationexception/is/
---
## Details_ApplicationException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_ApplicationException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันเทียบกับ |

### ค่าที่คืนกลับ

True หากวัตถุเป็นประเภทที่ระบุหรือคลาสย่อยของมัน, false ในกรณีอื่น.
## หมายเหตุ


ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการเทียบเท่าตัวดำเนินการ 'is' ของ C#.
## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_ApplicationException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)