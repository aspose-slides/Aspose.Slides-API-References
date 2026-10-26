---
title: SwfOptions class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/swfoptions/
---
## SwfOptions Klasse

Stellt Optionen bereit, die steuern, wie eine Präsentation im Swf-Format gespeichert wird.

**Inheritance:**[`SwfOptions`](/slides/python-net/de/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)

Der SwfOptions-Typ stellt die folgenden Member bereit:

## Konstruktoren

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/swfoptions/__init__/#) | Standardkonstruktor. |

## Eigenschaften

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/swfoptions/warning_callback/) | Ruft ein Objekt ab oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/swfoptions/progress_callback/) | Stellt ein Rückrufobjekt für Fortschrittsaktualisierungen beim Speichern in Prozent dar.<br/>            Siehe [`IProgressCallback`](/slides/python-net/de/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/swfoptions/default_regular_font/) | Ruft die Schriftart ab oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/swfoptions/gradient_style/) | Ruft den visuellen Stil des Farbverlaufs ab oder legt ihn fest.<br/>            Lesen/Schreiben [`GradientStyle`](/slides/python-net/de/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/swfoptions/skip_java_script_links/) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen.<br/>            Lesen/Schreiben **bool**. Der Standardwert ist **false**. |
| [`show_hidden_slides`](/slides/python-net/de/aspose.slides.export/swfoptions/show_hidden_slides/) | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht.<br/>            Standard ist `false`. |
| [`compressed`](/slides/python-net/de/aspose.slides.export/swfoptions/compressed/) | Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht.<br/>            Standard ist `true`. |
| [`viewer_included`](/slides/python-net/de/aspose.slides.export/swfoptions/viewer_included/) | Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentenbetrachter enthalten soll oder nicht.<br/>            Standard ist `true`. |
| [`show_page_border`](/slides/python-net/de/aspose.slides.export/swfoptions/show_page_border/) | Gibt an, ob ein Rand um die Seiten angezeigt werden soll. Standard ist true. |
| [`show_full_screen`](/slides/python-net/de/aspose.slides.export/swfoptions/show_full_screen/) | Vollbild-Schaltfläche ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [`show_page_stepper`](/slides/python-net/de/aspose.slides.export/swfoptions/show_page_stepper/) | Seitenschrittanzeige ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [`show_search`](/slides/python-net/de/aspose.slides.export/swfoptions/show_search/) | Suchbereich ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [`show_top_pane`](/slides/python-net/de/aspose.slides.export/swfoptions/show_top_pane/) | Ganzes oberes Panel ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [`show_bottom_pane`](/slides/python-net/de/aspose.slides.export/swfoptions/show_bottom_pane/) | Unteres Panel ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [`show_left_pane`](/slides/python-net/de/aspose.slides.export/swfoptions/show_left_pane/) | Linkes Panel ein-/ausblenden. Kann in flashvars überschrieben werden. Standard ist true. |
| [`start_open_left_pane`](/slides/python-net/de/aspose.slides.export/swfoptions/start_open_left_pane/) | Mit geöffnetem linkem Panel starten. Kann in flashvars überschrieben werden. Standard ist false. |
| [`enable_context_menu`](/slides/python-net/de/aspose.slides.export/swfoptions/enable_context_menu/) | Kontextmenü aktivieren/deaktivieren. Standard ist true. |
| [`logo_image_bytes`](/slides/python-net/de/aspose.slides.export/swfoptions/logo_image_bytes/) | Bild, das im oberen rechten Eck des Betrachters als Logo angezeigt wird.<br/>            Das Bild sollte ein 32x64 Pixel großes PNG-Bild sein, sonst kann das Logo fehlerhaft dargestellt werden. |
| [`logo_link`](/slides/python-net/de/aspose.slides.export/swfoptions/logo_link/) | Ruft die vollständige Hyperlink-Adresse für ein Logo ab oder legt sie fest.<br/>            Wirkt nur, wenn ein [`SwfOptions.logo_image_bytes`](/slides/python-net/de/aspose.slides.export/swfoptions/logo_image_bytes) angegeben ist. |
| [`jpeg_quality`](/slides/python-net/de/aspose.slides.export/swfoptions/jpeg_quality/) | Gibt die Qualität von JPEG-Bildern an.<br/>            Standard ist 95. |
| [`slides_layout_options`](/slides/python-net/de/aspose.slides.export/swfoptions/slides_layout_options/) | Ruft den Modus ab oder legt ihn fest, in dem Folien beim Export einer Präsentation [`ISlidesLayoutOptions`](/slides/python-net/de/aspose.slides.export/islideslayoutoptions) auf die Seite platziert werden.<br/>            Diese Eigenschaft unterstützt nicht das Zuweisen von Objekten des Typs [`HandoutLayoutingOptions`](/slides/python-net/de/aspose.slides.export/handoutlayoutingoptions) |

### Siehe auch
* Klasse [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)
* Klasse [`SwfOptions`](/slides/python-net/de/aspose.slides.export/swfoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)