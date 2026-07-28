---
title: VerifySignature()
second_title: Aspose.Slides C++ API-referencia
description: Ellenőrizze a DSA aláírást a megadott adatokhoz.
type: docs
weight: 118
url: /hu/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) metódus


Ellenőrizze a [DSA](../../dsa/) aláírást a megadott adatokhoz.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) **rgb_signature**-val aláírva. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) aláírás. |

### Visszatérési érték

true - ha a **rgb_signature** egyezik a **rgb_hash**-on számított [DSA](../../dsa/) aláírással, egyébként - false.

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Osztály [DSACryptoServiceProvider](../)
* Névtér [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)