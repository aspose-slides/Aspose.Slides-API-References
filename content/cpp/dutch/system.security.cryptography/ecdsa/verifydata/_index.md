---
title: VerifyData()
second_title: Aspose.Slides voor C++ API-referentie
description: Verifieert of de handtekening van de opgegeven gegevens geldig is.
type: docs
weight: 105
url: /nl/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) methode

Verifieert of de handtekening van de opgegeven gegevens geldig is.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ondertekende gegevens. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert true als de handtekening geldig is, anders - false. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) methode

Verifieert of de handtekening van de opgegeven gegevens geldig is.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ondertekende gegevens. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Aantal bytes om te hashen. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert true als de handtekening geldig is, anders - false. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) methode

Verifieert of de handtekening van de opgegeven binaire stroom geldig is.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Ondertekende gegevens. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert true als de handtekening geldig is, anders - false. |

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsa](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)