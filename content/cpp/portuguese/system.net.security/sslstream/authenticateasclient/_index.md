---
title: AuthenticateAsClient()
second_title: Referência da API Aspose.Slides para C++
description: Autentica o lado cliente da conexão.
type: docs
weight: 339
url: /pt/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) método

Autentica o lado cliente da conexão.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | O nome do servidor que compartilha a instância atual. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) método

Autentica o lado cliente da conexão.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | O nome do servidor que compartilha a instância atual. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | Os certificados do cliente. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | Os protocolos SSL usados para autenticação. |
| checkCertificateRevocation | **bool** | Um valor que indica se a lista de revogação de certificados deve ser verificada durante a autenticação. |

## Veja Também

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [SslStream](../)
* Classe [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Namespace [System::Net::Security](../../)
* Biblioteca [Aspose.Slides](../../../)