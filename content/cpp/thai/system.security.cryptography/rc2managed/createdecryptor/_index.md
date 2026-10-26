---
title: CreateDecryptor()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: สร้างอ็อบเจ็กต์ตัวถอดรหัสด้วยพารามิเตอร์ที่ระบุโดยชัดเจน
type: docs
weight: 14
url: /th/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด


สร้างอ็อบเจ็กต์ตัวถอดรหัสด้วยพารามิเตอร์ที่ระบุโดยชัดเจน

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | คีย์การเข้ารหัสในรูปแบบอาเรย์ไบต์ |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ค่าตั้งต้นในรูปแบบอาเรย์ไบต์ |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ตัวถอดรหัสที่สร้างขึ้นใหม่

## RC2Managed::CreateDecryptor() เมธอด


สร้างอ็อบเจ็กต์ตัวถอดรหัสด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริทึม

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด


สร้างอ็อบเจ็กต์ตัวถอดรหัสด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริทึม

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICryptoTransform](../../icryptotransform/)
* คลาส [RC2Managed](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)