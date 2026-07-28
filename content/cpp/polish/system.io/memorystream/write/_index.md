---
title: Write()
second_title: Referencja API Aspose.Slides dla C++
description: Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.
type: docs
weight: 92
url: /pl/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisania |
| offset | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisania |
| count | **int32_t** | Liczba elementów w podzakresie do zapisania |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy zawierający bajty do zapisania |
| offset | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisania |
| count | **int32_t** | Liczba elementów w podzakresie do zapisania |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [MemoryStream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)