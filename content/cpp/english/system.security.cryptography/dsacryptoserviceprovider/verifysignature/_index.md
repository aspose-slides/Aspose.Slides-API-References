---
title: VerifySignature()
second_title: Aspose.Slides for C++ API Reference
description: Verify DSA signature for the specified data.
type: docs
weight: 118
url: /system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) method


Verify [DSA](../../dsa/) signature for the specified data.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) signed with **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) signature. |

### Return Value

true - if **rgb_signature** matches the [DSA](../../dsa/) signature computed on **rgb_hash**, otherwise - false.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)