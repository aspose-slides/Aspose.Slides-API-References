---
title: Encrypt()
second_title: Aspose.Slides dla C++ – Referencja API
description: Szyfruje dane wejściowe przy użyciu określonego trybu wypełnienia.
type: docs
weight: 53
url: /pl/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metoda

Szyfruje dane wejściowe przy użyciu określonego trybu wypełnienia.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) tablica do zaszyfrowania. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Tryb wypełnienia. |

### Wartość zwracana

Zaszyfrowane dane w formacie tablicy bajtów.

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Klasa [RSA](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)