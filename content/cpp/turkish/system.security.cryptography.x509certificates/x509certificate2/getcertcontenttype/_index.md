---
title: GetCertContentType()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bayt dizisinde bulunan sertifikanın türünü alır.
type: docs
weight: 391
url: /tr/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) metodu

Belirtilen bayt dizisinde bulunan sertifikanın türünü alır.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sertifika verisi. |

### Dönüş Değeri

X.509 sertifikasının türü.

## X509Certificate2::GetCertContentType(const String\&) metodu

Belirtilen dosyada bulunan sertifikanın türünü alır.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifika dosya adı. |

### Dönüş Değeri

X.509 sertifikasının türü.

## Ayrıca Bakınız

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)