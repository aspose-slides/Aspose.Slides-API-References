---
title: Decrypt()
second_title: Reference API Aspose.Slides pro C++
description: Dešifruje vstupní data pomocí zadaného režimu výplně.
type: docs
weight: 27
url: /cs/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metoda

Dekryptuje vstupní data pomocí zadaného režimu výplně.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) pole k dešifrování. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Režim výplně. |

### Návratová hodnota

Dešifrovaná data v formátu pole bajtů.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Třída [RSA](../)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)