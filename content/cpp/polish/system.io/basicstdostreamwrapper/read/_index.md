---
title: Read()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Jeśli tryb opakowywania jest binarny, odczytuje określoną liczbę bajtów ze strumienia, w przeciwnym razie odczytuje określoną liczbę znaków i konwertuje je na typ uint8_t. Zapisuje wynik odczytu do określonej tablicy bajtów. Nieobsługiwane!
type: docs
weight: 66
url: /pl/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Jeśli tryb opakowywania jest binarny, odczytuje określoną liczbę bajtów z strumienia, w przeciwnym razie odczytuje określoną liczbę znaków i konwertuje je na typ **uint8_t**. Zapisuje wynik odczytu do określonej tablicy bajtów. Nieobsługiwane!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja w **buffer** zaczynająca się od 0, od której rozpoczyna się zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów lub znaków

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy bajtów, do którego zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja w **buffer** zaczynająca się od 0, od której rozpoczyna się zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [BasicSTDOStreamWrapper](../)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)