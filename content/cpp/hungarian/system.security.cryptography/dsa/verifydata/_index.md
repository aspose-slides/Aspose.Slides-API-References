---
title: VerifyData()
second_title: Aspose.Slides C++ API hivatkozás
description: Ellenőrzi, hogy a megadott adat aláírása érvényes-e.
type: docs
weight: 92
url: /hu/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metódus

Ellenőrzi, hogy a megadott adat aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírt adat. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírás adata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. true értéket ad vissza, ha az aláírás érvényes, egyébként - false. |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metódus

Ellenőrzi, hogy a megadott adat aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírt adat. |
| offset | **int32_t** | Eltolás a **data**-ban. |
| count | **int32_t** | A hash-elendő bájtok száma. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírás adata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. true értéket ad vissza, ha az aláírás érvényes, egyébként - false. |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metódus

Ellenőrzi, hogy a megadott bináris adatfolyam aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Aláírt adat. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírás adata. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. true értéket ad vissza, ha az aláírás érvényes, egyébként - false. |

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)