---
title: VerifyHash()
second_title: Aspose.Slides C++ API-referencia
description: Ellenőrzi az adat aláírását.
type: docs
weight: 222
url: /hu/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) metódus


Ellenőrzi az adat aláírását.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A fogadott adatokhoz számított hash. |
| str | const [String](../../../system/string/)\& | A használt hash algoritmus neve. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A fogadott aláírás. |

### Visszatérési érték

Igaz, ha az aláírás érvényes, egyébként hamis.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metódus


Ellenőrzi, hogy a megadott hash aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Az aláírt adat hash értéke. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Az aláírás adata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Kitöltési mód. |

true értéket ad vissza, ha az aláírás érvényes, egyébként - false.

## See Also

* Típusdefiníció [ByteArrayPtr](../../../system/bytearrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [RSACryptoServiceProvider](../)
* Osztály [RSASignaturePadding](../../rsasignaturepadding/)
* Struktúra [HashAlgorithmName](../../hashalgorithmname/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)