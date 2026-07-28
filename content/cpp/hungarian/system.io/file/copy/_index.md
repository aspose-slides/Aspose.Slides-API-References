---
title: Copy()
second_title: Aspose.Slides C++ API hivatkozás
description: Másolja a megadott fájlt a megadott helyre. Ha a célfájl már létezik, egy paraméter határozza meg, hogy felül legyen-e írva.
type: docs
weight: 40
url: /hu/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) metódus

Másolja a megadott fájlt a megadott helyre. Ha a célfájl már létezik, egy paraméter határozza meg, hogy felül legyen-e írva.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | A másolandó fájl elérési útja |
| destFileName | const [String](../../../system/string/)\& | Az új hely elérési útja a másolandó fájlnak |
| overwrite | **bool** | True, ha a meglévő célfájlt felül kell írni; false, ha a másolásnak sikertelennek kell lennie, ha a célfájl már létezik |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [File](../)
* Névterület [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)