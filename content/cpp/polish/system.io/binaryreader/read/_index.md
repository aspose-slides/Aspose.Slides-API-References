---
title: Read()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Odczytuje pojedynczy znak ze strumienia wejściowego.
type: docs
weight: 66
url: /pl/system.io/binaryreader/read/
---
## BinaryReader::Read() method

Odczytuje pojedynczy znak ze strumienia wejściowego.

```cpp
virtual int System::IO::BinaryReader::Read()
```

### Return Value

Zwrócony znak zakodowany w kodowaniu UTF-16; jeśli odczytany znak jest reprezentowany przez dwa punkty kodowe w kodowaniu UTF-16, zwracana jest tylko wysoka surrogata.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) method

Odczytuje określoną liczbę bajtów ze strumienia wejściowego i zapisuje je do określonej tablicy bajtów.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zapisywane są odczytane bajty |
| index | int | Pozycja zerowa w **buffer**, od której rozpocząć zapisywanie |
| count | int | Liczba bajtów do odczytania |

### Wartość zwracana

Liczba odczytanych bajtów

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) method

Odczytuje określoną liczbę znaków ze strumienia wejściowego, konwertuje je na kodowanie UTF-16 i zapisuje powstałe znaki UTF-16 do określonej tablicy znaków, zaczynając od określonej pozycji.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tablica znaków UTF-16, do której zapisywane są znaki odczytane ze strumienia wejściowego |
| index | int | Indeks zerowy w **buffer**, od którego rozpocząć zapisywanie |
| count | int | Liczba znaków do odczytania ze strumienia |

### Wartość zwracana

Liczba znaków odczytanych ze strumienia wejściowego

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [BinaryReader](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)