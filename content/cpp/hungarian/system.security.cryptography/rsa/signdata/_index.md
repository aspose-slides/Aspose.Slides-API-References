---
title: SignData()
second_title: Aspose.Slides for C++ API Referenciája
description: Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmus és kitöltés segítségével, és aláírja az eredményt.
type: docs
weight: 131
url: /hu/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metódus

Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmus és kitöltés segítségével, és aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Kitöltési mód. visszaadja a [RSA](../) aláírást a bemeneti adatokhoz. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metódus

Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmus és kitöltés segítségével, és aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. |
| offset | **int32_t** | Eltolás a **data**-ban. |
| count | **int32_t** | A bemeneti adathoz használandó bájtok száma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Kitöltési mód. visszaadja a [RSA](../) aláírást a bemeneti adatokhoz. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metódus

Kiszámítja a megadott bináris adatfolyam hash értékét a megadott hash algoritmus és kitöltés segítségével, és aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Bináris adatfolyam. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Kitöltési mód. visszaadja a [RSA](../) aláírást a bemeneti adatokhoz. |

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Osztály [RSASignaturePadding](../../rsasignaturepadding/)
* Osztály [RSA](../)
* Struktúra [HashAlgorithmName](../../hashalgorithmname/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)