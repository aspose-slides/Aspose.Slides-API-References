---
title: Read()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Odczytuje pojedynczy znak ze strumienia.
type: docs
weight: 40
url: /pl/system.io/stringreader/read/
---
## StringReader::Read() metoda

Odczytuje pojedynczy znak ze strumienia.

```cpp
virtual int System::IO::StringReader::Read() override
```

### Wartość zwracana

Znak odczytany lub -1, jeśli nie odczytano żadnego znaku

## StringReader::Read(ArrayPtr\<char_t\>, int, int) metoda

Odczytuje określoną liczbę znaków ze strumienia do podanej tablicy znaków zaczynając od określonej pozycji.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tablica znaków, do której zostaną zapisane odczytane ze strumienia znaki |
| index | int | Indeks zerowy w **buffer**, od którego rozpocząć zapisywanie |
| count | int | Liczba znaków do odczytania ze strumienia |

### Wartość zwracana

Liczba znaków odczytanych ze strumienia

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [StringReader](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)