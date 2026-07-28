---
title: Write()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.
type: docs
weight: 53
url: /pl/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisu |
| offset | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisu |
| count | **int32_t** | Liczba elementów w podzakresie do zapisu |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy zawierający bajty do zapisu |
| offset | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisu |
| count | **int32_t** | Liczba elementów w podzakresie do zapisu |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| N | Rozmiar tablicy stosu |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Tablica stosu zawierająca bajty do zapisu |
| offset | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisu |
| count | **int32_t** | Liczba elementów w podzakresie do zapisu |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) metoda

Zapisuje określony podzakres bajtów z określonego zakresu bajtów do strumienia.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | Zakres bajtów, z którego odczytywać zapisywane bajty |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Stream](../)
* Klasa [ReadOnlySpan](../../../system/readonlyspan/)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)