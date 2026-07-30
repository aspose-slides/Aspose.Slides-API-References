---
title: SignData()
second_title: Aspose.Slides pro C++ API Reference
description: Vypočítá hodnotu hash zadaného pole dat pomocí určeného hash algoritmu a výplně a výsledek podepíše.
type: docs
weight: 131
url: /cs/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metoda


Vypočítá hodnotu hash zadaného pole dat pomocí určeného hash algoritmu a výplně a výsledek podepíše.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Vstupní pole dat. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Režim výplně. vrátí [RSA](../) podpis pro vstupní data. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metoda


Vypočítá hodnotu hash zadaného pole dat pomocí určeného hash algoritmu a výplně a výsledek podepíše.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Vstupní pole dat. |
| offset | **int32_t** | Posun v **data**. |
| count | **int32_t** | Počet bajtů použité jako vstupní data. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Režim výplně. vrátí [RSA](../) podpis pro vstupní data. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metoda


Vypočítá hodnotu hash zadaného binárního proudu pomocí určeného hash algoritmu a výplně a výsledek podepíše.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Binární proud. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritmus. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Režim výplně. vrátí [RSA](../) podpis pro vstupní data. |

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)