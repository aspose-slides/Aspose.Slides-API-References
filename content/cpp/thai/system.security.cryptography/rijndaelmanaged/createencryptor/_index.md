---
title: CreateEncryptor()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์แบบชัดเจน.
type: docs
weight: 1
url: /th/system.security.cryptography/rijndaelmanaged/createencryptor/
---
## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด

สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์แบบชัดเจน.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | คีย์การเข้ารหัสในรูปแบบอาร์เรย์ไบต์ |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ค่าเริ่มต้นในรูปแบบอาร์เรย์ไบต์ |

### ค่าที่คืน

อ็อบเจ็กต์ encryptor ที่สร้างขึ้นใหม่.

## RijndaelManaged::CreateEncryptor() เมธอด

สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริทึม.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด

สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริทึม.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICryptoTransform](../../icryptotransform/)
* คลาส [RijndaelManaged](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)