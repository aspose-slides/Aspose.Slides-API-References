---
title: AuthenticateAsClient()
second_title: Aspose.Slides için C++ API Referansı
description: Bağlantının istemci tarafını kimlik doğrular.
type: docs
weight: 339
url: /tr/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) yöntemi

Bağlantının istemci tarafını kimlik doğrular.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Mevcut örneği paylaşan sunucunun adı. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) yöntemi

Bağlantının istemci tarafını kimlik doğrular.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Mevcut örneği paylaşan sunucunun adı. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | İstemci sertifikaları. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | Kimlik doğrulama için kullanılan SSL protokolleri. |
| checkCertificateRevocation | **bool** | Kimlik doğrulama sırasında sertifika iptal listesi kontrol edilmesi gerekip gerekmediğini belirten bir değer. |

## İlgili

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [SslStream](../)
* Sınıf [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* İsim Alanı [System::Net::Security](../../)
* Kütüphane [Aspose.Slides](../../../)