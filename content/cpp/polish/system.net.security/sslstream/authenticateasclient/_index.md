---
title: AuthenticateAsClient()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Uwierzytelnia stronę klienta połączenia.
type: docs
weight: 339
url: /pl/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) metoda

Uwierzytelnia stronę klienta połączenia.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Nazwa serwera, który udostępnia bieżącą instancję. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) metoda

Uwierzytelnia stronę klienta połączenia.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Nazwa serwera, który udostępnia bieżącą instancję. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | Certyfikaty klienta. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | Protokoły SSL używane do uwierzytelniania. |
| checkCertificateRevocation | **bool** | Wartość wskazująca, czy lista odwołań certyfikatów musi być sprawdzana podczas uwierzytelniania. |

## Zobacz także

* Wyliczenie [SslProtocols](../../../system.security.authentication/sslprotocols/)
* DefinicjaTypu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [SslStream](../)
* Klasa [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* PrzestrzeńNazw [System::Net::Security](../../)
* Biblioteka [Aspose.Slides](../../../)