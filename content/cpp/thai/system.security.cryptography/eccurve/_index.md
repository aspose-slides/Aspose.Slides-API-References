---
title: ECCurve
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: โค้งวงรีหนึ่ง.
type: docs
weight: 716
url: /th/system.security.cryptography/eccurve/
---
## ECCurve โครงสร้าง

โค้งวงรีหนึ่ง

```cpp
class ECCurve
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | สร้างโค้งจากชื่อ OID ที่เป็นมิตรที่ระบุ |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | สร้างโค้งจาก oid ที่ระบุ |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | สร้างโค้งจากค่า OID ที่ระบุ |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | รับ [Oid](../oid/) ที่แสดงถึงโค้งที่มีชื่อ |
| void [Validate](./validate/)() const | ตรวจสอบความถูกต้องของโค้งปัจจุบัน |

## Enum

| Enum | คำอธิบาย |
| --- | --- |
| [ECCurveType](./eccurvetype/) | ประเภทของโค้งวงรี |

## ดูเพิ่มเติม

* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)