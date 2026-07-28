---
title: Read()
second_title: Aspose.Slides C++ API Referencia
description: Egyetlen karaktert olvas be az adatfolyamból.
type: docs
weight: 40
url: /hu/system.io/streamreader/read/
---
## StreamReader::Read() metódus


Egyetlen karaktert olvas be az adatfolyamból.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### Visszatérési érték

A beolvasott karakter UTF-16 kódolású; ha a karakter két kódponttal van ábrázolva az UTF-16 kódolásban, akkor csak a magas szurrogát adja vissza.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) metódus


A megadott számú karaktert olvassa be a folyam-ból, UTF-16 kódolásra konvertálja, és az eredményül kapott UTF-16 karaktereket a megadott karaktertömbbe írja a megadott pozíciótól kezdve.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Az UTF-16 karaktertömb, amelybe a folyam-ból beolvasott karaktereket írja |
| index | int | A **buffer** 0-alapú indexe, ahol a írás kezdődik |
| count | int | A folyam-ból beolvasandó karakterek száma |

### Visszatérési érték

A folyam-ból beolvasott karakterek száma

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [StreamReader](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)