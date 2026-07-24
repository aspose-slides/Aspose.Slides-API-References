---
title: ReadLines()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest den Inhalt der angegebenen Textdatei zeilenweise unter Verwendung der angegebenen Zeichenkodierung und gibt eine auflistbare Sammlung von Zeichenketten zurück, von denen jede eine einzelne Zeile des Dateiinhalts darstellt.
type: docs
weight: 326
url: /de/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) Methode

Liest den Inhalt der angegebenen Textdatei zeilenweise unter Verwendung der angegebenen Zeichenkodierung und gibt eine auflistbare Sammlung von Zeichenketten zurück, von denen jede eine einzelne Zeile des Dateiinhalts darstellt.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der Datei, die gelesen werden soll |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Zeichenkodierung |

### Rückgabewert

Eine auflistbare Sammlung von Zeichenketten, die den Inhalt der angegebenen Datei darstellen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)