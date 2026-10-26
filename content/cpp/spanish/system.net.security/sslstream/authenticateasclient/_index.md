---
title: AuthenticateAsClient()
second_title: Referencia de API de Aspose.Slides para C++
description: Autentica el lado cliente de la conexión.
type: docs
weight: 339
url: /es/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) método


Authenticates the client-side of the connection.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | El nombre del servidor que comparte la instancia actual. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) método


Authenticates the client-side of the connection.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | El nombre del servidor que comparte la instancia actual. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | Los certificados del cliente. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | Los protocolos SSL que se usan para la autenticación. |
| checkCertificateRevocation | **bool** | Un valor que indica si la lista de revocación de certificados debe verificarse durante la autenticación. |

## Véase también

* Enumeración [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [SslStream](../)
* Clase [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Espacio de nombres [System::Net::Security](../../)
* Biblioteca [Aspose.Slides](../../../)