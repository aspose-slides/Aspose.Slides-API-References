---
title: CreateEncryptor()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่ระบุโดยชัดเจน.
type: docs
weight: 1
url: /th/system.security.cryptography/rc2managed/createencryptor/
---
## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด

สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่ระบุโดยชัดเจน.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | คีย์การเข้ารหัสในรูปแบบอาเรย์ไบต์. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ค่าเริ่มต้นในรูปแบบอาเรย์ไบต์. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ encryptor ที่สร้างขึ้นใหม่.

## RC2Managed::CreateEncryptor() เมธอด

สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริทึม.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด

สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริทึม.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICryptoTransform](../../icryptotransform/)
* คลาส [RC2Managed](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)