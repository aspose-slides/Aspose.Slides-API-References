---
title: IPdfOptions
second_title: Aspose.Sildes für .NET API-Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.
type: docs
weight: 4020
url: /de/aspose.slides.export/ipdfoptions/
---
## IPdfOptions Schnittstelle

Stellt Optionen bereit, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Eigenschaften

| Name | Description |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. Siehe [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder setzt es, die Aspose.Slides als üblich betrachten sollte. Lesen/Schreiben String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Wendet die angegebene transparente Farbe auf ein Bild an, wenn `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Gibt die ISaveOptions Schnittstelle zurück. Schreibgeschützt [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Gibt an, ob die effektivste Kompression (statt der standardmäßigen) für jedes Bild automatisch ausgewählt werden muss. Wenn auf Boolean.true gesetzt, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt. Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und verbraucht zusätzlichen RAM, und diese Option ist standardmäßig Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Lesen/Schreiben [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lesen/Schreiben Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. Lesen/Schreiben Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True, um TrueType-Schriften für ASCII-Zeichen 32-127 einzubetten. Schriften für Zeichenkodierungen größer als 127 werden immer eingebettet. Lesen/Schreiben Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Liest oder setzt die transparente Bildfarbe. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lesen/Schreiben Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Schreibgeschützt [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Gibt einen Wert zurück oder setzt ihn, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/Schreiben Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Festlegen des Benutzerkennworts zum Schutz des PDF-Dokuments. Lesen/Schreiben String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine fette Formatierung unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriftarten verbessern. Lesen/Schreiben Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lesen/Schreiben Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standard ist `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Liest oder setzt den Modus, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Gibt einen Wert zurück oder setzt ihn, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Gibt den zu verwendenden Kompressionstyp für alle Textinhalte im Dokument an. Lesen/Schreiben [`PdfTextCompression`](../pdftextcompression). |

### Siehe auch

* Schnittstelle [ISaveOptions](../isaveoptions)
* Namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->