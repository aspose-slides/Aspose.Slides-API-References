---
title: DigitalSignature()
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ C++
description: สร้างอ็อบเจ็กต์ DigitalSignature ใหม่ด้วยใบรับรองที่ระบุ.
type: docs
weight: 66
url: /th/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) constructor

สร้างอ็อบเจ็กต์ [DigitalSignature](../) ใหม่ด้วยใบรับรองที่ระบุ

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | ใบรับรองที่ใช้เพื่อเซ็นลำดับสไลด์ |

## DigitalSignature::DigitalSignature(System::String, System::String) constructor

สร้างอ็อบเจ็กต์ [DigitalSignature](../) ใหม่ด้วยเส้นทางไฟล์ใบรับรองและรหัสผ่านที่ระบุ

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ที่มีใบรับรอง |
| password | [System::String](../../../system/string/) | รหัสผ่านที่จำเป็นสำหรับเข้าถึงใบรับรอง |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* คลาส [DigitalSignature](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)