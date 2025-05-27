---
title: SVGOptions
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine SVG-Option dar.
type: docs
weight: 4240
url: /de/aspose.slides.export/svgoptions/
---

## SVGOptions-Klasse

Stellt eine SVG-Option dar.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initialisiert eine neue Instanz der SVGOptions-Klasse. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initialisiert eine neue Instanz der SVGOptions-Klasse und gibt das Objekt des Link-Einbettungscontrollers an. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Gibt die Standard-Einstellungen zurück. Nur-lesend [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Gibt die Einstellungen für die einfachste und kleinste SVG-Dateigenerierung zurück. Nur-lesend [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Gibt die Einstellungen für die genaueste SVG-Dateigenerierung zurück. Nur-lesend [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-/Schreib-String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Ein boolesches Flag, das angibt, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn wahr, werden die beschnittenen Teile entfernt, wenn falsch, werden sie im Dokument serialisiert (was möglicherweise zu einer größeren Datei führen kann). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Bestimmt, ob der 3D-Text in SVG deaktiviert ist. Lese-/Schreib-Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Gibt einen Wert zurück oder legt einen Wert fest, der angibt, ob Text ohne Verwendung von Ligaturen gerendert wird. Wenn auf `true` gesetzt, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf `false` gesetzt. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Gradienten. Lese-/Schreib-Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 hat keine Möglichkeit, Einzüge für Marker zu definieren. Die SVG-Schreibmaschine von Aspose.Slides hat einen Workaround für dieses Problem: Sie schneidet das Ende der Linie mit dem Pfeil ab, sodass die Linie die Marker nicht überlappt. Diese Option schaltet dieses Verhalten aus. Lese-/Schreib-Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Bestimmt die Handhabung extern geladener Schriftarten. Lese-/Schreib- [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Gradienten zurück oder legt ihn fest. Lese-/Schreib- [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Bietet Optionen, die das Erscheinungsbild von Ink-Objekten im exportierten Dokument steuern. Nur-lesend [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Bestimmt die JPEG-Codierungsqualität. Lese-/Schreib-Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Gibt die untere Auflösungsgrenze für die Metafile-Rasterisierung zurück oder legt sie fest. Lese-/Schreib-Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Stellt das Kompressionsniveau für Bilder dar. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stellt ein Callback-Objekt für das Speichern von Fortschrittsaktualisierungen in Prozent dar. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Gibt ein Callback-Interface zurück und legt es fest, das es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. Lese-/Schreib- [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lese-/Schreib-Boolean. Der Standardwert ist **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Bestimmt, ob die angegebene Rotation der Form beim Rendern durchgeführt werden soll oder nicht. Lese-/Schreib-Boolean. Der Standardwert ist true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Bestimmt, ob der Textrahmen in einem Rendering-Bereich enthalten ist oder nicht. Lese-/Schreib-Boolean. Der Standardwert ist false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Lese-/Schreib-Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladeprozess fortgesetzt oder abgebrochen wird. Lese-/Schreib- [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Siehe auch

* Klasse [SaveOptions](../saveoptions)
* Schnittstelle [ISVGOptions](../isvgoptions)
* Namespace [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->