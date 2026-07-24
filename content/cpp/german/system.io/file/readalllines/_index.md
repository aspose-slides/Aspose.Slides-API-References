---
title: ReadAllLines()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest den Inhalt der angegebenen Textdatei zeilenweise in ein Array von Zeichenketten ein, wobei die angegebene Zeichencodierung verwendet wird.
type: docs
weight: 300
url: /de/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) Methode

Liest den Inhalt der angegebenen Textdatei zeilenweise in ein Array von Zeichenketten ein, wobei die angegebene Zeichencodierung verwendet wird.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der zu lesenden Datei |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Zeichencodierung |

### Rückgabewert

Ein Zeichenketten-Array, dessen jedes Element eine einzelne Zeile aus der angegebenen Datei darstellt.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)