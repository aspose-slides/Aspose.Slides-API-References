---
title: VerifyData()
second_title: Aspose.Slides C++ API Referencia
description: Ellenőrzi, hogy a megadott adatok aláírása érvényes-e.
type: docs
weight: 105
url: /hu/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metódus

Ellenőrzi, hogy a megadott adatok aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírt adat. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírási adat. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. true értéket ad vissza, ha az aláírás érvényes, egyébként - false. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metódus

Ellenőrzi, hogy a megadott adatok aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírt adat. |
| offset | **int32_t** | Eltolás a **data**-ban. |
| count | **int32_t** | A hash-hez használandó bájtok száma. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírási adat. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. true értéket ad vissza, ha az aláírás érvényes, egyébként - false. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metódus

Ellenőrzi, hogy a megadott bináris folyam aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Aláírt adat. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírási adat. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. true értéket ad vissza, ha az aláírás érvényes, egyébként - false. |

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Osztály [ECDsa](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Névtér [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)