---
title: VerifySignature()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ตรวจสอบลายเซ็น DSA สำหรับข้อมูลที่ระบุ.
type: docs
weight: 14
url: /th/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) เมธอด

ตรวจสอบลายเซ็น [DSA](../) สำหรับข้อมูลที่ระบุ.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) ที่ลงนามด้วย **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) ลายเซ็น. |

### ค่าที่ส่งกลับ

true - หาก **rgb_signature** ตรงกับลายเซ็น [DSA](../) ที่คำนวณจาก **rgb_hash**, มิฉะนั้น - false.

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* คลาส [DSA](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)