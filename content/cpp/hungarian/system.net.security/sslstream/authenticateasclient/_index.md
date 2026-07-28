---
title: AuthenticateAsClient()
second_title: Aspose.Slides C++ API hivatkozás
description: Hitelesíti a kapcsolat kliensoldalát.
type: docs
weight: 339
url: /hu/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) metódus

Hitelesíti a kapcsolat kliensoldalát.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | A kiszolgáló neve, amely a jelenlegi példányt megosztja. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) metódus

Hitelesíti a kapcsolat kliensoldalát.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | A kiszolgáló neve, amely a jelenlegi példányt megosztja. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | Az ügyfél tanúsítványai. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | Az autentikációhoz használt SSL protokollok. |
| checkCertificateRevocation | **bool** | Egy érték, amely jelzi, hogy a tanúsítvány visszavonási listát ellenőrizni kell-e a hitelesítés során. |

## Lásd még

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [SslStream](../)
* Osztály [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Névtér [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)