---
title: Encrypt()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เข้ารหัสข้อมูลอินพุตโดยใช้โหมดการเติมที่ระบุ.
type: docs
weight: 53
url: /th/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) เมธอด

เข้ารหัสข้อมูลเข้าโดยใช้โหมดการเติมที่ระบุ.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) อาร์เรย์เพื่อเข้ารหัส. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | โหมดการเติม. |

### ค่าที่ส่งกลับ

ข้อมูลที่เข้ารหัสในรูปแบบอาร์เรย์ไบต์

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [RSAEncryptionPadding](../../rsaencryptionpadding/)
* คลาส [RSA](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)