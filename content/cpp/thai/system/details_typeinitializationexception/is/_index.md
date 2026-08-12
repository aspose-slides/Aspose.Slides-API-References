---
title: Is()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 27
url: /th/system/details_typeinitializationexception/is/
---
## Details_TypeInitializationException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_TypeInitializationException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันกับ |

### ค่าที่คืน

True หากวัตถุเป็นประเภทที่ทำเครื่องหมายหรือเป็นซับคลาสของมัน, false ในกรณีอื่น.

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการทำงานเทียบเท่าตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_TypeInitializationException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)