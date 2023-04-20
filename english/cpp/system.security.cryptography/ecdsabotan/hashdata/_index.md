---
title: HashData()
second_title: Aspose.Slides for C++ API Reference
description: Computes the hash value of the specified data array using the specified hash algorithm.
type: docs
weight: 105
url: /cpp/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) method


Computes the hash value of the specified data array using the specified hash algorithm.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) to hash. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Number of bytes to hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash algorithm. |

### Return Value

Hashed data.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) method


Computes the hash value of the specified binary stream using the specified hash algorithm.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Bynary stream to hashed. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash algorithm. |

### Return Value

Hashed data.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)