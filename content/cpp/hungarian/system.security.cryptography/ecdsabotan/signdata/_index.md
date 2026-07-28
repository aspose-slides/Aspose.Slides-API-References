---
title: SignData()
second_title: Aspose.Slides C++ API referencia
description: Számítja a megadott adat tömb hash értékét, és aláírja az eredményt.
type: docs
weight: 131
url: /hu/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) metódus

Számítja a megadott adat tömb hash értékét, és aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. visszaadja az ECDSA aláírást a bemeneti adatokhoz. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) metódus

Számítja a megadott adat tömb hash értékét, és aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. |
| offset | **int32_t** | Offset a **data**-ban. |
| count | **int32_t** | A bemeneti adatokként használandó bájtok száma. visszaadja az ECDSA aláírást a bemeneti adatokhoz. |

## ECDsaBotan::SignData(const StreamPtr\&) metódus

Számítja a megadott bináris adatfolyam hash értékét, és aláírja az eredményt.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Bináris adatfolyam. visszaadja az ECDSA aláírást a bemeneti adatokhoz. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metódus

Számítja a megadott adat tömb hash értékét a megadott hash algoritmus használatával, és aláírja az eredményt.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. visszaadja az ECDSA aláírást a bemeneti adatokhoz. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metódus

Számítja a megadott adat tömb hash értékét a megadott hash algoritmus használatával, és aláírja az eredményt.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Bemeneti adat tömb. |
| offset | **int32_t** | Offset a **data**-ban. |
| count | **int32_t** | A bemeneti adatokként használandó bájtok száma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. visszaadja az ECDSA aláírást a bemeneti adatokhoz. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) metódus

Számítja a megadott bináris adatfolyam hash értékét a megadott hash algoritmus használatával, és aláírja az eredményt.

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
* Osztály [ECDsaBotan](../)
* Struktúra [HashAlgorithmName](../../hashalgorithmname/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)