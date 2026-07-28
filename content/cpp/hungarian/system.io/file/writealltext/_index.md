---
title: WriteAllText()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy új szöveges fájlt, vagy felülírja a meglévőt, és a megadott kódolás használatával beírja a megadott karakterlánc tartalmát.
type: docs
weight: 469
url: /hu/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) metódus


Létrehoz egy új szöveges fájlt, vagy felülírja a meglévőt, és a megadott kódolás használatával beírja a megadott string tartalmát.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A fájl, amelyet létrehozni vagy felülírni kell |
| contents | const [String](../../../system/string/)\& | Egy string tömb |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó karakterkódolás |

## Lásd még

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Osztály [String](../../../system/string/)
* Osztály [File](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)