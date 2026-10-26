---
title: VerifyData()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Ověřuje, že podpis zadaných dat je platný.
type: docs
weight: 105
url: /cs/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Ověřuje, že podpis zadaných dat je platný.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podepsaná data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrátí true, pokud je podpis platný, jinak - false. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Ověřuje, že podpis zadaných dat je platný.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podepsaná data. |
| offset | **int32_t** | Offset v **data**. |
| count | **int32_t** | Počet bajtů pro hashování. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrátí true, pokud je podpis platný, jinak - false. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Ověřuje, že podpis zadaného binárního proudu je platný.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Podepsaná data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. vrátí true, pokud je podpis platný, jinak - false. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Třída [ECDsa](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)