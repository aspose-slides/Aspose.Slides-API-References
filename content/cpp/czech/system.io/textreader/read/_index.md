---
title: Read()
second_title: Aspose.Slides pro C++ API Reference
description: Načte jeden znak ze streamu.
type: docs
weight: 40
url: /cs/system.io/textreader/read/
---
## TextReader::Read() metoda

Načte jeden znak ze streamu.

```cpp
virtual int System::IO::TextReader::Read()
```

### Návratová hodnota

Znak zakódovaný v UTF-16; pokud je načtený znak reprezentován dvěma kódy v kódování UTF-16, vrátí se pouze vysoká surogátní dvojice.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) metoda

Načte zadaný počet znaků ze streamu a zapíše je do určeného pole znaků začínajícího na zadané pozici.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Pole znaků UTF-16, do kterého se zapíší načtené znaky ze streamu |
| index | int | Index od 0 v **buffer**, kde začít zapisovat |
| count | int | Počet znaků, které se mají načíst ze streamu |

### Návratová hodnota

Počet znaků načtených ze streamu

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [TextReader](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)