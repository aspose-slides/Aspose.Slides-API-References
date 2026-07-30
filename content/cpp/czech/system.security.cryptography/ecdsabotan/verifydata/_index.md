---
title: VerifyData()
second_title: Aspose.Slides pro C++ - Referenční příručka API
description: Ověřuje, že podpis zadaných dat je platný.
type: docs
weight: 170
url: /cs/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) metoda


Ověřuje, že podpis zadaných dat je platný.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podepsaná data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. vrátí true, pokud je podpis platný, jinak - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) metoda


Ověřuje, že podpis zadaných dat je platný.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podepsaná data. |
| offset | **int32_t** | Posun v **data**. |
| count | **int32_t** | Počet bajtů k hashování. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. vrátí true, pokud je podpis platný, jinak - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) metoda


Ověřuje, že podpis zadaného binárního proudu je platný.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Podepsaná data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. vrátí true, pokud je podpis platný, jinak - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda


Ověřuje, že podpis zadaných dat je platný.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podepsaná data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hashovací algoritmus. vrátí true, pokud je podpis platný, jinak - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda


Ověřuje, že podpis zadaných dat je platný.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podepsaná data. |
| offset | **int32_t** | Posun v **data**. |
| count | **int32_t** | Počet bajtů k hashování. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hashovací algoritmus. vrátí true, pokud je podpis platný, jinak - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda


Ověřuje, že podpis zadaného binárního proudu je platný.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Podepsaná data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hashovací algoritmus. vrátí true, pokud je podpis platný, jinak - false. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Třída [ECDsaBotan](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)