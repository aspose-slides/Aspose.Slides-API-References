---
title: GetCertContentType()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับประเภทรูปแบบใบรับรองที่อยู่ในอาร์เรย์ไบต์ที่ระบุ.
type: docs
weight: 391
url: /th/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) เมธอด

รับประเภทรูปแบบใบรับรองที่อยู่ในอาร์เรย์ไบต์ที่ระบุ.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Certificate data. |

### ค่าที่ส่งคืน

ประเภทของใบรับรอง X.509.

## X509Certificate2::GetCertContentType(const String\&) เมธอด

รับประเภทรูปแบบใบรับรองที่อยู่ในไฟล์ที่ระบุ.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Certificate file name. |

### ค่าที่ส่งคืน

ประเภทของใบรับรอง X.509.

## ดูเพิ่มเติม

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* คลาส [X509Certificate2](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)