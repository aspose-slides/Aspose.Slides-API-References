---
title: SignData()
second_title: Aspose.Slides for C++ API referencia
description: Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmus használatával, és aláírja az eredményt.
type: docs
weight: 79
url: /hu/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmus használatával, és aláírja az eredményt.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. visszaadja az ECDSA aláírást a bemeneti adatokhoz. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmus használatával, és aláírja az eredményt.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. |
| offset | **int32_t** | Eltolás a **data**-ban. |
| count | **int32_t** | A bemeneti adatként használandó bájtok száma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. visszaadja az ECDSA aláírást a bemeneti adatokhoz. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

Kiszámítja a megadott bináris adatfolyam hash értékét a megadott hash algoritmus használatával, és aláírja az eredményt.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Bináris adatfolyam. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. visszaadja az ECDSA aláírást a bemeneti adatokhoz. |

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsa](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)