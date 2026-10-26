---
title: SignHash()
second_title: Aspose.Slides dla C++ – referencja API
description: Oblicza podpis dla określonej wartości skrótu.
type: docs
weight: 196
url: /pl/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) metoda

Oblicza podpis dla określonej wartości skrótu.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Wartość skrótu. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algorytm skrótu. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Tryb wypełnienia. zwraca [RSA](../../rsa/) podpis dla określonego skrótu. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) metoda

Oblicza podpis określonej wartości wejściowej. Nie zaimplementowano.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Wartość skrótu danych do podpisania. |
| str | const [String](../../../system/string/)\& | Identyfikator algorytmu skrótu używany do utworzenia skrótu. |

### Wartość zwracana

[RSA](../../rsa/) podpis dla określonych danych.

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)