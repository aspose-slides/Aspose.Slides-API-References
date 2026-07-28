---
title: Read()
second_title: Odwołanie API Aspose.Slides dla C++
description: Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.
type: docs
weight: 144
url: /pl/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Odczytuje określoną liczbę bajtów z strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja w **buffer** rozpoczynająca się od 0, od której rozpocząć zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Odczytuje określoną liczbę bajtów z strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy bajtów, do którego zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja w **buffer** rozpoczynająca się od 0, od której rozpocząć zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## Zobacz również

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [UnmanagedMemoryStream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)