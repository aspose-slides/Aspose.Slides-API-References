---
title: ReadAllLines()
second_title: Aspose.Slides C++ API referencia
description: A megadott szöveges fájl tartalmát soronként egy karakterlánc tömbbe olvassa a megadott karakterkódolás használatával.
type: docs
weight: 300
url: /hu/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) metódus


A megadott szöveges fájl tartalmát soronként egy karakterlánc tömbbe olvassa a megadott karakterkódolás használatával.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A fájl elérési útja, amelyet olvasni kell |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó karakterkódolás |

### Visszatérési érték

Egy string tömb, amelynek minden eleme egy adott fájl egy sorát képviseli

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Osztály [String](../../../system/string/)
* Osztály [File](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)