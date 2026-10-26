---
title: Is()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 27
url: /th/system.security/details_securityexception/is/
---
## Details_SecurityException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Security::Details_SecurityException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) โครงสร้างที่บรรยายประเภทที่ต้องทดสอบวัตถุปัจจุบันกับ. |

### ค่าผลลัพธ์

จริงถ้าอ็อบเจ็กต์เป็นประเภทที่แท็กไว้หรือเป็นซับคลาสของมัน, มิฉะนั้นเป็นเท็จ.

## หมายเหตุ

ตรวจสอบว่ามีอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นฟังก์ชันที่คล้ายกับออปเจคต์ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [Details_SecurityException](../)
* เนมสเปซ [System::Security](../../)
* ไลบรารี [Aspose.Slides](../../../)