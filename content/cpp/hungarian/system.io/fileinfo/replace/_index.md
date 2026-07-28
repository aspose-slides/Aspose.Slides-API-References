---
title: Replace()
second_title: Aspose.Slides C++ API referenciája
description: Lecseréli egy megadott célfájl tartalmát a jelenlegi FileInfo objektum által képviselt fájlra, és biztonsági mentést készít a felcserélt fájlról.
type: docs
weight: 131
url: /hu/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) metódus


A megadott célfájl tartalmát a jelenlegi [FileInfo](../) objektum által képviselt fájlra cseréli, és biztonsági mentést készít a felcserélt fájlról.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | A fájl neve, amelyet cserélni kell |
| destinationBackupFileName | const [String](../../../system/string/)\& | A mentési fájl neve |

### Visszatérési érték

Egy FileInfor objektum, amely a **destinationFileName** által hivatkozott fájlt reprezentálja

## FileInfo::Replace(const String\&, const String\&, bool) metódus


A megadott célfájl tartalmát a jelenlegi [FileInfo](../) objektum által képviselt fájlra cseréli, és biztonsági mentést készít a felcserélt fájlról.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | A fájl neve, amelyet cserélni kell |
| destinationBackupFileName | const [String](../../../system/string/)\& | A mentési fájl neve |
| ignoreMetadataErrors | **bool** | Megadja, hogy a helyettesített fájlból a cserélő fájlba történő egyesítési hibákat figyelmen kívül kell-e hagyni (true) vagy sem (false) |

### Visszatérési érték

Egy FileInfor objektum, amely a **destinationFileName** által hivatkozott fájlt reprezentálja

## Lásd még

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Osztály [String](../../../system/string/)
* Osztály [FileInfo](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)