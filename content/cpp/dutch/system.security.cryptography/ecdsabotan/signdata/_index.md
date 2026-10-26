---
title: SignData()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent de hashwaarde van de opgegeven data-array en ondertekent het resultaat.
type: docs
weight: 131
url: /nl/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) methode

Berekent de hashwaarde van de opgegeven data-array en ondertekent het resultaat.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Invoergegevensarray. Retourneert ECDSA-handtekening voor de invoergegevens. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) methode

Berekent de hashwaarde van de opgegeven data-array en ondertekent het resultaat.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Invoergegevensarray. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Aantal bytes om als invoergegevens te gebruiken. Retourneert ECDSA-handtekening voor de invoergegevens. |

## ECDsaBotan::SignData(const StreamPtr\&) methode

Berekent de hashwaarde van de opgegeven binaire stream en ondertekent het resultaat.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binaire stream. Retourneert ECDSA-handtekening voor de invoergegevens. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) methode

Berekent de hashwaarde van de opgegeven data-array met behulp van het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Invoergegevensarray. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. Retourneert ECDSA-handtekening voor de invoergegevens. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) methode

Berekent de hashwaarde van de opgegeven data-array met behulp van het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Invoergegevensarray. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Aantal bytes om als invoergegevens te gebruiken. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. Retourneert ECDSA-handtekening voor de invoergegevens. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) methode

Berekent de hashwaarde van de opgegeven binaire stream met behulp van het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binaire stream. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. Retourneert ECDSA-handtekening voor de invoergegevens. |

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)