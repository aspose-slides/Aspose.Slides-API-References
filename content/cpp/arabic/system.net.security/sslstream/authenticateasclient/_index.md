---
title: AuthenticateAsClient()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بالمصادقة على جانب العميل من الاتصال.
type: docs
weight: 339
url: /ar/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) طريقة

يقوم بالمصادقة على جانب العميل من الاتصال.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | اسم الخادم الذي يشارك المثيل الحالي. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) طريقة

يقوم بالمصادقة على جانب العميل من الاتصال.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | اسم الخادم الذي يشارك المثيل الحالي. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | شهادات العميل. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | بروتوكولات SSL المستخدمة للمصادقة. |
| checkCertificateRevocation | **bool** | قيمة تشير إلى ما إذا كان يجب التحقق من قائمة إلغاء الشهادات أثناء المصادقة. |

## انظر أيضًا

* تعداد [SslProtocols](../../../system.security.authentication/sslprotocols/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [SslStream](../)
* فئة [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* مساحة اسم [System::Net::Security](../../)
* مكتبة [Aspose.Slides](../../../)