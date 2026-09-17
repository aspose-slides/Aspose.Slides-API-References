---
title: Audio class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/audio/
---
## Audio-Klasse

Stellt eine eingebettete Audiodatei dar.

Der Audio-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`content_type`](/slides/python-net/de/aspose.slides/audio/content_type/) | Gibt einen MIME-Typ einer Audiodatei zurück, kodiert in [`Audio.binary_data`](/slides/python-net/de/aspose.slides/audio/binary_data).<br/>            Nur lesbar **str**. |
| [`binary_data`](/slides/python-net/de/aspose.slides/audio/binary_data/) | Gibt eine Kopie der Audiodaten zurück. Bei großer Datenmenge sollte man <br/>            die Verwendung der [`Audio.get_stream`](/slides/python-net/de/aspose.slides/audio/get_stream)-Methode in Betracht ziehen, um das unnötige Laden der Audiodaten<br/>            in den Speicher oder sogar eine OutOfMemoryException zu vermeiden.<br/>            Nur lesbar **int**[]. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/de/aspose.slides/audio/get_stream/#) | Gibt einen Stream zum Lesen zurück.<br/>            Verwenden Sie 'using' oder schließen Sie den Stream nach der Verwendung. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)