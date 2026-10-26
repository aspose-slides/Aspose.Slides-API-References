---
title: AuthenticateAsClient()
second_title: Aspose.Slides für C++ API-Referenz
description: Authentifiziert die Client-Seite der Verbindung.
type: docs
weight: 339
url: /de/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) Methode


Authentifiziert die Client-Seite der Verbindung.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Der Name des Servers, der die aktuelle Instanz freigibt. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) Methode


Authentifiziert die Client-Seite der Verbindung.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Der Name des Servers, der die aktuelle Instanz freigibt. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | Die Client-Zertifikate. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | Die SSL-Protokolle, die für die Authentifizierung verwendet werden. |
| checkCertificateRevocation | **bool** | Ein Wert, der angibt, ob die Zertifikatswiderrufsliste während der Authentifizierung geprüft werden muss. |

## Siehe auch

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [SslStream](../)
* Klasse [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Namensraum [System::Net::Security](../../)
* Bibliothek [Aspose.Slides](../../../)