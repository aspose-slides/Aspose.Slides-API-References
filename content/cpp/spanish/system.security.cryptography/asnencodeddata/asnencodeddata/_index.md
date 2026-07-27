---
title: AsnEncodedData()
second_title: Referencia de la API de Aspose.Slides para C++
description: Constructor de copia.
type: docs
weight: 1
url: /es/system.security.cryptography/asnencodeddata/asnencodeddata/
---
## AsnEncodedData::AsnEncodedData(const SharedPtr\<AsnEncodedData\>\&) constructor

Constructor de copia.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<AsnEncodedData> &asn_encoded_data)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asn_encoded_data | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../)\>\& | [Object](../../../system/object/) para copiar datos de. |

## AsnEncodedData::AsnEncodedData(const ByteArrayPtr\&) constructor

Constructor.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const ByteArrayPtr &raw_data)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos codificados en formato de bytes crudos. |

## AsnEncodedData::AsnEncodedData(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) constructor

Constructor.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../oid/)\>\& | [Object](../../../system/object/) identificador de los datos codificados. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos codificados en formato de bytes crudos. |

## AsnEncodedData::AsnEncodedData(const String\&, const ByteArrayPtr\&) constructor

Constructor.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const String &oid, const ByteArrayPtr &raw_data)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identificador de los datos codificados. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Datos codificados en formato de bytes crudos. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Clase [AsnEncodedData](../)
* Clase [Oid](../../oid/)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)