---
title: Replace()
second_title: Aspose.Slides C++ API Referencia
description: Lecseréli egy fájl tartalmát egy másikra, és biztonsági mentést készít a helyettesített fájlról.
type: docs
weight: 339
url: /hu/system.io/file/replace/
---
## File::Replace(const String&, const String&, const String&, bool) metódus

A fájl tartalmát egy másik fájllal cseréli, és biztonsági mentést készít a helyettesített fájlról.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | A fájl neve, amellyel helyettesíteni kell |
| destinationFileName | const [String](../../../system/string/)\& | A fájl neve, amelyet helyettesíteni kell |
| destinationBackupFileName | const [String](../../../system/string/)\& | A biztonsági mentés fájl neve |
| ignoreMetadataErrors | **bool** | Megadja, hogy a helyettesített fájlból a csere fájlba történő egyesítési hibákat figyelmen kívül kell-e hagyni (true) vagy nem (false) |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [File](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)