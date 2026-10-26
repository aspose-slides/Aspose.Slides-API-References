---
title: PeekChar()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přečte jeden znak ze vstupního proudu, aniž by změnil čtecí kurzor proudu.
type: docs
weight: 53
url: /cs/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() metoda


Přečte jediný znak ze vstupního proudu, aniž by změnil čtecí kurzor proudu.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```


### Návratová hodnota

Přečtený znak je kódován v kódování UTF-16; pokud je přečtený znak v kódování UTF-16 reprezentován dvěma kódy, je vrácen pouze vyšší surrogate; pokud nebyl přečten žádný znak, je vráceno -1

## Viz také

* Třída [BinaryReader](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)