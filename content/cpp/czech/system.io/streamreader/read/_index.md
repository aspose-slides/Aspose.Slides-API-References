---
title: Read()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Načte jeden znak ze streamu.
type: docs
weight: 40
url: /cs/system.io/streamreader/read/
---
## StreamReader::Read() metoda


Načte jeden znak ze streamu.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### Návratová hodnota

Vrátí znak kódovaný v UTF-16; pokud je načtený znak reprezentován dvěma kódy v kódování UTF-16, vrátí se pouze vyšší surrogát.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) metoda


Načte z proudu zadaný počet znaků, převede je do kódování UTF-16 a zapíše výsledné znaky UTF-16 do zadaného pole znaků počínaje na zadané pozici.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Pole znaků UTF-16, do kterého se zapisují znaky načtené z proudu |
| index | int | Nulový index v **buffer**, od kterého se začne zapisovat |
| count | int | Počet znaků, které se mají načíst z proudu |

### Návratová hodnota

Počet znaků načtených z proudu

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [StreamReader](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)