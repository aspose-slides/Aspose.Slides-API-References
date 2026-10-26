---
title: VerifyData()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi az adat aláírását.
type: docs
weight: 209
url: /hu/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method

Ellenőrzi az adat aláírását.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) az aláírás ellenőrzéséhez. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírás a fogadott módon. |

### Visszatérési érték

Igaz, ha az aláírás érvényes, egyébként hamis.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Ellenőrzi, hogy a megadott adat aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírt adat. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírás adata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. igaz, ha az aláírás érvényes, egyébként - hamis. |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Ellenőrzi, hogy a megadott adat aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírt adat. |
| offset | **int32_t** | Eltolás a **data**-ban. |
| count | **int32_t** | Hashelandó bájtok száma. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírás adata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. igaz, ha az aláírás érvényes, egyébként - hamis. |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Ellenőrzi, hogy a megadott bináris adatfolyam aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Aláírt adat. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírás adata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. igaz, ha az aláírás érvényes, egyébként - hamis. |

## Lásd még

* Típusdefiníció [ByteArrayPtr](../../../system/bytearrayptr/)
* Típusdefiníció [StreamPtr](../../../system/streamptr/)
* Osztály [DSACryptoServiceProvider](../)
* Struktúra [HashAlgorithmName](../../hashalgorithmname/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)