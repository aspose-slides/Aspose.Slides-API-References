---
title: LinkEmbedDecision
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, wie das Objekt beim Speichern verarbeitet wird.
type: docs
weight: 911
url: /de/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enum

Bestimmt, wie das Objekt beim Speichern verarbeitet wird.

```cpp
enum class LinkEmbedDecision
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Link | 0 | Das Objekt wird extern gespeichert und per URL referenziert |
| Embed | 1 | Das Objekt sollte, wenn möglich, in die erzeugte Datei eingebettet werden. Wenn das Einbetten unmöglich ist, wird GetUrl aufgerufen und je nach Ergebnis wird das Objekt per URL referenziert oder ignoriert. |
| Ignore | 2 | Das Objekt wird ignoriert. |

## Siehe auch

* Namespace [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)