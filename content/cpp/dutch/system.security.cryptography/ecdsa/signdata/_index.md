---
title: SignData()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent de hashwaarde van de opgegeven datareeks met behulp van het opgegeven hash-algoritme en ondertekent het resultaat.
type: docs
weight: 79
url: /nl/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) methode


Berekent de hashwaarde van de opgegeven datareeks met behulp van het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert ECDSA-handtekening voor de invoergegevens. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) methode


Berekent de hashwaarde van de opgegeven datareeks met behulp van het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Number of bytes to use as input data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert ECDSA-handtekening voor de invoergegevens. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) methode


Berekent de hashwaarde van de opgegeven binaire stream met behulp van het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binary stream. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert ECDSA-handtekening voor de invoergegevens. |

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasse [ECDsa](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)