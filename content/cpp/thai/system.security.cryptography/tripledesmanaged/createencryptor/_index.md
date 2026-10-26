---
title: CreateEncryptor()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่ระบุโดยชัดเจน.
type: docs
weight: 1
url: /th/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด


สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่ระบุโดยตรง.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | คีย์การเข้ารหัสในรูปแบบอาร์เรย์ไบต์. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ค่าตั้งต้นในรูปแบบอาร์เรย์ไบต์. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ encryptor ที่สร้างใหม่.

## TripleDESManaged::CreateEncryptor() เมธอด


สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริทึม.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด


สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริทึม.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* ประเภทนิยาม [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICryptoTransform](../../icryptotransform/)
* คลาส [TripleDESManaged](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)