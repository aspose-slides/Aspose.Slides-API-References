---
title: Read()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Jeśli tryb opakowania jest binarny, odczytuje określoną liczbę bajtów ze strumienia, w przeciwnym razie odczytuje określoną liczbę znaków i konwertuje je na typ uint8_t. Zapisuje wynik odczytu do określonej tablicy bajtów.
type: docs
weight: 66
url: /pl/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Jeśli tryb opakowania jest binarny, odczytuje określoną liczbę bajtów z strumienia, w przeciwnym razie odczytuje określoną liczbę znaków i konwertuje je do typu **uint8_t**. Zapisuje wynik odczytu do określonej tablicy bajtów.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja w **buffer** rozpoczynająca zapis (indeks zerowy) |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów lub znaków

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Odczytuje określoną liczbę bajtów z strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy bajtów, do którego zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja w **buffer** rozpoczynająca zapis (indeks zerowy) |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [BasicSTDIOStreamWrapper](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)