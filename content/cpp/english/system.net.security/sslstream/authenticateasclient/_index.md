---
title: AuthenticateAsClient()
second_title: Aspose.Slides for C++ API Reference
description: Authenticates the client-side of the connection.
type: docs
weight: 339
url: /system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) method


Authenticates the client-side of the connection.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | The name of the server that shares the current instance. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) method


Authenticates the client-side of the connection.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | The name of the server that shares the current instance. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | The client certificates. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | The SSL protocols that are used for authentication. |
| checkCertificateRevocation | **bool** | A value that indicates if the certificate revocation list must be checked during authentication. |

## See Also

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [SslStream](../)
* Class [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)