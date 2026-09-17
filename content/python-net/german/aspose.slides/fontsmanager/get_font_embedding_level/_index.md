---
title: get_font_embedding_level method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Bestimmt die Einbettungsstufe einer Schriftart aus dem angegebenen Byte-Array und dem Schriftartnamen.

### Rückgabewert

Die Einbettungsstufe der angegebenen Schriftart.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_bytes | **bytes** | Das Byte-Array, das die Schriftartdaten enthält. |
| font_name | **str** | Der Name der Schriftart. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wird ausgelöst, wenn `font_bytes` None ist. |



### Siehe auch
* Aufzählung [`EmbeddingLevel`](/slides/python-net/de/aspose.slides/embeddinglevel)
* Klasse [`FontsManager`](/slides/python-net/de/aspose.slides/fontsmanager)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)