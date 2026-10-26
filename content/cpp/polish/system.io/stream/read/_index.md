---
title: Read()
second_title: Aspose.Slides for C++ – referencja API
description: Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.
type: docs
weight: 27
url: /pl/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja bazująca na zerze w **buffer**, od której rozpocząć zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tablica widoku bajtów, do której zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja bazująca na zerze w **buffer**, od której rozpocząć zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) metoda


Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonej tablicy bajtów.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| N | Rozmiar tablicy stosu |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Tablica bajtów stosu, do której zapisywane są odczytane bajty |
| offset | **int32_t** | Pozycja bazująca na zerze w **buffer**, od której rozpocząć zapisywanie |
| count | **int32_t** | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## Stream::Read(const System::Span\<uint8_t\>\&) metoda


Odczytuje określoną liczbę bajtów ze strumienia i zapisuje je do określonego zakresu bajtów.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | Zakres bajtów, do którego zapisywane są odczytane bajty |

### Wartość zwracana

Liczba odczytanych bajtów

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Stream](../)
* Klasa [Span](../../../system/span/)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)