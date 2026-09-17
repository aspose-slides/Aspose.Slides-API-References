---
title: PptOptions class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/pptoptions/
---
## PptOptions Klasse

Stellt Optionen bereit, die steuern, wie eine Präsentation im PPT-Format gespeichert wird.

**Vererbung:**[`PptOptions`](/slides/python-net/de/aspose.slides.export/pptoptions) → [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)

Der Typ PptOptions stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/pptoptions/__init__/#) |  |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/pptoptions/warning_callback/) | Rückgabe oder Festlegung eines Objekts, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/pptoptions/progress_callback/) | Stellt ein Callback-Objekt für Fortschrittsaktualisierungen beim Speichern in Prozent dar.<br/>            Siehe [`IProgressCallback`](/slides/python-net/de/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/pptoptions/default_regular_font/) | Rückgabe oder Festlegung der Schriftart, die verwendet wird, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen/Schreiben **str**. |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/pptoptions/gradient_style/) | Rückgabe oder Festlegung des visuellen Stils des Farbverlaufs.<br/>            Lesen/Schreiben [`GradientStyle`](/slides/python-net/de/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/pptoptions/skip_java_script_links/) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen.<br/>            Lesen/Schreiben **bool**. Der Standardwert ist **false**. |
| [`root_directory_clsid`](/slides/python-net/de/aspose.slides.export/pptoptions/root_directory_clsid/) | Stellt die Objektklassen-GUID (CLSID) dar, die im Eintrag des Stammverzeichnisses gespeichert ist. Kann für COM<br/>            Aktivierung der Anwendung des Dokuments verwendet werden.<br/>            Der Standardwert ist '64818D11-4F9B-11CF-86EA-00AA00B929E8', der 'Microsoft Powerpoint.Slide.8' entspricht. |


### Siehe auch
* Klasse [`PptOptions`](/slides/python-net/de/aspose.slides.export/pptoptions)
* Klasse [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)