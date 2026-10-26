---
title: DigitalSignature()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый объект DigitalSignature с указанным сертификатом.
type: docs
weight: 66
url: /ru/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) конструктор

Создает новый объект [DigitalSignature](../) с указанным сертификатом.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Сертификат, который будет использоваться для подписи презентации. |

## DigitalSignature::DigitalSignature(System::String, System::String) конструктор

Создает новый объект [DigitalSignature](../) с указанным путем к файлу сертификата и паролем.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Путь к файлу с сертификатом. |
| password | [System::String](../../../system/string/) | Пароль, необходимый для доступа к сертификату. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Класс [DigitalSignature](../)
* Класс [String](../../../system/string/)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)