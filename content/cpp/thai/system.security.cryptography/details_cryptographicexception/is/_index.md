---
title: Is()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system.security.cryptography/details_cryptographicexception/is/
---
## รายละเอียด_CryptographicException::Is(const System::TypeInfo\&) const เมธอด

```cpp
bool System::Security::Cryptography::Details_CryptographicException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันเทียบกับ |

### ค่าที่ส่งคืน

True หากวัตถุเป็นประเภทที่มีแท็กหรือเป็นคลาสย่อยของประเภทนั้น, false หากไม่เป็น

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. การเทียบเท่ากับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [Details_CryptographicException](../)
* เนมส페ซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)