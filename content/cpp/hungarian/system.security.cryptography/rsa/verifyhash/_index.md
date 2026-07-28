---
title: VerifyHash()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi, hogy a megadott hash aláírása érvényes-e.
type: docs
weight: 170
url: /hu/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metódus


Ellenőrzi, hogy a megadott hash aláírása érvényes-e.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Az aláírt adatok hash értéke. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Aláírási adatok. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Kitöltési mód. true-t ad vissza, ha az aláírás érvényes, egyébként - false. |

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [RSASignaturePadding](../../rsasignaturepadding/)
* Osztály [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Névtér [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)