---
title: HashData()
second_title: Aspose.Slides für C++ API-Referenz
description: Berechnet den Hash-Wert des angegebenen Datenarrays mithilfe des angegebenen Hash-Algorithmus.
type: docs
weight: 105
url: /de/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) method


Berechnet den Hash-Wert des angegebenen Datenarrays mit dem angegebenen Hash-Algorithmus.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) zu hashen. |
| offset | **int32_t** | Versatz in **data**. |
| count | **int32_t** | Anzahl der Bytes zum Hashen. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash-Algorithmus. |

### Rückgabewert

Gehashte Daten.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) method


Berechnet den Hash-Wert des angegebenen Binär-Streams mit dem angegebenen Hash-Algorithmus.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Binär-Stream zum Hashen. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash-Algorithmus. |

### Rückgabewert

Gehashte Daten.

## Siehe auch

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasse [ECDsaBotan](../)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)