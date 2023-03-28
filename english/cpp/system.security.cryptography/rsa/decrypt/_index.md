---
title: Decrypt()
second_title: Aspose.Slides for C++ API Reference
description: Decrypts input data using the specified padding mode.
type: docs
weight: 27
url: /cpp/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt([ByteArrayPtr](../../../system/bytearrayptr/), [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\>) method


Decrypts input data using the specified padding mode.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array to decrypt. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Padding mode. |

### Return Value

Decrypted data in byte array format.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Class [RSA](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
