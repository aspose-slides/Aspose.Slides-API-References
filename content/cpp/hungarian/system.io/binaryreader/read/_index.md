---
title: Read()
second_title: Aspose.Slides C++-hoz API referencia
description: Egyetlen karaktert olvas be a bemeneti adatfolyamból.
type: docs
weight: 66
url: /hu/system.io/binaryreader/read/
---
## BinaryReader::Read() metódus

Egyetlen karaktert olvas be a bemeneti adatfolyamból.

```cpp
virtual int System::IO::BinaryReader::Read()
```

### Visszatérési érték

A karakter UTF-16 kódolással olvasott; ha a karakter két kódpontot használ UTF-16-ban, akkor csak a magas szurrogát adja vissza.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) metódus

A megadott számú bájtot olvassa be a bemeneti adatfolyamból, és a megadott bájt tömbbe írja.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, amelybe az olvasott bájtokat írja |
| index | int | A **buffer**-ben a 0-alapú pozíció, ahol a írás kezdődik |
| count | int | Az olvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) metódus

A megadott számú karaktert olvassa be a bemeneti adatfolyamból, UTF-16 kódolásra alakítja, és az eredményül kapott UTF-16 karaktereket a megadott karakter tömbbe írja a megadott pozíciónál kezdve.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Az UTF-16 karakter tömb, amelybe a bemeneti adatfolyamból olvasott karaktereket írja |
| index | int | A **buffer**-ben a 0-alapú index, ahol a írás kezdődik |
| count | int | Az adatfolyamból olvasandó karakterek száma |

### Visszatérési érték

A bemeneti adatfolyamból beolvasott karakterek száma

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [BinaryReader](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)