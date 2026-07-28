---
title: Write()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zapisuje określony podzakres bajtów z podanej tablicy bajtów do strumienia.
type: docs
weight: 248
url: /pl/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisania. |
| offset | **int32_t** | Indeks zerowy elemnet w **buffer**, od którego zaczyna się podzakres do zapisania. |
| count | **int32_t** | Liczba elementów w podzakresie do zapisania. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy zawierający bajty do zapisania. |
| offset | **int32_t** | Indeks zerowy elemnet w **buffer**, od którego zaczyna się podzakres do zapisania. |
| count | **int32_t** | Liczba elementów w podzakresie do zapisania. |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [FileStream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)