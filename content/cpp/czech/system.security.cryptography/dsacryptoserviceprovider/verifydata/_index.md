---
title: VerifyData()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje podpis dat.
type: docs
weight: 209
url: /cs/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) metoda

Kontroluje podpis dat.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) pro kontrolu podpisu. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpis tak, jak byl přijat. |

### Návratová hodnota

True if signature is valid, false otherwise.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Ověřuje, zda je podpis specifikovaných dat platný.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podepsaná data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hashovací algoritmus. vrátí true, pokud je podpis platný, jinak - false. |

### Návratová hodnota

True if signature is valid, otherwise - false.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Ověřuje, zda je podpis specifikovaných dat platný.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podepsaná data. |
| offset | **int32_t** | Posun v **data**. |
| count | **int32_t** | Počet bajtů k hashování. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hashovací algoritmus. vrátí true, pokud je podpis platný, jinak - false. |

### Návratová hodnota

True if signature is valid, otherwise - false.

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Ověřuje, zda je podpis specifikovaného binárního proudu platný.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Podepsaná data. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hashovací algoritmus. vrátí true, pokud je podpis platný, jinak - false. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Třída [DSACryptoServiceProvider](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)