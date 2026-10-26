---
title: VerifySignature()
second_title: Aspose.Slides a C++ API referencia
description: Ellenőrizze a DSA aláírást a megadott adatokra.
type: docs
weight: 14
url: /hu/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) metódus

Ellenőrizze a(z) [DSA](../) aláírást a megadott adatokra.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) aláírva **rgb_signature**-val. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) aláírás. |

### Visszatérési érték

true - ha **rgb_signature** egyezik a **rgb_hash**-on kiszámított [DSA](../) aláírással, egyébként - false.

## Lásd még

* Típusdefiníció [ByteArrayPtr](../../../system/bytearrayptr/)
* Osztály [DSA](../)
* Névterület [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)