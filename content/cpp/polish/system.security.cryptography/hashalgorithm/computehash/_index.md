---
title: ComputeHash()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Generuje skrót bufora.
type: docs
weight: 14
url: /pl/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) metoda


Generuje skrót bufora.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bufor źródłowy. |

### Wartość zwracana

Obliczona wartość skrótu.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) metoda


Generuje skrót fragmentu bufora.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bufor źródłowy. |
| offset | int | Przesunięcie w buforze źródłowym. |
| count | int | Liczba bajtów do użycia z bufora źródłowego. |

### Wartość zwracana

Obliczona wartość skrótu.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) metoda


Odczytuje strumień do końca i oblicza skrót odczytanych danych.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Strumień do odczytu danych. |

### Wartość zwracana

Obliczona wartość skrótu dla całych danych strumienia.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [HashAlgorithm](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)