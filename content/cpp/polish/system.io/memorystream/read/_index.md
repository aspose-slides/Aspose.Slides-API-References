---
title: Read()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.
type: docs
weight: 79
url: /pl/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, do której mają zostać zapisane odczytane bajty |
| offset | **int32_t** | Pozycja w **buffer** zaczynająca się od 0, w której rozpocząć zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy bajtów, do którego mają zostać zapisane odczytane bajty |
| offset | **int32_t** | Pozycja w **buffer** zaczynająca się od 0, w której rozpocząć zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [MemoryStream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)