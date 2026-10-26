---
title: GifOptions class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/gifoptions/
---
## GifOptions Klasse

Stellt Optionen für den GIF-Export dar.

**Vererbung:**[`GifOptions`](/slides/python-net/de/aspose.slides.export/gifoptions) → [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)

Der GifOptions-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/gifoptions/__init__/#) | Initialisiert eine neue Instanz der GifOptions-Klasse. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/gifoptions/warning_callback/) | Gibt ein Objekt zurück bzw. legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/gifoptions/progress_callback/) | Stellt ein Callback-Objekt für Fortschrittsaktualisierungen beim Speichern in Prozent dar.<br/>            Siehe [`IProgressCallback`](/slides/python-net/de/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/gifoptions/default_regular_font/) | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/gifoptions/gradient_style/) | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`GradientStyle`](/slides/python-net/de/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/gifoptions/skip_java_script_links/) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen.<br/>            Lesen/Schreiben **bool**. Der Standardwert ist **false**. |
| [`frame_size`](/slides/python-net/de/aspose.slides.export/gifoptions/frame_size/) | Gibt die Frame-Größe zurück oder legt sie fest. |
| [`export_hidden_slides`](/slides/python-net/de/aspose.slides.export/gifoptions/export_hidden_slides/) | Bestimmt, ob versteckte Folien exportiert werden.<br/>            Der Standardwert ist false. |
| [`transition_fps`](/slides/python-net/de/aspose.slides.export/gifoptions/transition_fps/) | Gibt die Übergangs-FPS [frames/sec] zurück oder legt sie fest<br/>            Der Standardwert ist 25. |
| [`default_delay`](/slides/python-net/de/aspose.slides.export/gifoptions/default_delay/) | Gibt die Standardverzögerungszeit [ms] zurück oder legt sie fest. Dieser Wert wird verwendet, wenn [`ISlideShowTransition.advance_after_time`](/slides/python-net/de/aspose.slides/islideshowtransition/advance_after_time) nicht gesetzt ist.<br/>            Der Standardwert ist 1000. |

### Siehe auch
* Klasse [`GifOptions`](/slides/python-net/de/aspose.slides.export/gifoptions)
* Klasse [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)