---
title: SignHash()
second_title: Aspose.Slides pro C++ – reference API
description: Vypočítá podpis pro zadanou hodnotu hash.
type: docs
weight: 144
url: /cs/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) metoda


Vypočítá podpis pro zadanou hodnotu hash.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hodnota hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmus hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Režim výplně. vrací [RSA](../) podpis pro zadaný hash. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [RSASignaturePadding](../../rsasignaturepadding/)
* Třída [RSA](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)