---
title: SignData()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Oblicza wartość skrótu podanej tablicy danych przy użyciu określonego algorytmu skrótu i podpisuje wynik.
type: docs
weight: 79
url: /pl/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metoda


Oblicza wartość skrótu podanej tablicy danych przy użyciu określonego algorytmu skrótu i podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Wejściowa tablica danych. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. zwróć [DSA](../) podpis dla danych wejściowych. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metoda


Oblicza wartość skrótu podanej tablicy danych przy użyciu określonego algorytmu skrótu i podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Wejściowa tablica danych. |
| offset | **int32_t** | Przesunięcie w **data**. |
| count | **int32_t** | Liczba bajtów używanych jako dane wejściowe. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. zwróć [DSA](../) podpis dla danych wejściowych. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) metoda


Oblicza wartość skrótu podanego strumienia binarnego przy użyciu określonego algorytmu skrótu i podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Strumień binarny. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. zwróć [DSA](../) podpis dla danych wejściowych. |

## Zobacz także

* Definicja typu [ByteArrayPtr](../../../system/bytearrayptr/)
* Definicja typu [StreamPtr](../../../system/streamptr/)
* Klasa [DSA](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)