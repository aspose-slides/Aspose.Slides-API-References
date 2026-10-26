---
title: X509Extension()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คอนสตรัคเตอร์.
type: docs
weight: 1
url: /th/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) คอนสตรัคเตอร์

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | ข้อมูลที่เข้ารหัสที่เชื่อมโยงกับใบรับรอง. |
| critical | **bool** | สัญญาณความสำคัญ. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) คอนสตรัคเตอร์

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) ตัวระบุที่เชื่อมโยงกับส่วนเสริม. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลดิบที่เชื่อมโยงกับใบรับรอง. |
| critical | **bool** | สัญญาณความสำคัญ. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) คอนสตรัคเตอร์

คอนสตรัคเตอร์.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) ตัวระบุที่เชื่อมโยงกับส่วนเสริม. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | ข้อมูลดิบที่เชื่อมโยงกับใบรับรอง. |
| critical | **bool** | สัญญาณความสำคัญ. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* คลาส [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* คลาส [X509Extension](../)
* คลาส [Oid](../../../system.security.cryptography/oid/)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Security::Cryptography::X509Certificates](../../)
* ไลบรารี [Aspose.Slides](../../../)