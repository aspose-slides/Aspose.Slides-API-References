---
title: Decrypt()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ถอดรหัสข้อมูลอินพุตโดยใช้โหมดการเติมที่ระบุ.
type: docs
weight: 27
url: /th/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method

ถอดรหัสข้อมูลอินพุตโดยใช้โหมดการเติมที่ระบุ.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) อาร์เรย์เพื่อถอดรหัส. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | โหมดการเติม. |

### ค่าที่ส่งกลับ

ข้อมูลที่ถอดรหัสในรูปแบบอาร์เรย์ไบต์.

## ดูเพิ่มเติม

* ประเภทนิยาม [ByteArrayPtr](../../../system/bytearrayptr/)
* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [RSAEncryptionPadding](../../rsaencryptionpadding/)
* คลาส [RSA](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)