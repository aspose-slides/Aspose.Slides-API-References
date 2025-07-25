---
title: PptxOptions
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt Optionen zum Speichern von OpenXml-Präsentationen PPTX PPSX POTX PPTM PPSM POTM dar.
type: docs
weight: 4180
url: /de/aspose.slides.export/pptxoptions/
---

## PptxOptions-Klasse

Stellt Optionen zum Speichern von OpenXml-Präsentationen (PPTX, PPSX, POTX, PPTM, PPSM, POTM) dar.

```csharp
public sealed class PptxOptions : SaveOptions, IPptxOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PptxOptions](pptxoptions)() | Erstellt eine neue Instanz von PptxOptions |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Conformance](../../aspose.slides.export/pptxoptions/conformance) { get; set; } | Gibt die Konformitätsklasse an, zu der das Präsentationsdokument konform ist. Der Standardwert ist Ecma376_2006 |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese- und Schreibzeichenfolge. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Gradienten zurück oder legt ihn fest. Lese-/Schreibzugriff [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stellt ein Callback-Objekt für das Speichern von Fortschrittsaktualisierungen in Prozent dar. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RefreshThumbnail](../../aspose.slides.export/pptxoptions/refreshthumbnail) { get; set; } | Gibt an, ob das Miniaturbild der Präsentation aktualisiert werden soll. Lese-/Schreibzugriff Boolean. Der Standardwert ist **true**. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lese-/Schreibzugriff Boolean. Der Standardwert ist **false**. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lese-/Schreibzugriff [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |
| [Zip64Mode](../../aspose.slides.export/pptxoptions/zip64mode) { get; set; } | Gibt an, ob das ZIP64-Format für das Präsentationsdokument verwendet wird. Der Standardwert ist IfNecessary |

### Siehe auch

* Klasse [SaveOptions](../saveoptions)
* Schnittstelle [IPptxOptions](../ipptxoptions)
* Namespace [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->