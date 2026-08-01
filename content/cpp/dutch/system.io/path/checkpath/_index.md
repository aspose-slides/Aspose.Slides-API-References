---
title: CheckPath()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of het opgegeven pad geldig is door te controleren of het ongeldige tekens bevat. Er wordt een uitzondering gegooid als het pad ongeldige tekens bevat.
type: docs
weight: 209
url: /nl/system.io/path/checkpath/
---
## Path::CheckPath(const String&, const String&, bool) methode


Bepaalt of het opgegeven pad geldig is door te controleren of het ongeldige tekens bevat. Er wordt een uitzondering gegooid als het pad ongeldige tekens bevat.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Het pad om te controleren |
| msg | const [String](../../../system/string/)\& | Het bericht dat wordt doorgegeven aan de constructor van het exceptie-object |
| allow_empty | **bool** | Specificeert of een lege of null-string moet worden beschouwd als een geldig pad (true) of niet (false); als deze parameter false is en **path** leeg is, wordt een ArgumentException gegooid; als deze parameter false is en **path** null is, wordt een ArgumentNullException gegooid |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [Path](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)