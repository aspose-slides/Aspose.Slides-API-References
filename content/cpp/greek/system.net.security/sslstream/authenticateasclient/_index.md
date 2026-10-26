---
title: AuthenticateAsClient()
second_title: Aspose.Slides για C++ Αναφορά API
description: Πραγματοποιεί την πιστοποίηση της πλευράς πελάτη της σύνδεσης.
type: docs
weight: 339
url: /el/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) μέθοδος


Πραγματοποιεί την πιστοποίηση της πλευράς πελάτη της σύνδεσης.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Το όνομα του διακομιστή που μοιράζεται το τρέχον στιγμιότυπο. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) μέθοδος


Πραγματοποιεί την πιστοποίηση της πλευράς πελάτη της σύνδεσης.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Το όνομα του διακομιστή που μοιράζεται το τρέχον στιγμιότυπο. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | Τα πιστοποιητικά πελάτη. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | Τα πρωτόκολλα SSL που χρησιμοποιούνται για την πιστοποίηση. |
| checkCertificateRevocation | **bool** | Μια τιμή που υποδεικνύει αν πρέπει να ελεγχθεί η λίστα ανάκλησης πιστοποιητικών κατά την πιστοποίηση. |

## Δείτε επίσης

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [SslStream](../)
* Class [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)