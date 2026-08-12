---
title: Is()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: 
type: docs
weight: 27
url: /th/system.security.authentication/details_authenticationexception/is/
---
## รายละเอียด_AuthenticationException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Security::Authentication::Details_AuthenticationException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันต่อ. |

### ค่าที่ส่งคืน

จริงถ้าวัตถุเป็นประเภทที่กำหนดหรือคลาสย่อยของมัน, เท็จในกรณีอื่น.

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินส턴ซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นที่คล้ายกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [Details_AuthenticationException](../)
* เนมสเปซ [System::Security::Authentication](../../)
* ไลบรารี [Aspose.Slides](../../../)