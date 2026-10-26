---
title: CreateEncryptor()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างตัวเข้ารหัสพร้อมพารามิเตอร์ที่สัมพันธ์กับอ็อบเจ็กต์ของอัลกอริทึม
type: docs
weight: 183
url: /th/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() เมธอด

สร้างตัวเข้ารหัสด้วยพารามิเตอร์ที่สัมพันธ์กับอ็อบเจ็กต์ของอัลกอริทึม

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

### ค่าที่ส่งกลับ

Newly created encryptor object.

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด

สร้างตัวเข้ารหัสด้วยพารามิเตอร์ที่กำหนดโดยชัดเจน

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | คีย์ที่ใช้ |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ค่าเริ่มต้นที่ใช้ |

### ค่าที่ส่งกลับ

Newly created encryptor object.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)