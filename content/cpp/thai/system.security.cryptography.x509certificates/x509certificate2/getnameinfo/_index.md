---
title: GetNameInfo()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ดึงชื่อผู้ถือหรือผู้ออกจากใบรับรอง.
type: docs
weight: 248
url: /th/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const method

ดึงชื่อผู้ถือหรือผู้ออกจากใบรับรอง.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | ตัวเลือกการจัดรูปแบบชื่อ. |
| for_issuer | **bool** | หากเป็นจริงจะคืนชื่อผู้ออก, มิฉะนั้นจะคืนชื่อผู้ถือ. |

### ค่าที่ส่งคืน

ชื่อผู้ออกหรือผู้ถือที่จัดรูปแบบแล้ว.

## ดูเพิ่มเติม

* Enum [X509NameType](../../x509nametype/)
* คลาส [String](../../../system/string/)
* คลาส [X509Certificate2](../)
* เนมสเปซ [System::Security::Cryptography::X509Certificates](../../)
* ไลบรารี [Aspose.Slides](../../../)