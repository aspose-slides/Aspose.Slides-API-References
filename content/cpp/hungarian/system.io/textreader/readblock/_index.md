---
title: ReadBlock()
second_title: Aspose.Slides for C++ API Referencia
description: A megadott maximális számú karaktert olvassa a jelenlegi szövegolvasóból, és az adatokat egy bufferbe írja, a megadott indexnél kezdve.
type: docs
weight: 53
url: /hu/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) metódus


A megadott maximális számú karaktert olvassa a jelenlegi szövegolvasóból, és az adatokat egy bufferbe írja, a megadott indexnél kezdve.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Egy karakter buffer, amelybe az olvasott adatokat írja |
| index | int | 0-alapú index a **buffer**-ben, ahol a írás kezdődik |
| count | int | A karakterek maximális száma, amelyet olvasni kell |

### Visszatérési érték

A ténylegesen beolvasott karakterek száma

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [TextReader](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)