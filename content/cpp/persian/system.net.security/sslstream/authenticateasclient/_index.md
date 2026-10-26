---
title: AuthenticateAsClient()
second_title: مرجع API Aspose.Slides برای C++
description: احراز هویت سمت کلاینت اتصال.
type: docs
weight: 339
url: /fa/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) متد


احراز هویت سمت کلاینت اتصال.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | نام سروری که نمونهٔ جاری را به اشتراک می‌گذارد. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) متد


احراز هویت سمت کلاینت اتصال.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | نام سروری که نمونهٔ جاری را به اشتراک می‌گذارد. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | گواهی‌های کلاینت. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | پروتکل‌های SSL که برای احراز هویت استفاده می‌شوند. |
| checkCertificateRevocation | **bool** | مقداری که نشان می‌دهد آیا فهرست لغو گواهی باید در هنگام احراز هویت بررسی شود یا خیر. |

## ملاحظات

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [SslStream](../)
* Class [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)