---
title: VerifyHash()
second_title: Aspose.Slides for C++ API Reference
description: Checks data signature.
type: docs
weight: 118
url: /system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) method


Checks data signature.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash calculated for received data. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Signature as received. |

### Return Value

True if signature is valid, false otherwise.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)