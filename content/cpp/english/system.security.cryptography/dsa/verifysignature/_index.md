---
title: VerifySignature()
second_title: Aspose.Slides for C++ API Reference
description: Verify DSA signature for the specified data.
type: docs
weight: 14
url: /system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) method


Verify [DSA](../) signature for the specified data.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) signed with **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) signature. |

### Return Value

true - if **rgb_signature** matches the [DSA](../) signature computed on **rgb_hash**, otherwise - false.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [DSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)