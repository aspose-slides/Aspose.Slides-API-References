---
title: Encrypt()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เข้ารหัสข้อความ. ไม่ได้ดำเนินการ.
type: docs
weight: 118
url: /th/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) เมธอด

เข้ารหัสข้อความ ไม่ได้ทำการใช้งาน.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) เพื่อทำการเข้ารหัส. |
| use_oaep | **bool** | True เพื่อใช้การเติม OAEP, false เพื่อใช้การเติม PKCS#1 v1.5. |

### ค่าที่คืน

อาร์เรย์ข้อมูลที่เข้ารหัส.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) เมธอด

เข้ารหัสข้อมูลอินพุตโดยใช้โหมดการเติมที่ระบุ.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) อาร์เรย์เพื่อทำการเข้ารหัส. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | โหมดการเติม. |

### ค่าที่คืน

ข้อมูลที่เข้ารหัสในรูปแบบอาร์เรย์ไบต์.

## ดูเพิ่มเติม

* ประเภทกำหนด [ByteArrayPtr](../../../system/bytearrayptr/)
* ประเภทกำหนด [SharedPtr](../../../system/sharedptr/)
* คลาส [RSACryptoServiceProvider](../)
* คลาส [RSAEncryptionPadding](../../rsaencryptionpadding/)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)