---
title: SignData()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Oblicza wartość skrótu określonej tablicy danych przy użyciu określonego algorytmu skrótu i podpisuje wynik.
type: docs
weight: 79
url: /pl/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metoda


Oblicza wartość skrótu określonej tablicy danych przy użyciu określonego algorytmu skrótu i podpisuje wynik.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tablica danych wejściowych. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. Zwraca podpis ECDSA dla danych wejściowych. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metoda


Oblicza wartość skrótu określonej tablicy danych przy użyciu określonego algorytmu skrótu i podpisuje wynik.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tablica danych wejściowych. |
| offset | **int32_t** | Przesunięcie w **data**. |
| count | **int32_t** | Liczba bajtów używanych jako dane wejściowe. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. Zwraca podpis ECDSA dla danych wejściowych. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) metoda


Oblicza wartość skrótu określonego strumienia binarnego przy użyciu określonego algorytmu skrótu i podpisuje wynik.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Strumień binarny. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. Zwraca podpis ECDSA dla danych wejściowych. |

## Zobacz także

* Definicja typu [ByteArrayPtr](../../../system/bytearrayptr/)
* Definicja typu [StreamPtr](../../../system/streamptr/)
* Klasa [ECDsa](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)