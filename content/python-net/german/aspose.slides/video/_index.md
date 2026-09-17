---
title: Video class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/video/
---
## Video-Klasse

Stellt ein Bild dar, das in eine Präsentation eingebettet ist.

Der Video-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`content_type`](/slides/python-net/de/aspose.slides/video/content_type/) | Gibt einen MIME-Typ eines Videos zurück, codiert in [`Video.binary_data`](/slides/python-net/de/aspose.slides/video/binary_data).<br/>            Nur lesend **str**. |
| [`binary_data`](/slides/python-net/de/aspose.slides/video/binary_data/) | Gibt eine Kopie der Audiodaten zurück. Bei großer Datenmenge sollte die Methode <br/>            [`Video.get_stream`](/slides/python-net/de/aspose.slides/video/get_stream) verwendet werden, um das unnötige Laden der Videodaten in den Speicher <br/>            oder sogar eine OutOfMemoryException zu vermeiden.<br/>            Nur lesend **int**[]. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/de/aspose.slides/video/get_stream/#) | Gibt einen Stream zum Lesen zurück.<br/>            Verwenden Sie 'using' oder schließen Sie den Stream nach der Verwendung. |

### Siehe auch
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)