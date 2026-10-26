---
title: AuthenticateAsClient()
second_title: Aspose.Slides för C++ API-referens
description: Autentiserar klientsidan av anslutningen.
type: docs
weight: 339
url: /sv/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) metod

Autentiserar klient-sidan av anslutningen.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Namnet på servern som delar den aktuella instansen. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) metod

Autentiserar klient-sidan av anslutningen.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Namnet på servern som delar den aktuella instansen. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | Klientcertifikaten. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | SSL-protokollen som används för autentisering. |
| checkCertificateRevocation | **bool** | Ett värde som indikerar om certifikatåterkallandelistan måste kontrolleras under autentisering. |

## Se även

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [SslStream](../)
* Klass [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Namnrymd [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)