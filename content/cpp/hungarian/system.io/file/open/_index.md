---
title: Open()
second_title: Aspose.Slides C++ API referencia
description: Megnyitja a megadott fájlt a megadott módban olvasáshoz és íráshoz, megosztás nélkül.
type: docs
weight: 235
url: /hu/system.io/file/open/
---
## File::Open(const String\&, FileMode) metódus


Megnyitja a megadott fájlt a megadott módban olvasáshoz és íráshoz, megosztás nélkül.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A megnyitandó fájl elérési útja |
| mode | [FileMode](../../filemode/) | Megadja a módot, amellyel a fájlt meg kell nyitni |

### Visszatérési érték

Egy [FileStream](../../filestream/) objektum, amely a megnyitott fájlhoz kapcsolódik

## File::Open(const String\&, FileMode, FileAccess, FileShare) metódus


Megnyitja a megadott fájlt a megadott módban, a megadott hozzáférési típussal és megosztási beállítással.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A megnyitandó fájl elérési útja |
| mode | [FileMode](../../filemode/) | Megadja a módot, amellyel a fájlt meg kell nyitni |
| access | [FileAccess](../../fileaccess/) | A kért hozzáférési típus |
| share | [FileShare](../../fileshare/) | Az a hozzáféréstípus, amelyet a többi [FileStream](../../filestream/) objektum a megnyitott fájlhoz kap |

### Visszatérési érték

Egy [FileStream](../../filestream/) objektum, amely a megnyitott fájlhoz kapcsolódik

## Lásd még

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Osztály [String](../../../system/string/)
* Osztály [File](../)
* Névtere [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)