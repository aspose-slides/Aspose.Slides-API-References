---
title: VerifyData()
second_title: Aspose.Slides for C++ API Reference
description: Checks data signature.
type: docs
weight: 209
url: /cpp/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../../system/bytearrayptr/)\&) method


Checks data signature.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) to check signature for. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature as received. |

### Return Value

True if signature is valid, false otherwise.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
## DSACryptoServiceProvider::VerifyData(const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [HashAlgorithmName](../../hashalgorithmname/)\&) method


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
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
## DSACryptoServiceProvider::VerifyData(const [ByteArrayPtr](../../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [HashAlgorithmName](../../hashalgorithmname/)\&) method


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
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
## DSACryptoServiceProvider::VerifyData(const [StreamPtr](../../../system/streamptr/)\&, const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [HashAlgorithmName](../../hashalgorithmname/)\&) method


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
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
