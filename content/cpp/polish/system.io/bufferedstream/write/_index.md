---
title: Write()
second_title: Aspose.Slides dla C++ Referencja API
description: Zapisuje określony podzakres bajtów z podanej tablicy bajtów do leżącego pod spodem strumienia.
type: docs
weight: 66
url: /pl/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Zapisuje określony podzakres bajtów z określonej tablicy bajtów do leżącego pod spodem strumienia.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisu |
| offset | **int32_t** | Indeks zaczynający się od 0 elementu w **buffer**, od którego zaczyna się podzakres do zapisu |
| count | **int32_t** | Liczba elementów w podzakresie do zapisu |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Zapisuje określony podzakres bajtów z określonej tablicy bajtów do leżącego pod spodem strumienia.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisu |
| offset | **int32_t** | Indeks zaczynający się od 0 elementu w **buffer**, od którego zaczyna się podzakres do zapisu |
| count | **int32_t** | Liczba elementów w podzakresie do zapisu |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [BufferedStream](../)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)