---
title: AppendAllText()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt die angegebene Zeichenkette mit der angegebenen Kodierung an die angegebene Datei an.
type: docs
weight: 14
url: /de/system.io/file/appendalltext/
---
## File::AppendAllText(const String\&, const String\&, const EncodingPtr\&) Methode

Fügt die angegebene Zeichenkette an die angegebene Datei mit der angegebenen Kodierung an.

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der Datei, an die die Zeichenkette angehängt wird |
| contents | const [String](../../../system/string/)\& | Die Zeichenkette, die in die Datei geschrieben werden soll |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Zeichenkodierung |

## Siehe auch

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)