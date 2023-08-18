---
title: SignData()
second_title: Aspose.Slides for C++ API Reference
description: Computes the signature of specified input value.
type: docs
weight: 183
url: /system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) method


Computes the signature of specified input value.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) to read input data from. |

### Return Value

[DSA](../../dsa/) signature for specified data.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) method


Computes the signature of specified input value.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream to read data being signed from. |

### Return Value

[DSA](../../dsa/) signature for specified data.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) method


Computes the signature of specified input value.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) to read input data from. |
| offset | **int32_t** | Input buffer slice beginning index. |
| count | **int32_t** | Input buffer slice size. |

### Return Value

[DSA](../../dsa/) signature for specified data.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


Computes the hash value of the specified data array using the specified hash algorithm, and signs the result.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return [DSA](../../dsa/) signature for the input data. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


Computes the hash value of the specified data array using the specified hash algorithm, and signs the result.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Number of bytes to use as input data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return [DSA](../../dsa/) signature for the input data. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


Computes the hash value of the specified binary stream using the specified hash algorithm, and signs the result.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binary stream. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. return [DSA](../../dsa/) signature for the input data. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Class [Stream](../../../system.io/stream/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)