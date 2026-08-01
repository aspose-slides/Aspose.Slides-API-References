---
title: SignData()
second_title: Aspose.Slides voor C++ API Referentie
description: Berekent de hashwaarde van de opgegeven gegevensarray met het opgegeven hash-algoritme en ondertekent het resultaat.
type: docs
weight: 79
url: /nl/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) methode


Berekent de hashwaarde van de opgegeven gegevensarray met het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Invoergegevensarray. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert [DSA](../) handtekening voor de invoergegevens. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) methode


Berekent de hashwaarde van de opgegeven gegevensarray met het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Invoergegevensarray. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Aantal bytes die als invoergegevens worden gebruikt. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert [DSA](../) handtekening voor de invoergegevens. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) methode


Berekent de hashwaarde van de opgegeven binaire stream met het opgegeven hash-algoritme en ondertekent het resultaat.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binaire stream. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert [DSA](../) handtekening voor de invoergegevens. |

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)