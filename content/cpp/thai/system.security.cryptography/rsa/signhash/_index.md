---
title: SignHash()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คำนวณลายเซ็นสำหรับค่าแฮชที่ระบุ.
type: docs
weight: 144
url: /th/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) เมธอด

คำนวณลายเซ็นสำหรับค่าแฮชที่ระบุ.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | ค่าแฮช. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | อัลกอริทึมแฮช. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | โหมดการเติม. คืนค่า [RSA](../) ลายเซ็นสำหรับแฮชที่ระบุ. |

## ดูเพิ่มเติม

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [RSASignaturePadding](../../rsasignaturepadding/)
* คลาส [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* เนมสเปซ [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)