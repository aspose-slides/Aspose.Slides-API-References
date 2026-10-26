---
title: PeekChar()
second_title: Aspose.Slides C++ API referencia
description: Egyetlen karaktert olvas be a bemeneti adatfolyamból anélkül, hogy megváltoztatná a folyam olvasási kurzorát.
type: docs
weight: 53
url: /hu/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() metódus

Egyetlen karaktert olvas be a bemeneti adatfolyamból anélkül, hogy megváltoztatná a folyam olvasási kurzorát.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```

### Visszatérési érték

A UTF-16 kódolással kódolt karakter olvasása; ha a beolvasott karakter a UTF-16 kódolásban két kódpontból áll, akkor csak a magas szurrogát visszatér; ha nem olvasott karaktert, -1-et ad vissza

## Lásd még

* Osztály [BinaryReader](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)