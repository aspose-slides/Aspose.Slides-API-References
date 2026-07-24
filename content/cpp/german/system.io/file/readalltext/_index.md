---
title: ReadAllText()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest den Inhalt der angegebenen Textdatei in ein einzelnes String-Objekt unter Verwendung der angegebenen Zeichenkodierung.
type: docs
weight: 313
url: /de/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) Methode

Liest den Inhalt der angegebenen Textdatei in ein einzelnes [String](../../../system/string/)-Objekt unter Verwendung der angegebenen Zeichenkodierung.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der zu lesenden Datei |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Zeichenkodierung |

### Rückgabewert

Ein String, der den Inhalt der angegebenen Datei enthält

## Siehe auch

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)