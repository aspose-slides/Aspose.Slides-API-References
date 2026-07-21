---
title: AuthenticateAsClient()
second_title: Aspose.Slides для C++ справочник API
description: Аутентифицирует клиентскую сторону соединения.
type: docs
weight: 339
url: /ru/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) метод


Аутентифицирует клиентскую сторону соединения.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Имя сервера, который предоставляет текущий экземпляр. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) метод


Аутентифицирует клиентскую сторону соединения.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Имя сервера, который предоставляет текущий экземпляр. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | Сертификаты клиента. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | Протоколы SSL, используемые для аутентификации. |
| checkCertificateRevocation | **bool** | Значение, указывающее, необходимо ли проверять список отзыва сертификатов во время аутентификации. |

## См. также

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [SslStream](../)
* Класс [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Пространство имён [System::Net::Security](../../)
* Библиотека [Aspose.Slides](../../../)