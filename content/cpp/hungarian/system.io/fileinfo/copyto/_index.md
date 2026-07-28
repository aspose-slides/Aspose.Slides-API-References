---
title: CopyTo()
second_title: Aspose.Slides C++ API referencia
description: Átmásolja a jelenlegi objektum által képviselt fájlt a megadott helyre. Ha a célfájl már létezik, a másolás sikertelen.
type: docs
weight: 105
url: /hu/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) metódus

A jelenlegi objektum által képviselt fájlt a megadott helyre másolja. Ha a célfájl már létezik, a másolás sikertelen.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | A célfájl neve |

### Visszatérési érték

Egy [FileInfo](../) objektum, amely a másolatot képviseli

## FileInfo::CopyTo(const String\&, bool) metódus

A jelenlegi objektum által képviselt fájlt a megadott helyre másolja. Egy paraméter határozza meg, hogy a létező célfájlt felül kell-e írni.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | A célfájl neve |
| overwrite | **bool** | Igaz, ha a létező célfájlt felül kell írni, hamis, ha a másolásnak sikertelennek kell lennie, ha a célfájl már létezik |

### Visszatérési érték

Egy [FileInfo](../) objektum, amely a másolatot képviseli

## Lásd még

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Osztály [String](../../../system/string/)
* Osztály [FileInfo](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)