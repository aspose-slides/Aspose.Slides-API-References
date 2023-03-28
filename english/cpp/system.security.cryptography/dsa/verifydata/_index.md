---
title: VerifyData()
second_title: Aspose.Slides for C++ API Reference
description: Verifies that the signature of the specified data is valid.
type: docs
weight: 92
url: /cpp/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [HashAlgorithmName](../../hashalgorithmname/)\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signed data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
## DSA::VerifyData(const [ByteArrayPtr](../../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [HashAlgorithmName](../../hashalgorithmname/)\&) method


Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signed data. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Number of bytes to hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
## DSA::VerifyData(const [StreamPtr](../../../system/streamptr/)\&, const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [HashAlgorithmName](../../hashalgorithmname/)\&) method


Verifies that the signature of the specified binary stream is valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Signed data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
