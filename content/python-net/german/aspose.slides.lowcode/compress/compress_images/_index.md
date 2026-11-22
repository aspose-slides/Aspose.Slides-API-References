---
title: compress_images method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Reduziert die Auflösung von Bildern in der Präsentation und entfernt deren beschnittenen Bereiche,
            ähnlich wie PowerPoint's „Compress Pictures“, das auf alle Bilder angewendet wird.
            Bilder auf Folien, Layout-Folien und Master-Folien werden verarbeitet, einschließlich Bilder in Gruppierungsformen
            und Bildfüllungen von Formen.


```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) | Die zu verarbeitende Präsentation. |
| resolution | [`PicturesCompression`](/slides/python-net/de/aspose.slides.export/picturescompression) | Zielauflösung relativ zur Größe, in der jedes Bild angezeigt wird.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/de/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) lässt Bilder unverändert. |

### Anmerkungen

Bilder, die bereits die Zielauflösung erreichen oder darunter liegen, bleiben unverändert; Bilder werden niemals hochskaliert.

Nicht verarbeitet: Folienhintergründe, Tabellenzellenfüllungen, Diagramme, SmartArt, GIF-Bilder (zur Erhaltung der Animation),
            SVG- und Metadatei-Bilder (EMF/WMF).

Beschnittene Bereiche werden dauerhaft entfernt und können in PowerPoint nicht wiederhergestellt werden.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` ist `None`. |



### Siehe auch
* Klasse [`Compress`](/slides/python-net/de/aspose.slides.lowcode/compress)
* Klasse [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)
* Aufzählung [`PicturesCompression`](/slides/python-net/de/aspose.slides.export/picturescompression)
* Modul [`aspose.slides.lowcode`](/slides/python-net/de/aspose.slides.lowcode)
* Bibliothek [`Aspose.Slides`](/slides/python-net)