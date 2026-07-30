---
title: VerifyHash()
second_title: Aspose.Slides pro C++ API Reference
description: Ověřuje, že podpis zadaného hashe je platný.
type: docs
weight: 170
url: /cs/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metoda

Ověřuje, že podpis zadaného hashe je platný.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hodnota hash podepsaných dat. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Režim výplně. vrátí true, pokud je podpis platný, jinak false. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [RSASignaturePadding](../../rsasignaturepadding/)
* Třída [RSA](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)