---
title: SignData()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Oblicza wartość skrótu określonej tablicy danych przy użyciu określonego algorytmu skrótu i wypełnienia oraz podpisuje wynik.
type: docs
weight: 131
url: /pl/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metoda


Oblicza wartość skrótu określonej tablicy danych przy użyciu określonego algorytmu skrótu i wypełnienia oraz podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tablica danych wejściowych. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Tryb wypełnienia. zwraca podpis [RSA](../) dla danych wejściowych. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metoda


Oblicza wartość skrótu określonej tablicy danych przy użyciu określonego algorytmu skrótu i wypełnienia oraz podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tablica danych wejściowych. |
| offset | **int32_t** | Przesunięcie w **data**. |
| count | **int32_t** | Liczba bajtów używana jako dane wejściowe. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Tryb wypełnienia. zwraca podpis [RSA](../) dla danych wejściowych. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metoda


Oblicza wartość skrótu określonego strumienia binarnego przy użyciu określonego algorytmu skrótu i wypełnienia oraz podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Strumień binarny. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm skrótu. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Tryb wypełnienia. zwraca podpis [RSA](../) dla danych wejściowych. |

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasa [RSASignaturePadding](../../rsasignaturepadding/)
* Klasa [RSA](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)