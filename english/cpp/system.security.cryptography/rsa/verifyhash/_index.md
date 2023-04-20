---
title: VerifyHash()
second_title: Aspose.Slides for C++ API Reference
description: Verifies that the signature of the specified hash is valid.
type: docs
weight: 170
url: /cpp/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) method


Verifies that the signature of the specified hash is valid.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
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
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)