---
title: SignHash()
second_title: Aspose.Slides C++ API referencia
description: Kiszámítja a megadott hash érték aláírását.
type: docs
weight: 144
url: /hu/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) metódus

Kiszámítja a megadott hash érték aláírását.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash érték. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash algoritmus. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Kitöltési mód. visszaadja a(z) [RSA](../) aláírást a megadott hash-hez. |

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [RSASignaturePadding](../../rsasignaturepadding/)
* Osztály [RSA](../)
* Struktúra [HashAlgorithmName](../../hashalgorithmname/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)