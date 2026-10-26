---
title: X509KeyUsageExtension()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตัวสร้างเริ่มต้น.
type: docs
weight: 1
url: /th/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() ตัวสร้าง

ตัวสร้างเริ่มต้น

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) ตัวสร้าง

ตัวสร้าง

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | ข้อมูลที่เข้ารหัสของการใช้คีย์ |
| critical | **bool** | สัญญาณความสำคัญ |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) ตัวสร้าง

ตัวสร้าง

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | การใช้คีย์ |
| critical | **bool** | สัญญาณความสำคัญ |

## ดูเพิ่มเติม

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [X509KeyUsageExtension](../)
* คลาส [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* เนมสเปซ [System::Security::Cryptography::X509Certificates](../../)
* ไลบรารี [Aspose.Slides](../../../)