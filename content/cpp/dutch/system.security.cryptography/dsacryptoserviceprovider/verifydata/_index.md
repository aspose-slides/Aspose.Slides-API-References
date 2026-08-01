---
title: VerifyData()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert de handtekening van gegevens.
type: docs
weight: 209
url: /nl/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) methode


Controleert de handtekening van gegevens.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) om de handtekening voor te controleren. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekening zoals ontvangen. |

### Retourwaarde

True als de handtekening geldig is, false anders.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) methode


Verifieert dat de handtekening van de opgegeven gegevens geldig is.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ondertekende gegevens. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. return true als de handtekening geldig is, anders - false. |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) methode


Verifieert dat de handtekening van de opgegeven gegevens geldig is.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ondertekende gegevens. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Aantal bytes om te hashen. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. return true als de handtekening geldig is, anders - false. |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) methode


Verifieert dat de handtekening van de opgegeven binaire stroom geldig is.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Ondertekende gegevens. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. return true als de handtekening geldig is, anders - false. |

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)