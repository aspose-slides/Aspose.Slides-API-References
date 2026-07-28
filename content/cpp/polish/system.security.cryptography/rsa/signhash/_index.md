---
title: SignHash()
second_title: Aspose.Slides dla C++ API Reference
description: Oblicza podpis dla określonej wartości skrótu.
type: docs
weight: 144
url: /pl/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) metoda

Oblicza podpis dla określonej wartości skrótu.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Wartość skrótu. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algorytm skrótu. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Tryb wypełnienia. zwraca [RSA](../) podpis dla określonego skrótu. |

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)