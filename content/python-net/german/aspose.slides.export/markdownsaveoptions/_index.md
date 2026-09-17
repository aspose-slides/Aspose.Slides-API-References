---
title: MarkdownSaveOptions class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions Klasse

Stellt Optionen dar, die steuern, wie die Präsentation in Markdown gespeichert wird.

**Vererbung:**[`MarkdownSaveOptions`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)

Der Typ MarkdownSaveOptions stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/__init__/#) | Konstruktor. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/warning_callback/) | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/progress_callback/) | Stellt ein Rückrufobjekt für Fortschrittsaktualisierungen beim Speichern in Prozent dar.<br/>            Siehe [`IProgressCallback`](/slides/python-net/de/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Gibt die Schriftart zurück oder setzt sie, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/gradient_style/) | Gibt den visuellen Stil des Farbverlaufs zurück oder setzt ihn.<br/>            Lesen/Schreiben [`GradientStyle`](/slides/python-net/de/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen.<br/>            Lesen/Schreiben **bool**. Der Standardwert ist **false**. |
| [`export_type`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/export_type/) | Gibt die Markdown-Spezifikation zum Konvertieren der Präsentation an.<br/>            Standard ist `TextOnly`. |
| [`base_path`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/base_path/) | Gibt den Basispfad an, in dem das Dokument mit Ressourcen gespeichert wird.<br/>            Standard ist das aktuelle Verzeichnis der Anwendung. |
| [`images_save_folder_name`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Gibt den Ordnernamen zum Speichern von Bildern an.<br/>            Standard ist `Images`. |
| [`new_line_type`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/new_line_type/) | Gibt an, ob das erzeugte Dokument Zeilenumbrüche \r(Macintosh), \n(Unix) oder \r\n(Windows) haben soll.<br/>            Standard ist `Unix`. |
| [`show_comments`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/show_comments/) | Gibt an, ob das erzeugte Dokument Kommentare anzeigen soll.<br/>            Standard ist `false`. |
| [`show_hidden_slides`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Gibt an, ob das erzeugte Dokument versteckte Folien einbeziehen soll.<br/>            Standard ist `false`. |
| [`show_slide_number`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Gibt an, ob das erzeugte Dokument die Nummer jeder Folie anzeigen soll.<br/>            Standard ist `false`. |
| [`flavor`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/flavor/) | Gibt die Markdown-Spezifikation zum Konvertieren der Präsentation an.<br/>            Standard ist `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Ruft die Formatzeichenfolge für Foliennummernüberschriften in der Markdown-Ausgabe ab oder legt sie fest.<br/>            Das Format muss den Platzhalter "{0}" enthalten, der beim Export durch den Folienindex ersetzt wird.<br/>            Beispiel: "# Slide {0}" erzeugt "# Slide 1", "# Slide 2" usw. |
| [`handle_repeated_spaces`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Wenn auf `true` gesetzt, werden leere oder nur aus Leerzeichen bestehende Zeilen aus der endgültigen Markdown-Ausgabe entfernt.<br/>            Standard ist `false`. |

### Siehe auch
* Klasse [`MarkdownSaveOptions`](/slides/python-net/de/aspose.slides.export/markdownsaveoptions)
* Klasse [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)