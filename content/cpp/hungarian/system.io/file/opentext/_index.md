---
title: OpenText()
second_title: Aspose.Slides C++ API referencia
description: Megnyitja a megadott létező fájlt szöveg olvasásához UTF-8 kódolással, megosztás nélkül.
type: docs
weight: 261
url: /hu/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) metódus


Megnyitja a megadott létező fájlt szöveg olvasásához UTF-8 kódolással, megosztás nélkül.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | A megnyitandó fájl elérési útja |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A használandó karakterkódolás |

### Visszatérési érték

Megosztott mutató egy [StreamWriter](../../streamwriter/) objektumra, amely a megnyitott fájlhoz kapcsolódik

## Lásd még

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Osztály [String](../../../system/string/)
* Osztály [File](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)