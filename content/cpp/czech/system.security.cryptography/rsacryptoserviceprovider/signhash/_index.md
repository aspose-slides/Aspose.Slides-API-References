---
title: SignHash()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vypočítá podpis pro zadanou hash hodnotu.
type: docs
weight: 196
url: /cs/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) metoda


Vypočítá podpis pro zadanou hash hodnotu.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hodnota hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmus hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Režim výplně. vrátí [RSA](../../rsa/) podpis pro zadaný hash. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) metoda


Vypočítá podpis zadané vstupní hodnoty. Není implementováno.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hodnota hash dat k podepsání. |
| str | const [String](../../../system/string/)\& | Identifikátor hash algoritmu použitý k vytvoření hash. |

### Návratová hodnota

[RSA](../../rsa/) podpis pro zadaná data.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [RSASignaturePadding](../../rsasignaturepadding/)
* Třída [RSACryptoServiceProvider](../)
* Třída [String](../../../system/string/)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)