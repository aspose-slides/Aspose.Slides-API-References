---
title: Read()
second_title: Aspose.Slides C++ API referenciához
description: Egyetlen karaktert olvas be a folyamatról.
type: docs
weight: 40
url: /hu/system.io/stringreader/read/
---
## StringReader::Read() metódus


Egyetlen karaktert olvas be a folyamatról.

```cpp
virtual int System::IO::StringReader::Read() override
```


### Visszatérési érték

Beolvasott karakter vagy -1, ha nem olvasott karakter

## StringReader::Read(ArrayPtr\<char_t\>, int, int) metódus


Beolvasza a megadott számú karaktert a folyamatról a megadott karaktertömbbe a megadott pozíciótól kezdve.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | A karaktertömb, amelybe a folyamatról beolvasott karaktereket írja |
| index | int | A 0-alapú index a **buffer**-ben, ahol a írás elkezdődik |
| count | int | A folyamatról beolvasandó karakterek száma |

### Visszatérési érték

A folyamatról beolvasott karakterek száma

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [StringReader](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)