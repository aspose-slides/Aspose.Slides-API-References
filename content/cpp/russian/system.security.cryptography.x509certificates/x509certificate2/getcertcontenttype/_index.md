---
title: GetCertContentType()
second_title: Aspose.Slides для C++ справочника API
description: Возвращает тип сертификата, содержащегося в указанном массиве байтов.
type: docs
weight: 391
url: /ru/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) метод


Возвращает тип сертификата, содержащегося в указанном массиве байтов.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Данные сертификата. |

### Возвращаемое значение

Тип X.509 сертификата.

## X509Certificate2::GetCertContentType(const String\&) метод


Возвращает тип сертификата, содержащегося в указанном файле.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Имя файла сертификата. |

### Возвращаемое значение

Тип X.509 сертификата.

## См. также

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)