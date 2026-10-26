---
title: VerifyHash()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje podpis dat.
type: docs
weight: 222
url: /cs/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method

Kontroluje podpis dat.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash vypočítaný pro přijatá data. |
| str | const [String](../../../system/string/)\& | Název použitého hash algoritmu. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpis tak, jak byl přijat. |

### Návratová hodnota

True pokud je podpis platný, false jinak.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) method

Ověřuje, že podpis zadaného hashe je platný.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hodnota hashe podepsaných dat. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Režim výplně. vrátí true, pokud je podpis platný, jinak - false. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [RSACryptoServiceProvider](../)
* Třída [RSASignaturePadding](../../rsasignaturepadding/)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)