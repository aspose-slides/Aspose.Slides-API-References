---
title: Read()
second_title: Aspose.Slides for C++ API Referencia
description: Egyetlen karaktert olvas be a folyamából.
type: docs
weight: 40
url: /hu/system.io/textreader/read/
---
## TextReader::Read() metódus

Egyetlen karaktert olvas be a streame-ből.

```cpp
virtual int System::IO::TextReader::Read()
```

### Visszatérési érték

Olvasott karakter UTF-16 kódolással; ha a karakter két kódpontot foglal el az UTF-16 kódolásban, akkor csak a magas szurrogát tér vissza.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) metódus

A megadott számú karaktert olvassa be a streame-ból, és a megadott karaktertömbbe írja a megadott pozíciótól kezdve.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Az UTF-16 karaktertömb, amelybe a streame-ból beolvasott karaktereket írja |
| index | int | A **buffer**-ben a 0-alapú index, ahol a írás megkezdődik |
| count | int | A karakterek száma, amelyet a streame-ból be kell olvasni |

### Visszatérési érték

A streame-ból beolvasott karakterek száma

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [TextReader](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)