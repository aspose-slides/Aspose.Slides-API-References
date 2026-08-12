---
title: VerifyHash()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ตรวจสอบลายเซ็นของข้อมูล.
type: docs
weight: 222
url: /th/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) เมธอด

ตรวจสอบลายเซ็นของข้อมูล.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash ที่คำนวนจากข้อมูลที่ได้รับ |
| str | const [String](../../../system/string/)\& | ชื่อของอัลกอริทึมแฮชที่ใช้ |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ลายเซ็นที่ได้รับมา |

### ค่าที่คืน

True หากลายเซ็นถูกต้อง, false หากไม่ถูกต้อง.

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [DSACryptoServiceProvider](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)