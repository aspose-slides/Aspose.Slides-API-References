---
title: HtmlOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/htmloptions/
---
## HtmlOptions Klasse

Stellt HTML-Exportoptionen dar.

**Vererbung:**[`HtmlOptions`](/slides/python-net/de/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)

Der Typ HtmlOptions stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/de/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Erstellt ein neues HtmlOptions-Objekt, das einen Callback spezifiziert. |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/htmloptions/__init__/#) | Erstellt ein neues HtmlOptions-Objekt zum Speichern in einer einzelnen HTML-Datei. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/htmloptions/warning_callback/) | Gibt ein Objekt zurück oder setzt es, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/htmloptions/progress_callback/) | Stellt ein Callback-Objekt für das Speichern von Fortschrittsaktualisierungen in Prozent dar.<br/>            Siehe [`IProgressCallback`](/slides/python-net/de/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/htmloptions/default_regular_font/) | Gibt die Schriftart zurück oder setzt sie, die verwendet wird, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/htmloptions/gradient_style/) | Gibt den visuellen Stil des Farbverlaufs zurück oder setzt ihn.<br/>            Lesen/Schreiben [`GradientStyle`](/slides/python-net/de/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/htmloptions/skip_java_script_links/) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen.<br/>            Lesen/Schreiben **bool**. Der Standardwert ist **false**. |
| [`slides_layout_options`](/slides/python-net/de/aspose.slides.export/htmloptions/slides_layout_options/) | Liest oder setzt den Modus, in dem Folien beim Exportieren einer Präsentation auf die Seite platziert werden [`ISlidesLayoutOptions`](/slides/python-net/de/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/de/aspose.slides.export/htmloptions/ink_options/) | Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern.<br/>            Nur-Lesen [`IInkOptions`](/slides/python-net/de/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/de/aspose.slides.export/htmloptions/show_hidden_slides/) | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht.<br/>            Standard ist `false`. |
| [`html_formatter`](/slides/python-net/de/aspose.slides.export/htmloptions/html_formatter/) | Gibt die HTML-Vorlage zurück oder setzt sie.<br/>            Lesen/Schreiben [`IHtmlFormatter`](/slides/python-net/de/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/de/aspose.slides.export/htmloptions/disable_font_ligatures/) | Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird.<br/>            Wenn auf `true` gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf `false` gesetzt. |
| [`slide_image_format`](/slides/python-net/de/aspose.slides.export/htmloptions/slide_image_format/) | Gibt Optionen für das Folienbildformat zurück oder setzt sie.<br/>            Lesen/Schreiben [`ISlideImageFormat`](/slides/python-net/de/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/de/aspose.slides.export/htmloptions/jpeg_quality/) | Gibt einen Wert zurück oder setzt ihn, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt.<br/>            Lesen/Schreiben **int**. |
| [`pictures_compression`](/slides/python-net/de/aspose.slides.export/htmloptions/pictures_compression/) | Stellt das Komprimierungslevel von Bildern dar |
| [`delete_pictures_cropped_areas`](/slides/python-net/de/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die beschnittenen <br/>            Teile entfernt, wenn false werden sie im Dokument serialisiert (was zu einer <br/>            größeren Datei führen kann) |
| [`svg_responsive_layout`](/slides/python-net/de/aspose.slides.export/htmloptions/svg_responsive_layout/) | True, um Breiten- und Höhenattribute vom SVG-Container auszuschließen – das macht das Layout responsiv. False – andernfalls.<br/>            Lesen/Schreiben **bool**. |


### Siehe auch
* Klasse [`HtmlOptions`](/slides/python-net/de/aspose.slides.export/htmloptions)
* Klasse [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)