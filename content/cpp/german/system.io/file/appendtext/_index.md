---
title: AppendText()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt ein StreamWriter-Objekt, das Text an die angegebene Datei anhängt und UTF-8-Kodierung verwendet. Wenn die angegebene Datei nicht existiert, wird sie erstellt.
type: docs
weight: 27
url: /de/system.io/file/appendtext/
---
## File::AppendText(const String\&) Methode


Erstellt ein [StreamWriter](../../streamwriter/) Objekt, das Text an die angegebene Datei anhängt und UTF-8-Kodierung verwendet. Wenn die angegebene Datei nicht existiert, wird sie erstellt.

```cpp
static StreamWriterPtr System::IO::File::AppendText(const String &path)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der zu öffnenden oder zu erstellenden Datei |

### Rückgabewert

Ein shared pointer auf das erstellte [StreamWriter](../../streamwriter/)-Objekt, das mit der angegebenen Datei verknüpft ist

## Siehe auch

* Typedef [StreamWriterPtr](../../../system/streamwriterptr/)
* Klasse [String](../../../system/string/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)