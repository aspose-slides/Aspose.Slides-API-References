---
title: AuthenticateAsClient()
second_title: Aspose.Slides pro C++ API Reference
description: Ověřuje klientskou stranu připojení.
type: docs
weight: 339
url: /cs/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) metoda


Ověřuje klientskou stranu připojení.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Název serveru, který sdílí aktuální instanci. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) metoda


Ověřuje klientskou stranu připojení.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Název serveru, který sdílí aktuální instanci. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | Klientské certifikáty. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | SSL protokoly, které jsou použity pro ověřování. |
| checkCertificateRevocation | **bool** | Hodnota, která určuje, zda má být během ověřování kontrolován seznam odvolaných certifikátů. |

## Viz také

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [String](../../../system/string/)
* třída [SslStream](../)
* třída [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* jmenný prostor [System::Net::Security](../../)
* knihovna [Aspose.Slides](../../../)