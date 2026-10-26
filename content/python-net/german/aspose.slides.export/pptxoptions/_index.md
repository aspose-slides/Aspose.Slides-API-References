---
title: PptxOptions class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/pptxoptions/
---
## PptxOptions Klasse

Stellt Optionen zum Speichern von OpenXml-Präsentationen (PPTX, PPSX, POTX, PPTM, PPSM, POTM) bereit.

**Vererbung:**[`PptxOptions`](/slides/python-net/de/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)

Der PptxOptions-Typ stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.export/pptxoptions/__init__/#) | Erstellt eine neue Instanz von PptxOptions |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`warning_callback`](/slides/python-net/de/aspose.slides.export/pptxoptions/warning_callback/) | Gibt ein Objekt zurück bzw. setzt es, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird.<br/>            Lesen/Schreiben [`IWarningCallback`](/slides/python-net/de/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/de/aspose.slides.export/pptxoptions/progress_callback/) | Stellt ein Rückruffunktions-Objekt für Fortschritts-Updates beim Speichern in Prozent dar.<br/>            Siehe [`IProgressCallback`](/slides/python-net/de/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/de/aspose.slides.export/pptxoptions/default_regular_font/) | Gibt die Schriftart zurück oder setzt sie, die verwendet wird, falls die Quellschriftart nicht gefunden wird.<br/>            Lesen-Schreiben **str**. |
| [`gradient_style`](/slides/python-net/de/aspose.slides.export/pptxoptions/gradient_style/) | Gibt den visuellen Stil des Farbverlaufs zurück oder setzt ihn.<br/>            Lesen/Schreiben [`GradientStyle`](/slides/python-net/de/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/de/aspose.slides.export/pptxoptions/skip_java_script_links/) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen.<br/>            Lesen/Schreiben **bool**. Der Standardwert ist **false**. |
| [`conformance`](/slides/python-net/de/aspose.slides.export/pptxoptions/conformance/) | Gibt die Konformitäts-Klasse an, der das Präsentations-Dokument entspricht.<br/>            Standardwert ist [`Conformance.ECMA_376_2006`](/slides/python-net/de/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/de/aspose.slides.export/pptxoptions/zip_64_mode/) | Gibt an, ob das ZIP64-Format für das Präsentations-Dokument verwendet wird.<br/>            Der Standardwert ist [`Zip64Mode.IF_NECESSARY`](/slides/python-net/de/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/de/aspose.slides.export/pptxoptions/refresh_thumbnail/) | Gibt an, ob das Vorschaubild der Präsentation aktualisiert wird.<br/>            Lesen/Schreiben **bool**.<br/>            Standardwert ist **true**. |
| [`compression_level`](/slides/python-net/de/aspose.slides.export/pptxoptions/compression_level/) | Gibt die beim Speichern des Präsentations-Dokuments verwendete Komprimierungsstufe an.<br/>            Standardwert ist [`CompressionLevel.LEVEL6`](/slides/python-net/de/aspose.slides.export/compressionlevel/LEVEL6). |

### Siehe auch
* Klasse [`PptxOptions`](/slides/python-net/de/aspose.slides.export/pptxoptions)
* Klasse [`SaveOptions`](/slides/python-net/de/aspose.slides.export/saveoptions)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)