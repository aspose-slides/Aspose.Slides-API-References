---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController Klasse

Die Formatierungscontroller-Klasse zum Einbetten aller Präsentationsschriftarten im WOFF-Format.

Der Typ EmbedAllFontsHtmlController stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Erstellt eine neue Instanz |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Erstellt eine neue Instanz |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Wird aufgerufen, um den HTML-Dokument-Header zu schreiben. Wird einmal pro Präsentationskonvertierung aufgerufen. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Wird aufgerufen, um den HTML-Dokument-Footer zu schreiben. Wird einmal pro Präsentationskonvertierung aufgerufen. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Wird aufgerufen, um den HTML-Folien-Header zu schreiben. Wird für jede Folie einmal aufgerufen. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Wird aufgerufen, um den HTML-Folien-Footer zu schreiben. Wird für jede Folie einmal aufgerufen. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Wird vor dem Rendern einer Form aufgerufen. Wird für jede Form einmal aufgerufen. Wenn diese Funktion etwas in den Generator schreibt, wird die aktuelle Folien-Bildgenerierung beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über das vorherige gestartet. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Wird vor dem Rendern einer Form aufgerufen. Wird für jede Form einmal aufgerufen. Wenn diese Funktion etwas in den Generator schreibt, wird die aktuelle Folien-Bildgenerierung beendet, das hinzugefügte HTML-Fragment eingefügt und ein neues Bild über das vorherige gestartet. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Schreibt alle in [`Presentation`](/slides/python-net/de/aspose.slides/presentation) enthaltenen Schriftarten. |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/de/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Schreibt Daten als Base64 in das HTML-Dokument selbst |


### Siehe auch
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)