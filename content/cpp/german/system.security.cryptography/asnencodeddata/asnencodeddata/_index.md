---
title: AsnEncodedData()
second_title: Aspose.Slides für C++ API-Referenz
description: Kopierkonstruktor.
type: docs
weight: 1
url: /de/system.security.cryptography/asnencodeddata/asnencodeddata/
---
## AsnEncodedData::AsnEncodedData(const SharedPtr\<AsnEncodedData\>\&) Konstruktor


Kopierkonstruktor.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<AsnEncodedData> &asn_encoded_data)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asn_encoded_data | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../)\>\& | [Object](../../../system/object/) zum Kopieren der Daten aus. |

## AsnEncodedData::AsnEncodedData(const ByteArrayPtr\&) Konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const ByteArrayPtr &raw_data)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodierte Daten im Rohbyteformat. |

## AsnEncodedData::AsnEncodedData(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) Konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../oid/)\>\& | [Object](../../../system/object/) Bezeichner der kodierten Daten. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodierte Daten im Rohbyteformat. |

## AsnEncodedData::AsnEncodedData(const String\&, const ByteArrayPtr\&) Konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const String &oid, const ByteArrayPtr &raw_data)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) Bezeichner der kodierten Daten. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodierte Daten im Rohbyteformat. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasse [AsnEncodedData](../)
* Klasse [Oid](../../oid/)
* Klasse [String](../../../system/string/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)