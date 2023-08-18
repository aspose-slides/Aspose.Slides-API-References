---
title: VerifyData()
second_title: Aspose.Slides for C++ API Reference
description: Verifies that the signature of the specified data is valid.
type: docs
weight: 170
url: /system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signed data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature data. return true if signature is valid, otherwise - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signed data. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Number of bytes to hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature data. return true if signature is valid, otherwise - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) method


Verifies that the signature of the specified binary stream is valid.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Signed data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature data. return true if signature is valid, otherwise - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signed data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return true if signature is valid, otherwise - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signed data. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Number of bytes to hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return true if signature is valid, otherwise - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Verifies that the signature of the specified binary stream is valid.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Signed data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)