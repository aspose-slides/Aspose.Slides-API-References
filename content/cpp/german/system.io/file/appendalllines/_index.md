---
title: AppendAllLines()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt Zeichenketten aus der angegebenen Sammlung von Zeichenketten in die angegebene Datei ein, indem jede Zeichenkette in einer neuen Zeile geschrieben wird und die angegebene Codierung verwendet wird. Falls die angegebene Datei nicht existiert, wird sie erstellt. Die Datei wird nach dem Schreiben aller Zeichenketten geschlossen.
type: docs
weight: 1
url: /de/system.io/file/appendalllines/
---
## File::AppendAllLines(const String&, const SharedPtr<Collections::Generic::IEnumerable<String>>&, const EncodingPtr&) Methode

Fügt Zeichenketten aus der angegebenen Sammlung von Zeichenketten in die angegebene Datei ein, indem jede Zeichenkette in einer neuen Zeile geschrieben wird und die angegebene Codierung verwendet wird. Falls die angegebene Datei nicht existiert, wird sie erstellt. Die Datei wird nach dem Schreiben aller Zeichenketten geschlossen.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der Pfad der Datei, an die die Zeichenketten angehängt werden |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Die Zeichenketten, die in die Datei geschrieben werden sollen |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Die zu verwendende Zeichenkodierung |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [String](../../../system/string/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [File](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)