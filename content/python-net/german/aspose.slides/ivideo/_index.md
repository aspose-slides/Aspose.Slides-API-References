---
title: IVideo class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ivideo/
---
## IVideo Klasse

Stellt ein in eine Präsentation eingebettetes Video dar.

Der IVideo-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`content_type`](/slides/python-net/de/aspose.slides/ivideo/content_type/) | Gibt den MIME-Typ eines Videos zurück, codiert in [`IVideo.binary_data`](/slides/python-net/de/aspose.slides/ivideo/binary_data).<br/>            Nur lesbar **str**. |
| [`binary_data`](/slides/python-net/de/aspose.slides/ivideo/binary_data/) | Gibt die Kopie der Audiodaten zurück. Bei großer Datenmenge sollte die <br/>            [`IVideo.get_stream`](/slides/python-net/de/aspose.slides/ivideo/get_stream)-Methode verwendet werden, um das unnötige Laden der Videodaten in den Speicher zu verhindern <br/>            oder sogar OutOfMemoryException.<br/>            Nur lesbar **int**[]. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/de/aspose.slides/ivideo/get_stream/#) | Gibt einen Stream zum Lesen zurück.<br/>            Verwenden Sie 'using' oder schließen Sie den Stream nach der Verwendung. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)