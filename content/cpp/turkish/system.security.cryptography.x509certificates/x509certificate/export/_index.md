---
title: Export()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen formatı kullanarak mevcut nesneyi bir bayt dizisine dışa aktarır. UYGULANMADI.
type: docs
weight: 287
url: /tr/system.security.cryptography.x509certificates/x509certificate/export/
---
## X509Certificate::Export(X509ContentType) const method

Belirtilen formatı kullanarak mevcut nesneyi bir bayt dizisine dışa aktarır. UYGULANMADI.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Çıktı verisinin nasıl biçimlendirileceğini belirtir. |

### Dönüş Değeri

Mevcut nesneyi temsil eden bir bayt dizisi.

## X509Certificate::Export(X509ContentType, const SecureStringPtr\&) const method

Belirtilen formatı kullanarak mevcut nesneyi bir bayt dizisine dışa aktarır. UYGULANMADI.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const SecureStringPtr &password) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Çıktı verisinin nasıl biçimlendirileceğini belirtir. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Sertifika verilerine erişmek için gereken şifre. |

### Dönüş Değeri

Mevcut nesneyi temsil eden bir bayt dizisi.

## X509Certificate::Export(X509ContentType, const String\&) const method

Belirtilen formatı kullanarak mevcut nesneyi bir bayt dizisine dışa aktarır. UYGULANMADI.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const String &password) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Çıktı verisinin nasıl biçimlendirileceğini belirtir. |
| password | const [String](../../../system/string/)\& | Sertifika verilerine erişmek için gereken şifre. |

### Dönüş Değeri

Mevcut nesneyi temsil eden bir bayt dizisi.

## Ayrıca Bakınız

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Sınıf [X509Certificate](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Security::Cryptography::X509Certificates](../../)
* Kütüphane [Aspose.Slides](../../../)