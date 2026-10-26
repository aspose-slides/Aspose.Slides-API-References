---
title: SignData()
second_title: Aspose.Slides C++ API referencia
description: Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmus segítségével, és aláírja az eredményt.
type: docs
weight: 79
url: /hu/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metódus

Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmus segítségével, és aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. visszaadja a [DSA](../) aláírást a bemeneti adatokhoz. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metódus

Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmus segítségével, és aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. |
| offset | **int32_t** | Eltolás a **data**-ban. |
| count | **int32_t** | A bemeneti adatként használandó bájtok száma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. visszaadja a [DSA](../) aláírást a bemeneti adatokhoz. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) metódus

Kiszámítja a megadott bináris adatfolyam hash értékét a megadott hash algoritmus segítségével, és aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Bináris adatfolyam. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. visszaadja a [DSA](../) aláírást a bemeneti adatokhoz. |

## Lásd még

* Típusdefiníció [ByteArrayPtr](../../../system/bytearrayptr/)
* Típusdefiníció [StreamPtr](../../../system/streamptr/)
* Osztály [DSA](../)
* Struktúra [HashAlgorithmName](../../hashalgorithmname/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)