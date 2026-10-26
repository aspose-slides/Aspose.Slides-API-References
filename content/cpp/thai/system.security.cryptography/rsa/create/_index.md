---
title: Create()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างการทำงานของอัลกอริธึม RSA เริ่มต้น
type: docs
weight: 183
url: /th/system.security.cryptography/rsa/create/
---
## RSA::Create() เมธอด

สร้างการทำงานของอัลกอริธึม [RSA](../) เริ่มต้น

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) เมธอด

สร้างการทำงานของอัลกอริธึม [RSA](../) เริ่มต้น

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | ต้องเป็น "System.Security.Cryptography.RSACryptoServiceProvider". |

## RSA::Create(int32_t) เมธอด

สร้างการทำงานของอัลกอริธึม [RSA](../) เริ่มต้นพร้อมขนาดคีย์ที่ระบุ

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | ขนาดคีย์, หน่วยเป็นบิต. |

## RSA::Create(const RSAParameters\&) เมธอด

สร้างการทำงานของอัลกอริธึม [RSA](../) เริ่มต้นพร้อมพารามิเตอร์ที่ระบุ

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | พารามิเตอร์สำหรับอัลกอริธึม [RSA](../). |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [RSA](../)
* คลาส [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* เนมสเปซ [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)