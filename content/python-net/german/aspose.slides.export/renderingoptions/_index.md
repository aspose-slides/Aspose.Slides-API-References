---
title: RenderingOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/renderingoptions/
---
## RenderingOptions Klasse

Stellt Optionen bereit, die steuern, wie eine Präsentation/Folie gerendert wird.

**Vererbung:**[`RenderingOptions`](/slides/python-net/de/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)

Der Typ RenderingOptions stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/renderingoptions/__init__/#) | Standardkonstruktor. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/renderingoptions/warning_callback/) | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird.<br/>            Lese/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/renderingoptions/progress_callback/) | Stellt ein Rückrufobjekt für das Speichern von Fortschrittsaktualisierungen in Prozent dar.<br/>            Siehe [`IProgressCallback`](/slides/python-net/de/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/renderingoptions/default_regular_font/) | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quell-Schriftart nicht gefunden wird.<br/>            Lese/Schreiben **str**. |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/renderingoptions/gradient_style/) | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest.<br/>            Lese/Schreiben [`GradientStyle`](/slides/python-net/de/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/renderingoptions/skip_java_script_links/) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen.<br/>            Lese/Schreiben **bool**. Der Standardwert ist **false**. |
| [`slides_layout_options`](/slides/python-net/de/aspose.slides.export/renderingoptions/slides_layout_options/) | Gibt den Modus zurück oder legt ihn fest, in dem Folien beim Export einer Präsentation [`ISlidesLayoutOptions`](/slides/python-net/de/aspose.slides.export/islideslayoutoptions) auf der Seite angeordnet werden. |
| [`ink_options`](/slides/python-net/de/aspose.slides.export/renderingoptions/ink_options/) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern.<br/>            Nur-Lesen [`IInkOptions`](/slides/python-net/de/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/de/aspose.slides.export/renderingoptions/disable_font_ligatures/) | Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen gerendert wird.<br/>            Wird er auf `true` gesetzt, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf `false` gesetzt. |


### Siehe auch
* Klasse [`RenderingOptions`](/slides/python-net/de/aspose.slides.export/renderingoptions)
* Klasse [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)