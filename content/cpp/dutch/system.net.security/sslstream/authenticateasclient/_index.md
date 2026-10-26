---
title: AuthenticateAsClient()
second_title: Aspose.Slides voor C++ API-referentie
description: Authenticates de clientzijde van de verbinding.
type: docs
weight: 339
url: /nl/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) methode

Authentiseert de clientzijde van de verbinding.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | De naam van de server die de huidige instantie deelt. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) methode

Authentiseert de clientzijde van de verbinding.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | De naam van de server die de huidige instantie deelt. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | De clientcertificaten. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | De SSL-protocollen die worden gebruikt voor authenticatie. |
| checkCertificateRevocation | **bool** | Een waarde die aangeeft of de certificaat-intrekkingslijst moet worden gecontroleerd tijdens authenticatie. |

## Zie ook

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [SslStream](../)
* Klasse [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Naamruimte [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)