---
title: GetCertContentType()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce il tipo di certificato contenuto nell'array di byte specificato.
type: docs
weight: 391
url: /it/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) metodo


Restituisce il tipo di certificato contenuto nell'array di byte specificato.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati del certificato. |

### Valore di ritorno

Tipo di certificato X.509.

## X509Certificate2::GetCertContentType(const String\&) metodo


Restituisce il tipo di certificato contenuto nel file specificato.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nome file del certificato. |

### Valore di ritorno

Tipo di certificato X.509.

## Vedi anche

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)