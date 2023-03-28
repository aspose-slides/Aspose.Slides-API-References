---
title: VerifyHash()
second_title: Aspose.Slides for C++ API Reference
description: Checks data signature.
type: docs
weight: 222
url: /cpp/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [String](../../../system/string/)\&, const [ByteArrayPtr](../../../system/bytearrayptr/)\&) method


Checks data signature.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash calculated for received data. |
| str | const [String](../../../system/string/)\& | Name of hash algorithm used. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature as received. |

### Return Value

True if signature is valid, false otherwise.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
## RSACryptoServiceProvider::VerifyHash([ByteArrayPtr](../../../system/bytearrayptr/), [ByteArrayPtr](../../../system/bytearrayptr/), const [HashAlgorithmName](../../hashalgorithmname/)\&, [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>) method


Verifies that the signature of the specified hash is valid.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash value of the signed data. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Signature data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algorithm. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Padding mode. return true if signature is valid, otherwise - false. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
