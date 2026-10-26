---
title: AsnEncodedData()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruttore di copia.
type: docs
weight: 1
url: /it/system.security.cryptography/asnencodeddata/asnencodeddata/
---
## AsnEncodedData::AsnEncodedData(const SharedPtr\<AsnEncodedData\>\&) costruttore

Costruttore di copia.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<AsnEncodedData> &asn_encoded_data)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| asn_encoded_data | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../)\>\& | [Object](../../../system/object/) da cui copiare i dati. |

## AsnEncodedData::AsnEncodedData(const ByteArrayPtr\&) costruttore

Costruttore.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const ByteArrayPtr &raw_data)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati codificati in formato byte grezzo. |

## AsnEncodedData::AsnEncodedData(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) costruttore

Costruttore.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../oid/)\>\& | [Object](../../../system/object/) identificatore dei dati codificati. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati codificati in formato byte grezzo. |

## AsnEncodedData::AsnEncodedData(const String\&, const ByteArrayPtr\&) costruttore

Costruttore.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const String &oid, const ByteArrayPtr &raw_data)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identificatore dei dati codificati. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati codificati in formato byte grezzo. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [AsnEncodedData](../)
* Classe [Oid](../../oid/)
* Classe [String](../../../system/string/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)