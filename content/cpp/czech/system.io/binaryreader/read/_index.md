---
title: Read()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přečte jeden znak ze vstupního proudu.
type: docs
weight: 66
url: /cs/system.io/binaryreader/read/
---
## BinaryReader::Read() metoda

Přečte jeden znak ze vstupního proudu.

```cpp
virtual int System::IO::BinaryReader::Read()
```

### Návratová hodnota

Přečtený znak kódovaný v kódování UTF-16; pokud je přečtený znak v kódování UTF-16 reprezentován dvěma kóda, vrátí se jen vyšší surrogate.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) metoda

Přečte zadaný počet bajtů ze vstupního proudu a zapíše je do zadaného pole bajtů.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého se zapíšou přečtené bajty |
| index | int | Nulový index v **buffer**, odkud začít zápis |
| count | int | Počet bajtů k přečtení |

### Návratová hodnota

Počet přečtených bajtů

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) metoda

Přečte zadaný počet znaků ze vstupního proudu, převede je do kódování UTF-16 a zapíše výsledné znaky UTF-16 do zadaného pole znaků začínající na zadané pozici.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Pole znaků UTF-16, do kterého se zapíšou znaky přečtené ze vstupního proudu |
| index | int | Nulový index v **buffer**, odkud začít zápis |
| count | int | Počet znaků k přečtení ze streamu |

### Návratová hodnota

Počet znaků přečtených ze vstupního proudu

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [BinaryReader](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)