---
title: AuthenticateAsClient()
second_title: Référence de l'API Aspose.Slides pour C++
description: Authentifie le côté client de la connexion.
type: docs
weight: 339
url: /fr/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) méthode

Authentifie le côté client de la connexion.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Le nom du serveur qui partage l'instance actuelle. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) méthode

Authentifie le côté client de la connexion.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Le nom du serveur qui partage l'instance actuelle. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | Les certificats client. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | Les protocoles SSL qui sont utilisés pour l'authentification. |
| checkCertificateRevocation | **bool** | Une valeur indiquant si la liste de révocation des certificats doit être vérifiée lors de l'authentification. |

## Voir aussi

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [SslStream](../)
* Classe [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Espace de noms [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)