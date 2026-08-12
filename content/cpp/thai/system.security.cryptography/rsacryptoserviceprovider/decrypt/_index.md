---
title: Decrypt()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ถอดรหัสข้อความ. ยังไม่ได้ทำการดำเนินการ.
type: docs
weight: 105
url: /th/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method


ถอดรหัสข้อความ. ยังไม่ได้ทำการดำเนินการ.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) เพื่อถอดรหัส. |
| use_oaep | **bool** | true เพื่อใช้การเติม OAEP, false เพื่อใช้การเติม PKCS#1 v1.5. |

### ค่าที่ส่งกลับ

อาร์เรย์ข้อมูลที่ถอดรหัสแล้ว.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


ถอดรหัสข้อมูลอินพุตโดยใช้โหมดการเติมที่ระบุ.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) อาร์เรย์เพื่อถอดรหัส. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | โหมดการเติม. |

### ค่าที่ส่งกลับ

ข้อมูลที่ถอดรหัสในรูปแบบอาร์เรย์ไบต์.

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSACryptoServiceProvider](../)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)