---
title: Compress class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.lowcode/compress/
---
## Compress Klasse

Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, [`Presentation`](/slides/python-net/de/aspose.slides/presentation) zu komprimieren.

Der Typ Compress stellt die folgenden Mitglieder bereit:

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/de/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Reduziert die Größe einer Präsentation, indem alle verfügbaren Komprimierungsschritte angewendet werden:<br/>            <br/>* Entfernt nicht verwendete Master-Folien **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Entfernt nicht verwendete Layout-Folien **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Beibehält nur die tatsächlich in eingebetteten Schriftarten verwendeten Glyphen **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Reduziert die Bildauflösung auf 150 DPI und löscht beschnittene Bildbereiche **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/de/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Komprimiert das [`Presentation`](/slides/python-net/de/aspose.slides/presentation) durch Entfernen nicht verwendeter Master-Folien. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/de/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Komprimiert das [`Presentation`](/slides/python-net/de/aspose.slides/presentation) durch Entfernen nicht verwendeter Layout-Folien. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/de/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Komprimiert das [`Presentation`](/slides/python-net/de/aspose.slides/presentation) durch Entfernen nicht verwendeter Zeichen aus eingebetteten Schriftarten. |
| [`compress_images(presentation, resolution)`](/slides/python-net/de/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Reduziert die Auflösung von Bildern in der Präsentation und löscht deren beschnittene Bereiche,<br/>            ähnlich wie PowerPoints "Compress Pictures" auf alle Bilder angewendet.<br/>            Bilder auf Folien, Layout-Folien und Master-Folien werden verarbeitet, einschließlich Bilder in Gruppenformen<br/>            und Bildfüllungen von Formen. |

### Siehe auch
* Klasse [`Presentation`](/slides/python-net/de/aspose.slides/presentation)
* Modul [`aspose.slides.lowcode`](/slides/python-net/de/aspose.slides.lowcode)
* Bibliothek [`Aspose.Slides`](/slides/python-net)