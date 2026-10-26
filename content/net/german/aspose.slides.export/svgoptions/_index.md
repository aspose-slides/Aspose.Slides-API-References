---
title: SVGOptions
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt SVG-Optionen dar.
type: docs
weight: 4430
url: /de/aspose.slides.export/svgoptions/
---
## SVGOptions Klasse

Stellt SVG-Optionen dar.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initialisiert eine neue Instanz der SVGOptions Klasse. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initialisiert eine neue Instanz der SVGOptions Klasse und gibt das Link-Embedding-Controller-Objekt an. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Gibt die Standardeinstellungen zurück. Nur lesbar [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Gibt die Einstellungen für die einfachste und kleinste SVG-Dateigenerierung zurück. Nur lesbar [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Gibt die Einstellungen für die genaueste SVG-Dateigenerierung zurück. Nur lesbar [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lesen/Schreiben String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Ein boolesches Flag gibt an, ob die beschnittenen Teile beim Dokument verbleiben. Wenn true, werden die beschnittenen Teile entfernt, wenn false, werden sie im Dokument serialisiert (was möglicherweise zu einer größeren Datei führen kann). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Bestimmt, ob der 3D-Text in SVG deaktiviert ist. Lesen/Schreiben Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Liest oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf `true` gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf `false` gesetzt. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Deaktiviert das Aufspalten von FromCornerX- und FromCenter-Verläufen. Lesen/Schreiben Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 unterstützt das Definieren von Einzügen für Marker nicht. Die Aspose.Slides-SVG-Schreibengine hat dafür einen Workaround: Sie schneidet das Ende der Linie mit Pfeil ab, sodass die Linie die Marker nicht überlappt. Diese Option schaltet dieses Verhalten aus. Lesen/Schreiben Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Bestimmt, wie extern geladene Schriften behandelt werden. Lesen/Schreiben [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest. Lesen/Schreiben [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Bietet Optionen, die das Erscheinungsbild von Ink-Objekten im exportierten Dokument steuern. Nur lesbar [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Bestimmt die JPEG-Kodierungsqualität. Lesen/Schreiben Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Gibt die untere Auflösungsgrenze für die Rasterisierung von Metadateien zurück oder legt sie fest. Lesen/Schreiben Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Stellt das Komprimierungsniveau der Bilder dar |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stellt ein Callback-Objekt für die prozentuale Fortschrittsanzeige beim Speichern dar. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Gibt eine Callback-Schnittstelle zurück und legt sie fest, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. Lesen/Schreiben [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Legt fest, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lesen/Schreiben Boolean. Der Standardwert ist **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Bestimmt, ob die angegebene Drehung der Form beim Rendern ausgeführt werden soll oder nicht. Lesen/Schreiben Boolean. Standardwert ist true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Bestimmt, ob der Textrahmen in den Renderbereich einbezogen wird oder nicht. Lesen/Schreiben Boolean. Standardwert ist false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Lesen/Schreiben Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Siehe auch

* Klasse [SaveOptions](../saveoptions)
* Schnittstelle [ISVGOptions](../isvgoptions)
* Namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->