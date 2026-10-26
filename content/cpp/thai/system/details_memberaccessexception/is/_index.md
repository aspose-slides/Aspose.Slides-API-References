---
title: Is()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: 
type: docs
weight: 27
url: /th/system/details_memberaccessexception/is/
---
## Details_MemberAccessException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_MemberAccessException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) structure describing the type to test current object against. |

### ค่าผลลัพธ์

เป็นจริงถ้าอ็อบเจกต์เป็นประเภทที่ระบุหรือเป็นคลาสย่อยของมัน, ไม่เช่นนั้นเป็นเท็จ.
## หมายเหตุ


ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. 
## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_MemberAccessException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)