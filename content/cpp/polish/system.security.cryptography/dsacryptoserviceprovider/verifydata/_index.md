---
title: VerifyData()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Sprawdza podpis danych.
type: docs
weight: 209
url: /pl/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


Sprawdza podpis danych.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) do sprawdzenia podpisu. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpis otrzymany. |

### Wartość zwracana

true, jeśli podpis jest prawidłowy, false w przeciwnym razie.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Weryfikuje, czy podpis określonych danych jest prawidłowy.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpisane dane. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dane podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. true jeśli podpis jest prawidłowy, w przeciwnym razie - false. |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Weryfikuje, czy podpis określonych danych jest prawidłowy.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Podpisane dane. |
| offset | **int32_t** | Offset w **data**. |
| count | **int32_t** | Liczba bajtów do haszowania. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dane podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. true jeśli podpis jest prawidłowy, w przeciwnym razie - false. |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Weryfikuje, czy podpis określonego strumienia binarnego jest prawidłowy.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Podpisane dane. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dane podpisu. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. true jeśli podpis jest prawidłowy, w przeciwnym razie - false. |

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasa [DSACryptoServiceProvider](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)