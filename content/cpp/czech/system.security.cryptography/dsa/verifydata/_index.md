---
title: VerifyData()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Ověřuje, že podpis uvedených dat je platný.
type: docs
weight: 92
url: /cs/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Ověřuje, že podpis uvedených dat je platný.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpisaná data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hashovací algoritmus. vrací true, pokud je podpis platný, jinak false. |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Ověřuje, že podpis uvedených dat je platný.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpisaná data. |
| offset | **int32_t** | Posun v data. |
| count | **int32_t** | Počet bajtů k hashování. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hashovací algoritmus. vrací true, pokud je podpis platný, jinak false. |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Ověřuje, že podpis uvedeného binárního proudu je platný.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Podpisaná data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hashovací algoritmus. vrací true, pokud je podpis platný, jinak false. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Třída [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)