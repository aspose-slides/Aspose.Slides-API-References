---
title: WriteAllText()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine neue Textdatei oder überschreibt die vorhandene und schreibt den Inhalt der angegebenen Zeichenfolge mit der angegebenen Kodierung in die Datei.
type: docs
weight: 469
url: /de/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) Methode


Erstellt eine neue Textdatei oder überschreibt die bestehende und schreibt den Inhalt der angegebenen Zeichenfolge mit der angegebenen Codierung in die Datei.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Die Datei, die erstellt oder überschrieben werden soll |
| contents | const [String](../../../system/string/)\& | Ein String-Array |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Zeichenkodierung |

## Siehe auch

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)