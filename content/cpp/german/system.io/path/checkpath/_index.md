---
title: CheckPath()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob der angegebene Pfad gültig ist, indem geprüft wird, ob er ungültige Zeichen enthält. Es wird eine Ausnahme ausgelöst, wenn der Pfad ungültige Zeichen enthält.
type: docs
weight: 209
url: /de/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) Methode

Bestimmt, ob der angegebene Pfad gültig ist, indem geprüft wird, ob er ungültige Zeichen enthält. Es wird eine Ausnahme ausgelöst, wenn der Pfad ungültige Zeichen enthält.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Der zu prüfende Pfad |
| msg | const [String](../../../system/string/)\& | Die Nachricht, die an den Konstruktor des Ausnahmesobjekts übergeben wird |
| allow_empty | **bool** | Gibt an, ob ein leerer oder null-String als korrekter Pfad betrachtet werden soll (true) oder nicht (false); ist dieser Parameter false und ist **path** leer, wird eine ArgumentException ausgelöst; ist dieser Parameter false und ist **path** null, wird eine ArgumentNullException ausgelöst |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [Path](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)