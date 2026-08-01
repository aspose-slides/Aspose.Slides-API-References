---
title: VerifyData()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of de handtekening van de opgegeven gegevens geldig is.
type: docs
weight: 170
url: /nl/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) methode

Controleert of de handtekening van de opgegeven gegevens geldig is.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ondertekende gegevens. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. retourneert true als de handtekening geldig is, anders false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) methode

Controleert of de handtekening van de opgegeven gegevens geldig is.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ondertekende gegevens. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Aantal bytes om te hashen. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. retourneert true als de handtekening geldig is, anders false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) methode

Controleert of de handtekening van de opgegeven binaire stream geldig is.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Ondertekende gegevens. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. retourneert true als de handtekening geldig is, anders false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) methode

Controleert of de handtekening van de opgegeven gegevens geldig is.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ondertekende gegevens. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert true als de handtekening geldig is, anders false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) methode

Controleert of de handtekening van de opgegeven gegevens geldig is.

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
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert true als de handtekening geldig is, anders false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) methode

Controleert of de handtekening van de opgegeven binaire stream geldig is.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Ondertekende gegevens. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Handtekeninggegevens. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritme. retourneert true als de handtekening geldig is, anders false. |

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)