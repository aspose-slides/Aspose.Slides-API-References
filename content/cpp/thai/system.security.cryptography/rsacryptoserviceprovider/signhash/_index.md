---
title: SignHash()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: คำนวณลายเซ็นสำหรับค่าแฮชที่ระบุ.
type: docs
weight: 196
url: /th/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) เมธอด


คำนวณลายเซ็นสำหรับค่าแฮชที่ระบุ.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | ค่าแฮช |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | อัลกอริธึมแฮช |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | โหมดการเติมเต็ม ส่งคืนลายเซ็น [RSA](../../rsa/) สำหรับค่าแฮชที่ระบุ |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) เมธอด


คำนวณลายเซ็นของค่าป้อนเข้าที่ระบุ ยังไม่ได้ดำเนินการ.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ค่าแฮชของข้อมูลที่ต้องการลงลายเซ็น |
| str | const [String](../../../system/string/)\& | ตัวระบุอัลกอริธึมแฮชที่ใช้สร้างแฮช |

### ค่าที่ส่งกลับ

[RSA](../../rsa/) ลายเซ็นสำหรับข้อมูลที่ระบุ.

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)