---
title: AsnEncodedData()
second_title: Référence de l'API Aspose.Slides pour C++
description: Constructeur de copie.
type: docs
weight: 1
url: /fr/system.security.cryptography/asnencodeddata/asnencodeddata/
---
## AsnEncodedData::AsnEncodedData(const SharedPtr\<AsnEncodedData\>\&) constructeur

Constructeur de copie.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<AsnEncodedData> &asn_encoded_data)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| asn_encoded_data | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../)\>\& | [Object](../../../system/object/) pour copier les données de. |

## AsnEncodedData::AsnEncodedData(const ByteArrayPtr\&) constructeur

Constructeur.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const ByteArrayPtr &raw_data)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données encodées au format brut d'octets. |

## AsnEncodedData::AsnEncodedData(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) constructeur

Constructeur.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../oid/)\>\& | [Object](../../../system/object/) identifiant des données encodées. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données encodées au format brut d'octets. |

## AsnEncodedData::AsnEncodedData(const String\&, const ByteArrayPtr\&) constructeur

Constructeur.

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const String &oid, const ByteArrayPtr &raw_data)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identifiant des données encodées. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Données encodées au format brut d'octets. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [AsnEncodedData](../)
* Classe [Oid](../../oid/)
* Classe [String](../../../system/string/)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)