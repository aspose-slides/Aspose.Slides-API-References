---
title: Encrypt()
second_title: Aspose.Slides for C++ API Referencia
description: Titkosítja a bemeneti adatokat a megadott kitöltési móddal.
type: docs
weight: 53
url: /hu/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metódus


Titkosítja a bemeneti adatot a megadott kitöltési móddal.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) titkosítandó tömb. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Kitöltési mód. |

### Visszatérési érték

Titkosított adat bájt tömb formátumban.

## Lásd még

* Típusdefiníció [ByteArrayPtr](../../../system/bytearrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Osztály [RSA](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)