---
title: CreateDecryptor()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอ็อบเจ็กต์ตัวถอดรหัสด้วยพารามิเตอร์ที่ระบุโดยชัดเจน.
type: docs
weight: 14
url: /th/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

สร้างอ็อบเจ็กต์ตัวถอดรหัสด้วยพารามิเตอร์ที่ระบุโดยชัดเจน.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | คีย์การเข้ารหัสในรูปแบบอาร์เรย์ของไบต์. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ค่าตั้งต้นในรูปแบบอาร์เรย์ของไบต์. |

### Return Value

อ็อบเจ็กต์ตัวถอดรหัสที่สร้างใหม่.

## TripleDESManaged::CreateDecryptor() method

สร้างอ็อบเจ็กต์ตัวถอดรหัสด้วยพารามิเตอร์ที่กำหนดโดยออบเจ็กต์อัลกอริทึม.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

สร้างอ็อบเจ็กต์ตัวถอดรหัสด้วยพารามิเตอร์ที่กำหนดโดยออบเจ็กต์อัลกอริทึม.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICryptoTransform](../../icryptotransform/)
* คลาส [TripleDESManaged](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)