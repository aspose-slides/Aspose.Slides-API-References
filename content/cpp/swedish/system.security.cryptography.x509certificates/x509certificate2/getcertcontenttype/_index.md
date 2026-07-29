---
title: GetCertContentType()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar typen av certifikat som finns i den angivna bytearrayen.
type: docs
weight: 391
url: /sv/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) metod

Hämtar typen av certifikat som finns i den angivna bytearrayen.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Certifikatdata. |

### Returvärde

Typ av X.509-certifikat.

## X509Certificate2::GetCertContentType(const String\&) metod

Hämtar typen av certifikat som finns i den angivna filen.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Certifikatfilnamn. |

### Returvärde

Typ av X.509-certifikat.

## Se även

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klass [X509Certificate2](../)
* Klass [String](../../../system/string/)
* Namnutrymme [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)