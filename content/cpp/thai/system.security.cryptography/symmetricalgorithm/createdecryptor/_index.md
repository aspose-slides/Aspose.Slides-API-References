---
title: CreateDecryptor()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างตัวถอดรหัสด้วยพารามิเตอร์ที่เกี่ยวข้องกับอ็อบเจ็กต์อัลกอริธึม.
type: docs
weight: 196
url: /th/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() เมธอด


สร้างตัวถอดรหัสด้วยพารามิเตอร์ที่เกี่ยวข้องกับอ็อบเจ็กต์อัลกอริธึม.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### ค่าที่ส่งคืน

อ็อบเจ็กต์ตัวถอดรหัสที่สร้างใหม่.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด


สร้างตัวถอดรหัสด้วยพารามิเตอร์โดยชัดเจน.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | คีย์ที่ใช้. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ค่าตั้งต้นที่ใช้. |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ตัวถอดรหัสที่สร้างใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICryptoTransform](../../icryptotransform/)
* คลาส [SymmetricAlgorithm](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)