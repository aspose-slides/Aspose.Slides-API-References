---
title: SignHash()
second_title: Aspose.Slides C++ API-referencia
description: Kiszámítja a megadott hash érték aláírását.
type: docs
weight: 196
url: /hu/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) metódus

Kiszámítja a megadott hash érték aláírását.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash érték. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash algoritmus. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Kitöltési mód. visszaadja [RSA](../../rsa/) aláírást a megadott hash-hez. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) metódus

Kiszámítja a megadott bemeneti érték aláírását. Nincs implementálva.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A aláírandó adatok hash értéke. |
| str | const [String](../../../system/string/)\& | A hash létrehozásához használt hash algoritmus azonosító. |

### Visszatérési érték

[RSA](../../rsa/) aláírás a megadott adatokhoz.

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)