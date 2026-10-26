---
title: HashData()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen.
type: docs
weight: 105
url: /sv/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) metod


Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) att hasha. |
| offset | **int32_t** | Offset i **data**. |
| count | **int32_t** | Antal byte att hasha. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash-algoritm. |

### Returvärde

Hashad data.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) metod


Beräknar hashvärdet för den angivna binära strömmen med den angivna hash-algoritmen.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Binär ström att hasha. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash-algoritm. |

### Returvärde

Hashad data.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klass [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namnrymd [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)