---
title: SVGOptions
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt SVG-Optionen dar.
type: docs
weight: 4450
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
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initialisiert eine neue Instanz der SVGOptions Klasse und spezifiziert das Link-Embedding-Controller-Objekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Gibt die Standardeinstellungen zurück. Nur lesbar [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Gibt die Einstellungen für die einfachste und kleinste SVG-Dateierstellung zurück. Nur lesbar [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Gibt die Einstellungen für die genaueste SVG-Dateierstellung zurück. Nur lesbar [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lese/Schreib String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Ein boolescher Hinweis, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die beschnittenen Teile entfernt, wenn false, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Bestimmt, ob der 3D-Text in SVG deaktiviert ist. Lese/Schreib Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Gibt an, ob Text ohne Ligaturen gerendert wird. Beim Setzen auf `true` werden Ligaturen im gerenderten Ergebnis deaktiviert. Standardmäßig ist diese Eigenschaft auf `false` gesetzt. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. Lese/Schreib Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 kann keine Einrückungen für Marker definieren. Die Aspose.Slides-SVG-Schreibengine bietet dafür einen Workaround: Sie schneidet das Ende einer Linie mit Pfeil ab, sodass die Linie die Marker nicht überlappt. Diese Option schaltet dieses Verhalten aus. Lese/Schreib Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Bestimmt, wie extern geladene Schriftarten behandelt werden. Lese/Schreib [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest. Lese/Schreib [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur lesbar [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Bestimmt die JPEG-Kodierungsqualität. Lese/Schreib Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück oder legt sie fest. Lese/Schreib Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Stellt das Kompressionsniveau für Bilder dar. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stellt ein Callback-Objekt für das Speichern von Fortschrittsupdates in Prozent dar. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Gibt ein Callback-Interface zurück und legt es fest, das dem Benutzer die Kontrolle über die Formkonvertierung ermöglicht. Lese/Schreib [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lese/Schreib Boolean. Der Standardwert ist **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Bestimmt, ob die angegebene Drehung der Form beim Rendern ausgeführt wird. Lese/Schreib Boolean. Der Standardwert ist true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Bestimmt, ob der Textframe in einen Rendering-Bereich eingeschlossen wird. Lese/Schreib Boolean. Der Standardwert ist false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Lese/Schreib Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lese/Schreib [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Siehe auch

* Klasse [SaveOptions](../saveoptions)
* Schnittstelle [ISVGOptions](../isvgoptions)
* Namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->