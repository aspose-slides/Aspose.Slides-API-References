---
title: Is()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: 
type: docs
weight: 27
url: /th/system/details_invalidoperationexception/is/
---
## รายละเอียด_InvalidOperationException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_InvalidOperationException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันเทียบกับ |

### ค่าที่ส่งคืน

True หากวัตถุเป็นประเภทที่แท็กไว้หรือคลาสย่อยของมัน, false ในกรณีอื่น.

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. ตรงกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_InvalidOperationException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)