---
title: SignHash()
second_title: Aspose.Slides for C++ API Reference
description: Computes the signature for the specified hash value.
type: docs
weight: 144
url: /cpp/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) method


Computes the signature for the specified hash value.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash value. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash algorithm. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Padding mode. return [RSA](../) signature for the specified hash. |

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)