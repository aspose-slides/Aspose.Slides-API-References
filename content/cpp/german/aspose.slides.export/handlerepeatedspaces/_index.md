---
title: HandleRepeatedSpaces
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie wiederholte reguläre Leerzeichenzeichen beim Markdown-Export behandelt werden sollen.
type: docs
weight: 937
url: /de/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces Aufzählung

Gibt an, wie wiederholte normale Leerzeichenzeichen beim Markdown-Export behandelt werden sollen.

```cpp
enum class HandleRepeatedSpaces
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Alle Leerzeichen werden als normale Leerzeichenzeichen unverändert beibehalten. Es wird keine Transformation angewendet, und mehrere aufeinanderfolgende Leerzeichen werden unverändert exportiert. |
| AlternateSpacesToNbsp | 1 | Wandelt Sequenzen von zwei oder mehr aufeinanderfolgenden normalen Leerzeichen durch abwechselndes Verwenden von normalen Leerzeichen und nicht-brechenden Leerzeichen-Entitäten (**&nbsp;**) um. Das erste Leerzeichen wird immer als normales Leerzeichen beibehalten. |
| MultipleSpacesToNbsp | 2 | Wandelt Sequenzen von zwei oder mehr aufeinanderfolgenden normalen Leerzeichen, indem das erste Leerzeichen als normales Leerzeichen beibehalten und alle nachfolgenden Leerzeichen durch nicht-brechende Leerzeichen-Entitäten (**&nbsp;**) ersetzt werden. |

## Siehe auch

* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)