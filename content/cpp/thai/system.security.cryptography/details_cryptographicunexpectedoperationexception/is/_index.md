---
title: Is()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system.security.cryptography/details_cryptographicunexpectedoperationexception/is/
---
## รายละเอียด_CryptographicUnexpectedOperationException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Security::Cryptography::Details_CryptographicUnexpectedOperationException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันต่อ |

### ค่าที่ส่งกลับ

True หากวัตถุเป็นประเภทที่แท็กไว้หรือเป็นคลาสย่อยของมัน, false มิฉะนั้น.

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการทำงานเดียวกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [Details_CryptographicUnexpectedOperationException](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)