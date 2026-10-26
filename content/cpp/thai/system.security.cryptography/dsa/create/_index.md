---
title: Create()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างการนำไปใช้ของอัลกอริธม DSA เริ่มต้น
type: docs
weight: 105
url: /th/system.security.cryptography/dsa/create/
---
## DSA::Create() เมธอด


สร้างการนำไปใช้ของอัลกอริธึม [DSA](../) เริ่มต้น

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```


### ผลลัพธ์

อ็อบเจ็กต์อัลกอริธึม [DSA](../).

## DSA::Create(const String\&) เมธอด


สร้างการนำไปใช้ของอัลกอริธึม [DSA](../) เริ่มต้น

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | ต้องเป็น "System.Security.Cryptography.DSACryptoServiceProvider". |

### ผลลัพธ์

อ็อบเจ็กต์อัลกอริธึม [DSA](../).

## DSA::Create(int32_t) เมธอด


สร้างการนำไปใช้ของอัลกอริธึม [DSA](../) เริ่มต้นด้วยขนาดคีย์ที่ระบุ

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | ขนาดคีย์เป็นบิต |

## DSA::Create(const DSAParameters\&) เมธอด


สร้างการนำไปใช้ของอัลกอริธึม [DSA](../) เริ่มต้นด้วยพารามิเตอร์ที่ระบุ

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | พารามิเตอร์สำหรับอัลกอริธึม [DSA](../) |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [DSA](../)
* คลาส [String](../../../system/string/)
* โครงสร้าง [DSAParameters](../../dsaparameters/)
* เนมสเปซ [System::Security::Cryptography](../../)
* ไลบรารี [Aspose.Slides](../../../)