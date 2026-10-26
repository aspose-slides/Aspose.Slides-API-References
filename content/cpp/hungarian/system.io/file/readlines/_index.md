---
title: ReadLines()
second_title: Aspose.Slides for C++ API referencia
description: Beolvassa a megadott szövegfájl tartalmát soronként a megadott karakterkódolás használatával, és visszaad egy felsorolható karakterlánc-gyűjteményt, amelynek minden eleme a fájl egyetlen sorát reprezentálja.
type: docs
weight: 326
url: /hu/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) metódus

Beolvassa a megadott szövegfájl tartalmát soronként a megadott karakterkódolás használatával, és visszaad egy felsorolható karakterlánc-gyűjteményt, amelynek minden eleme a fájl egyetlen sorát reprezentálja.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A beolvasandó fájl elérési útja |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó karakterkódolás |

### Visszatérési érték

A megadott fájl tartalmát reprezentáló felsorolható karakterlánc-gyűjtemény

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Osztály [String](../../../system/string/)
* Osztály [File](../)
* Névtér [System::IO](../../)
* Library [Aspose.Slides](../../../)