---
title: OpenText()
second_title: Aspose.Slides für C++ API-Referenz
description: Öffnet die angegebene vorhandene Datei zum Lesen von Text mit UTF-8-Kodierung ohne Freigabe.
type: docs
weight: 261
url: /de/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) Methode

Öffnet die angegebene vorhandene Datei zum Lesen von Text mit UTF-8-Kodierung ohne Freigabe.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der zu öffnenden Datei |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Zeichenkodierung |

### Rückgabewert

Ein Shared Pointer auf ein [StreamWriter](../../streamwriter/)-Objekt, das mit der geöffneten Datei verknüpft ist

## Siehe auch

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)