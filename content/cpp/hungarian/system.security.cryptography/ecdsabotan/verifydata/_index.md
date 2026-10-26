---
title: VerifyData()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi, hogy a megadott adatok aláírása érvényes-e.
type: docs
weight: 170
url: /hu/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


Ellenőrzi, hogy a megadott adatok aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírt adat. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírási adat. true-t ad vissza, ha az aláírás érvényes, egyébként false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) method


Ellenőrzi, hogy a megadott adatok aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírt adat. |
| offset | **int32_t** | **data** eltolása. |
| count | **int32_t** | A hash-elni kívánt bájtok száma. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírási adat. true-t ad vissza, ha az aláírás érvényes, egyébként false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) method


Ellenőrzi, hogy a megadott bináris adatfolyam aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Aláírt adat. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírási adat. true-t ad vissza, ha az aláírás érvényes, egyébként false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Ellenőrzi, hogy a megadott adatok aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírt adat. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírási adat. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritmus. true-t ad vissza, ha az aláírás érvényes, egyébként false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Ellenőrzi, hogy a megadott adatok aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírt adat. |
| offset | **int32_t** | **data** eltolása. |
| count | **int32_t** | A hash-elni kívánt bájtok száma. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírási adat. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritmus. true-t ad vissza, ha az aláírás érvényes, egyébként false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Ellenőrzi, hogy a megadott bináris adatfolyam aláírása érvényes-e.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Aláírt adat. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Aláírási adat. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash-algoritmus. true-t ad vissza, ha az aláírás érvényes, egyébként false. |

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Osztály [ECDsaBotan](../)
* Struktúra [HashAlgorithmName](../../hashalgorithmname/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)