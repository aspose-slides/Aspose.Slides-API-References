---
title: Read()
second_title: Aspose.Slides dla C++ – referencja API
description: Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.
type: docs
weight: 391
url: /pl/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Odczytuje określoną liczbę bajtów z strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja indeksowana od zera w **buffer**, od której rozpocząć zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Odczytuje określoną liczbę bajtów z strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja indeksowana od zera w **buffer**, od której rozpocząć zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [SslStream](../)
* Przestrzeń nazw [System::Net::Security](../../)
* Biblioteka [Aspose.Slides](../../../)