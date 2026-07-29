---
title: Encrypt()
second_title: Aspose.Slides för C++ API-referens
description: Krypterar indata med det angivna utfyllnadsläget.
type: docs
weight: 53
url: /sv/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metod

Krypterar indata med det angivna utfyllnadsläget.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array att kryptera. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Utfyllnadsläge. |

### Returvärde

Krypterad data i bytearrayformat.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Klass [RSA](../)
* Namnrymd [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)