---
title: AuthenticateAsClient()
second_title: Riferimento API di Aspose.Slides per C++
description: Autentica il lato client della connessione.
type: docs
weight: 339
url: /it/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) metodo

Autentica il lato client della connessione.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Il nome del server che condivide l'istanza corrente. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) metodo

Autentica il lato client della connessione.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Il nome del server che condivide l'istanza corrente. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | I certificati client. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | I protocolli SSL utilizzati per l'autenticazione. |
| checkCertificateRevocation | **bool** | Un valore che indica se la lista di revoca dei certificati deve essere controllata durante l'autenticazione. |

## Vedi anche

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [SslStream](../)
* Classe [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Spazio dei nomi [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)