---
title: IAudio class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iaudio/
---
## IAudio Klasse

Stellt eine eingebettete Audiodatei dar.

Der IAudio-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`content_type`](/slides/python-net/de/aspose.slides/iaudio/content_type/) | Gibt einen MIME-Typ einer Audiodatei zurück, kodiert in [`IAudio.binary_data`](/slides/python-net/de/aspose.slides/iaudio/binary_data).<br/>            Nur lesbar **str**. |
| [`binary_data`](/slides/python-net/de/aspose.slides/iaudio/binary_data/) | Gibt eine Kopie der Audiodaten zurück. Bei großer Datenmenge sollte <br/>            die Verwendung der [`IAudio.get_stream`](/slides/python-net/de/aspose.slides/iaudio/get_stream)-Methode in Betracht gezogen werden, um das unnötige  Laden der Audiodaten<br/>            in den Speicher oder sogar eine OutOfMemoryException zu verhindern.<br/>            Nur lesbar **int**[]. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/de/aspose.slides/iaudio/get_stream/#) | Gibt Stream stream zum Lesen zurück.<br/>            Verwenden Sie 'using' oder schließen Sie den Stream nach der Verwendung. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)