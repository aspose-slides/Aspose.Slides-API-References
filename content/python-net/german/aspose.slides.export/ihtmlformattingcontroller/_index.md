---
title: IHtmlFormattingController class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController Klasse

Steuert die Erstellung einer html-Datei.

Der Typ IHtmlFormattingController stellt die folgenden Mitglieder bereit:

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/de/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Wird aufgerufen, um den Header des html-Dokuments zu schreiben. Wird einmal pro Präsentationskonvertierung aufgerufen. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/de/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Wird aufgerufen, um den Footer des html-Dokuments zu schreiben. Wird einmal pro Präsentationskonvertierung aufgerufen. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/de/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Wird aufgerufen, um den Header der html-Folie zu schreiben. Wird einmal für jede Folie aufgerufen. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/de/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Wird aufgerufen, um den Footer der html-Folie zu schreiben. Wird einmal für jede Folie aufgerufen. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/de/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Wird vor dem Rendern einer Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas an den Generator schreibt, wird die aktuelle Folienbildgenerierung beendet, das hinzugefügte html-Fragment eingefügt und ein neues Bild oben auf dem vorherigen gestartet. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/de/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Wird vor dem Rendern einer Form aufgerufen. Wird einmal pro Form aufgerufen. Wenn diese Funktion etwas an den Generator schreibt, wird die aktuelle Folienbildgenerierung beendet, das hinzugefügte html-Fragment eingefügt und ein neues Bild oben auf dem vorherigen gestartet. |

### Siehe auch
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)