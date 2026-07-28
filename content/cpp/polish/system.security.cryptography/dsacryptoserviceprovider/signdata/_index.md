---
title: SignData()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Oblicza podpis określonej wartości wejściowej.
type: docs
weight: 183
url: /pl/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) metoda

Oblicza podpis określonej wartości wejściowej.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) do odczytu danych wejściowych z. |

### Wartość zwracana

[DSA](../../dsa/) podpis dla określonych danych.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) metoda

Oblicza podpis określonej wartości wejściowej.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień do odczytu danych, które mają być podpisane, z. |

### Wartość zwracana

[DSA](../../dsa/) podpis dla określonych danych.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) metoda

Oblicza podpis określonej wartości wejściowej.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) do odczytu danych wejściowych z. |
| offset | **int32_t** | Indeks początkowy fragmentu bufora wejściowego. |
| count | **int32_t** | Rozmiar fragmentu bufora wejściowego. |

### Wartość zwracana

[DSA](../../dsa/) podpis dla określonych danych.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metoda

Oblicza wartość skrótu określonej tablicy danych przy użyciu podanego algorytmu skrótu i podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tablica danych wejściowych. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm hashujący. zwraca [DSA](../../dsa/) podpis dla danych wejściowych. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metoda

Oblicza wartość skrótu określonej tablicy danych przy użyciu podanego algorytmu skrótu i podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tablica danych wejściowych. |
| offset | **int32_t** | Przesunięcie w **data**. |
| count | **int32_t** | Liczba bajtów używana jako dane wejściowe. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm hashujący. zwraca [DSA](../../dsa/) podpis dla danych wejściowych. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) metoda

Oblicza wartość skrótu określonego strumienia binarnego przy użyciu podanego algorytmu skrótu i podpisuje wynik.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Strumień binarny. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algorytm hashujący. zwraca [DSA](../../dsa/) podpis dla danych wejściowych. |

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Class [Stream](../../../system.io/stream/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)