---
title: SignData()
second_title: Aspose.Slides for C++ API Reference
description: Computes the hash value of the specified data array, and signs the result.
type: docs
weight: 131
url: /system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) method


Computes the hash value of the specified data array, and signs the result.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. return ECDSA signature for the input data. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) method


Computes the hash value of the specified data array, and signs the result.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Number of bytes to use as input data. return ECDSA signature for the input data. |

## ECDsaBotan::SignData(const StreamPtr\&) method


Computes the hash value of the specified binary stream, and signs the result.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binary stream. return ECDSA signature for the input data. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


Computes the hash value of the specified data array using the specified hash algorithm, and signs the result.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return ECDSA signature for the input data. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


Computes the hash value of the specified data array using the specified hash algorithm, and signs the result.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Number of bytes to use as input data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return ECDSA signature for the input data. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


Computes the hash value of the specified binary stream using the specified hash algorithm, and signs the result.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binary stream. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return ECDSA signature for the input data. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)