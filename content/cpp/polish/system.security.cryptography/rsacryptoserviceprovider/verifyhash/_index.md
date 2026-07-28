---
title: VerifyHash()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Sprawdza podpis danych.
type: docs
weight: 222
url: /pl/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) metoda

Sprawdza podpis danych.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Skrót obliczony dla otrzymanych danych. |
| str | const [String](../../../system/string/)\& | Nazwa używanego algorytmu skrótu. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Otrzymany podpis. |

### Wartość zwracana

True, jeśli podpis jest prawidłowy, false w przeciwnym razie.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metoda

Sprawdza, czy podpis określonego skrótu jest prawidłowy.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Wartość skrótu podpisanych danych. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Dane podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Tryb wypełnienia. zwraca true, jeśli podpis jest prawidłowy, w przeciwnym razie - false. |

## Zobacz także

* Definicja typu [ByteArrayPtr](../../../system/bytearrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [RSACryptoServiceProvider](../)
* Klasa [RSASignaturePadding](../../rsasignaturepadding/)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)