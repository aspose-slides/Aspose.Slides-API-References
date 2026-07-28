---
title: AppendText()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy StreamWriter objektumot, amely UTF-8 kódolással szöveget fűz hozzá a megadott fájlhoz. Ha a megadott fájl nem létezik, létrehozza.
type: docs
weight: 27
url: /hu/system.io/file/appendtext/
---
## File::AppendText(const String\&) metódus

Létrehoz egy [StreamWriter](../../streamwriter/) objektumot, amely UTF-8 kódolással szöveget fűz hozzá a megadott fájlhoz. Ha a megadott fájl nem létezik, létrehozzák.

```cpp
static StreamWriterPtr System::IO::File::AppendText(const String &path)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A megnyitandó vagy létrehozandó fájl útvonala |

### Visszatérési érték

Egy megosztott mutató a létrehozott [StreamWriter](../../streamwriter/) objektumra, amely a megadott fájlhoz kapcsolódik

## Lásd még

* Típusdefiníció [StreamWriterPtr](../../../system/streamwriterptr/)
* Osztály [String](../../../system/string/)
* Osztály [File](../)
* Névterület [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)