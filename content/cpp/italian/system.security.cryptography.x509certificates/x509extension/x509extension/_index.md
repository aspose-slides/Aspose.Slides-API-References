---
title: X509Extension()
second_title: Riferimento API Aspose.Slides per C++
description: Costruttore.
type: docs
weight: 1
url: /it/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor

Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Dati codificati associati al certificato. |
| critical | **bool** | Indicatore di criticità. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor

Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | Identificatore [Object](../../../system/object/) associato all'estensione. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati grezzi associati al certificato. |
| critical | **bool** | Indicatore di criticità. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor

Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | Identificatore [Object](../../../system/object/) associato all'estensione. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati grezzi associati al certificato. |
| critical | **bool** | Indicatore di criticità. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X509Extension](../)
* Class [Oid](../../../system.security.cryptography/oid/)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)