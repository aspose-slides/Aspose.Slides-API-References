---
title: X509Extension()
second_title: Referência da API Aspose.Slides para C++
description: Construtor.
type: docs
weight: 1
url: /pt/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) construtor

Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Dados codificados associados ao certificado. |
| critical | **bool** | Sinal de criticidade. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) construtor

Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) identificador associado à extensão. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados brutos associados ao certificado. |
| critical | **bool** | Sinal de criticidade. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) construtor

Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identificador associado à extensão. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dados brutos associados ao certificado. |
| critical | **bool** | Sinal de criticidade. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X509Extension](../)
* Class [Oid](../../../system.security.cryptography/oid/)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)