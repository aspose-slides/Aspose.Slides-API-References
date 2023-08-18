---
title: VerifyHash()
second_title: Aspose.Slides for C++ API Reference
description: Checks data signature.
type: docs
weight: 183
url: /system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash(ByteArrayPtr, ByteArrayPtr) method


Checks data signature.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
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
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)