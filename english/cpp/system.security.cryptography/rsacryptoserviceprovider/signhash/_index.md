---
title: SignHash()
second_title: Aspose.Slides for C++ API Reference
description: Computes the signature for the specified hash value.
type: docs
weight: 196
url: /cpp/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) method


Computes the signature for the specified hash value.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash value. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash algorithm. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Padding mode. return [RSA](../../rsa/) signature for the specified hash. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) method


Computes the signature of specified input value. Not implemented.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash value of data to be signed. |
| str | const [String](../../../system/string/)\& | Hash algorithm identifier used to create the hash. |

### Return Value

[RSA](../../rsa/) signature for specified data.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)