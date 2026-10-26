---
title: VerifySignature()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบลายเซ็น DSA สำหรับข้อมูลที่ระบุ.
type: docs
weight: 118
url: /th/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) เมธอด

ตรวจสอบลายเซ็น [DSA](../../dsa/) สำหรับข้อมูลที่ระบุ.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) ที่เซ็นด้วย **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) ลายเซ็น. |

### Return Value

true - หาก **rgb_signature** ตรงกับลายเซ็น [DSA](../../dsa/) ที่คำนวณจาก **rgb_hash**, ไม่เช่นนั้น - false.

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* คลาส [DSACryptoServiceProvider](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)