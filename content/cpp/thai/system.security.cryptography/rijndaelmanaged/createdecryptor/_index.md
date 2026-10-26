---
title: CreateDecryptor()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้างอ็อบเจกต์ decryptor ด้วยพารามิเตอร์ที่ระบุอย่างชัดเจน.
type: docs
weight: 14
url: /th/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด

สร้างอ็อบเจกต์ decryptor ด้วยพารามิเตอร์ที่ระบุอย่างชัดเจน.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | คีย์การเข้ารหัสในรูปแบบอาร์เรย์ไบต์. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ค่าเริ่มต้นในรูปแบบอาร์เรย์ไบต์. |

### ค่าที่ส่งคืน

อ็อบเจกต์ decryptor ที่สร้างใหม่.

## RijndaelManaged::CreateDecryptor() เมธอด

สร้างอ็อบเจกต์ decryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจกต์อัลกอริทึม.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) เมธอด

สร้างอ็อบเจกต์ decryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจกต์อัลกอริทึม.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICryptoTransform](../../icryptotransform/)
* คลาส [RijndaelManaged](../)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)