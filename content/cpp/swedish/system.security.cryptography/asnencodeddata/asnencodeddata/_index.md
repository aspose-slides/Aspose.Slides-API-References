---
title: AsnEncodedData()
second_title: Aspose.Slides för C++ API-referens
description: Kopieringskonstruktor.
type: docs
weight: 1
url: /sv/system.security.cryptography/asnencodeddata/asnencodeddata/
---
## AsnEncodedData::AsnEncodedData(const SharedPtr\<AsnEncodedData\>\&) konstruktor

Kopieringskonstruktor.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<AsnEncodedData> &asn_encoded_data)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asn_encoded_data | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../)\>\& | [Object](../../../system/object/) för att kopiera data från. |

## AsnEncodedData::AsnEncodedData(const ByteArrayPtr\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const ByteArrayPtr &raw_data)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodad data i rå byteformat. |

## AsnEncodedData::AsnEncodedData(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../oid/)\>\& | [Object](../../../system/object/) identifierare för kodad data. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodad data i rå byteformat. |

## AsnEncodedData::AsnEncodedData(const String\&, const ByteArrayPtr\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const String &oid, const ByteArrayPtr &raw_data)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identifierare för kodad data. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodad data i rå byteformat. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klass [AsnEncodedData](../)
* Klass [Oid](../../oid/)
* Klass [String](../../../system/string/)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)