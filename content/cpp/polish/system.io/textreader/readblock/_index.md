---
title: ReadBlock()
second_title: Aspose.Slides dla C++ Referencja API
description: Odczytuje określoną maksymalną liczbę znaków z bieżącego czytnika tekstu i zapisuje dane do bufora, zaczynając od określonego indeksu.
type: docs
weight: 53
url: /pl/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) metoda

Odczytuje określoną maksymalną liczbę znaków z bieżącego czytnika tekstu i zapisuje dane do bufora, zaczynając od określonego indeksu.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Bufor znaków, do którego zapisywane są odczytane dane |
| index | int | Indeks zerowy w **buffer** określający miejsce rozpoczęcia zapisu |
| count | int | Maksymalna liczba znaków do odczytania |

### Wartość zwracana

Rzeczywista liczba odczytanych znaków

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [TextReader](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)