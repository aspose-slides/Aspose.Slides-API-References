---
title: Write()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zapisuje określoną tablicę bajtów do strumienia.
type: docs
weight: 404
url: /pl/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) metoda


Zapisuje określoną tablicę bajtów do strumienia.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów do zapisu. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisu |
| offset | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisu |
| count | **int32_t** | Liczba elementów w podzakresie do zapisu |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) metoda


Zapisuje określoną tablicę bajtów do strumienia.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tablica bajtów do zapisu. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisu |
| offset | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisu |
| count | **int32_t** | Liczba elementów w podzakresie do zapisu |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [SslStream](../)
* Przestrzeń nazw [System::Net::Security](../../)
* Biblioteka [Aspose.Slides](../../../)