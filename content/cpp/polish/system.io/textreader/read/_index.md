---
title: Read()
second_title: Aspose.Slides dla C++ Referencja API
description: Odczytuje pojedynczy znak ze strumienia.
type: docs
weight: 40
url: /pl/system.io/textreader/read/
---
## TextReader::Read() method

Odczytuje pojedynczy znak ze strumienia.

```cpp
virtual int System::IO::TextReader::Read()
```

### Wartość zwracana

Zwrócony znak zakodowany w kodowaniu UTF-16; jeśli odczytany znak jest reprezentowany przez dwa punkty kodowe w kodowaniu UTF-16, zwracany jest tylko wysoki surrogat.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) method

Odczytuje określoną liczbę znaków ze strumienia i zapisuje je do określonej tablicy znaków, zaczynając od określonej pozycji.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tablica znaków UTF-16, do której zapisywane są znaki odczytane ze strumienia |
| index | int | Indeks w **buffer** liczony od zera, od którego rozpocząć zapisywanie |
| count | int | Liczba znaków do odczytania ze strumienia |

### Wartość zwracana

Liczba znaków odczytanych ze strumienia

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [TextReader](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)