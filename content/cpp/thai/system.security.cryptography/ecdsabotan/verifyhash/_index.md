---
title: VerifyHash()
second_title: Aspose.Slides สำหรับ API C++
description: ตรวจสอบลายเซ็นของข้อมูล.
type: docs
weight: 183
url: /th/system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash(ByteArrayPtr, ByteArrayPtr) method

Checks data signature.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | แฮชที่คำนวณจากข้อมูลที่ได้รับ. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | ลายเซ็นตามที่ได้รับ. |

### ค่าที่คืน

True หากลายเซ็นถูกต้อง, false ในกรณีอื่น.

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* คลาส [ECDsaBotan](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)