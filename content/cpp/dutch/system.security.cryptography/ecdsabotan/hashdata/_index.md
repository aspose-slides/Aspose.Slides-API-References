---
title: HashData()
second_title: Aspose.Slides voor C++ API Referentie
description: Berekent de hashwaarde van de opgegeven gegevensarray met het opgegeven hash-algoritme.
type: docs
weight: 105
url: /nl/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) method

Berekent de hashwaarde van de opgegeven gegevensarray met behulp van het opgegeven hash-algoritme.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) te hashen. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Aantal bytes om te hashen. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash-algoritme. |

### Retourwaarde

Hashed data.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) method

Berekent de hashwaarde van de opgegeven binaire stream met behulp van het opgegeven hash-algoritme.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Binaire stream om te hashen. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash-algoritme. |

### Retourwaarde

Hashed data.

## Zie ook

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasse [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Naamruimte [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)