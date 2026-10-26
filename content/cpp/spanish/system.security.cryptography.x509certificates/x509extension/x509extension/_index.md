---
title: X509Extension()
second_title: Referencia de la API de Aspose.Slides para C++
description: Constructor.
type: docs
weight: 1
url: /es/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Datos codificados asociados al certificado. |
| critical | **bool** | Señal de criticidad. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) identificador asociado a la extensión. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos sin procesar asociados al certificado. |
| critical | **bool** | Señal de criticidad. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identificador asociado a la extensión. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos sin procesar asociados al certificado. |
| critical | **bool** | Señal de criticidad. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Clase [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Clase [X509Extension](../)
* Clase [Oid](../../../system.security.cryptography/oid/)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)