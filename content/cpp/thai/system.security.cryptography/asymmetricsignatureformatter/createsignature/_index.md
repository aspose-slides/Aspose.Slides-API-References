---
title: CreateSignature()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างลายเซ็นสำหรับข้อมูลที่ระบุ.
type: docs
weight: 1
url: /th/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) method

สร้างลายเซ็นสำหรับข้อมูลที่ระบุ.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) เพื่อคำนวณแฮชสำหรับ. |

### ค่าที่ส่งกลับ

ลายเซ็นที่คำนวณได้ในรูปแบบอาร์เรย์ของไบต์.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) method

สร้างลายเซ็นสำหรับค่าแฮชที่ระบุ.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | อัลกอริทึมแฮชที่ใช้เมื่อสร้างลายเซ็น. |

### ค่าที่ส่งกลับ

ลายเซ็นที่คำนวณได้ในรูปแบบอาร์เรย์ของไบต์.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AsymmetricSignatureFormatter](../)
* Class [HashAlgorithm](../../hashalgorithm/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)