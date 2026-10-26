---
title: Encrypt()
second_title: Aspose.Slides pro C++ reference API
description: Šifruje vstupní data pomocí zadaného režimu vycpávání.
type: docs
weight: 53
url: /cs/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metoda


Šifruje vstupní data pomocí zadaného režimu vycpávání.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) pole k zašifrování. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Režim vycpávání. |

### Návratová hodnota

Zašifrovaná data ve formátu pole bajtů.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Třída [RSA](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)