---
title: VerifyHash()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่าลายเซ็นของแฮชที่ระบุเป็นค่าที่ถูกต้อง
type: docs
weight: 170
url: /th/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) เมธอด

ตรวจสอบว่าลายเซ็นของแฮชที่ระบุเป็นค่าที่ถูกต้อง

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | ค่าแฮชของข้อมูลที่ลงลายเซ็น |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | ข้อมูลลายเซ็น |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | อัลกอริทึมแฮช |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | โหมดการเติมเต็ม. คืนค่า true หากลายเซ็นถูกต้อง, มิฉะนั้น - false |

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)