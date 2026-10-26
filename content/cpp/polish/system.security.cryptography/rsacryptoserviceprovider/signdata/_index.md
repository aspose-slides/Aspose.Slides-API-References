---
title: SignData()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Oblicza podpis określonej wartości wejściowej.
type: docs
weight: 183
url: /pl/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) method


Oblicza podpis określonej wartości wejściowej.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) do odczytu danych wejściowych. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algorytm skrótu do użycia. |

### Wartość zwracana

[RSA](../../rsa/) podpis dla określonych danych.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) method


Oblicza podpis określonej wartości wejściowej.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień do odczytu danych, które mają zostać podpisane. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algorytm skrótu do użycia. |

### Wartość zwracana

[RSA](../../rsa/) podpis dla określonych danych.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) method


Oblicza podpis określonej wartości wejściowej.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) do odczytu danych wejściowych. |
| offset | **int32_t** | Indeks początkowy fragmentu bufora wejściowego. |
| count | **int32_t** | Rozmiar fragmentu bufora wejściowego. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algorytm skrótu do użycia. |

### Wartość zwracana

[RSA](../../rsa/) podpis dla określonych danych.

## Zobacz też

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [RSACryptoServiceProvider](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)