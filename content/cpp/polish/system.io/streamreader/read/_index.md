---
title: Read()
second_title: Aspose.Slides dla C++ Referencja API
description: Odczytuje pojedynczy znak ze strumienia.
type: docs
weight: 40
url: /pl/system.io/streamreader/read/
---
## StreamReader::Read() metoda


Odczytuje pojedynczy znak ze strumienia.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### Wartość zwracana

Zwraca znak zakodowany w UTF-16; jeśli odczytany znak jest reprezentowany przez dwa kodpunkty w kodowaniu UTF-16, zwracany jest tylko wysoki surogat.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) metoda


Odczytuje określoną liczbę znaków ze strumienia, konwertuje je na kodowanie UTF-16 i zapisuje powstałe znaki UTF-16 do określonej tablicy znaków, zaczynając od określonej pozycji.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tablica znaków UTF-16, do której zapisywane są odczytane ze strumienia znaki |
| index | int | Indeks zerowy w **buffer**, od którego rozpocząć zapisywanie |
| count | int | Liczba znaków do odczytania ze strumienia |

### Wartość zwracana

Liczba znaków odczytanych ze strumienia

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)