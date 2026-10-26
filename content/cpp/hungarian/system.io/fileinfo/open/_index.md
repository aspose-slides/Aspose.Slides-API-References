---
title: Open()
second_title: Aspose.Slides for C++ API Referencia
description: Megnyitja a jelenlegi objektum által képviselt fájlt a megadott módban olvasásra és írásra, megosztás nélkül.
type: docs
weight: 183
url: /hu/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) metódus

Megnyitja a jelenlegi objektum által képviselt fájlt a megadott módban olvasásra és írásra, megosztás nélkül.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Megadja a módot, amelyben a fájlt megnyitja |

### Visszatérési érték

Egy [FileStream](../../filestream/) objektum, amely a jelenlegi objektum által képviselt fájlhoz kapcsolódik

## FileInfo::Open(FileMode, FileAccess) metódus

Megnyitja a jelenlegi objektum által képviselt fájlt a megadott módban, a megadott hozzáférési típussal, megosztás nélkül.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Megadja a módot, amelyben a fájlt megnyitja |
| access | [FileAccess](../../fileaccess/) | A kért hozzáférési típus |

### Visszatérési érték

Egy [FileStream](../../filestream/) objektum, amely a jelenlegi objektum által képviselt fájlhoz kapcsolódik

## FileInfo::Open(FileMode, FileAccess, FileShare) metódus

Megnyitja a jelenlegi objektum által képviselt fájlt a megadott módban, a megadott hozzáférési típussal és a megosztási beállítással.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Megadja a módot, amelyben a fájlt megnyitja |
| access | [FileAccess](../../fileaccess/) | A kért hozzáférési típus |
| share | [FileShare](../../fileshare/) | Az a hozzáférés típusa, amelyet más [FileStream](../../filestream/) objektumok a megnyitott fájlhoz használnak |

### Visszatérési érték

Egy [FileStream](../../filestream/) objektum, amely a jelenlegi objektum által képviselt fájlhoz kapcsolódik

## Lásd még

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Osztály [FileInfo](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)