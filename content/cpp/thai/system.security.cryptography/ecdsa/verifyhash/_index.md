---
title: VerifyHash()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบลายเซ็นของข้อมูล.
type: docs
weight: 118
url: /th/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) เมธอด

ตรวจสอบลายเซ็นของข้อมูล.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | แฮชที่คำนวณจากข้อมูลที่ได้รับ. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | ลายเซ็นที่ได้รับ. |

### ค่าที่ส่งคืน

True หากลายเซ็นถูกต้อง, false หากไม่.

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)