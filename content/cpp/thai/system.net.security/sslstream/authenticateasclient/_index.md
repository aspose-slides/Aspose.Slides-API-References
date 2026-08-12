---
title: AuthenticateAsClient()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตรวจสอบความถูกต้องของด้านไคลเอนต์ของการเชื่อมต่อ.
type: docs
weight: 339
url: /th/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) เมธอด

ตรวจสอบความถูกต้องของด้านไคลเอนต์ของการเชื่อมต่อ.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | ชื่อของเซิร์ฟเวอร์ที่แชร์อินสแตนซ์ปัจจุบันนี้. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) เมธอด

ตรวจสอบความถูกต้องของด้านไคลเอนต์ของการเชื่อมต่อ.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | ชื่อของเซิร์ฟเวอร์ที่แชร์อินสแตนซ์ปัจจุบันนี้. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | ใบรับรองของไคลเอนต์. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | โปรโตคอล SSL ที่ใช้สำหรับการตรวจสอบความถูกต้อง. |
| checkCertificateRevocation | **bool** | ค่าที่ระบุว่าต้องตรวจสอบรายการเพิกถอนใบรับรองระหว่างการตรวจสอบความถูกต้องหรือไม่. |

## ดูเพิ่มเติม

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [SslStream](../)
* Class [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)