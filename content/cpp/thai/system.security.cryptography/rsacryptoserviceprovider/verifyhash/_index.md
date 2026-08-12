---
title: VerifyHash()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตรวจสอบลายเซ็นของข้อมูล.
type: docs
weight: 222
url: /th/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) เมธอด

ตรวจสอบลายเซ็นข้อมูล

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | แฮชที่คำนวนจากข้อมูลที่รับมา |
| str | const [String](../../../system/string/)\& | ชื่อของอัลกอริธึมแฮชที่ใช้ |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ลายเซ็นที่รับมา |

### ค่าที่ส่งกลับ

True หากลายเซ็นถูกต้อง, false หากไม่ถูกต้อง

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) เมธอด

ยืนยันว่าลายเซ็นของแฮชที่ระบุเป็นค่าที่ถูกต้อง

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | ค่าการแฮชของข้อมูลที่เซ็น |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริธึมแฮช |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | โหมดการเติม. คืนค่า true หากลายเซ็นถูกต้อง, มิฉะนั้น - false. |

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)