---
title: IPdfOptions
second_title: Aspose.Slides für .NET API-Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.
type: docs
weight: 3830
url: /de/aspose.slides.export/ipdfoptions/
---

## IPdfOptions-Schnittstelle

Bietet Optionen, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Enthält eine Reihe von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. Siehe [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder legt es fest, die Aspose.Slides als allgemein betrachten sollte. Lese-/Schreib-String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Wendet die angegebene transparente Farbe auf ein Bild an, wenn `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Gibt die ISaveOptions-Schnittstelle zurück. Nur lesend [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Gibt an, ob die effektivste Kompression (anstatt der Standardkompression) für jedes Bild automatisch ausgewählt werden muss. Wenn auf Boolean.true gesetzt, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus ausgewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt. Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und benötigt zusätzlichen RAM, und diese Option ist standardmäßig Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Gewünschtes Konformitätsniveau für das generierte PDF-Dokument. Lese-/Schreib- [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lese-/Schreib-Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur die verwendete Teilmenge. Lese-/Schreib-Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True, um TrueType-Schriftarten für ASCII-Zeichen 32-127 einzubetten. Schriftarten für Zeichencodes größer als 127 werden immer eingebettet. Lese-/Schreib-Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Gibt die transparente Farbe des Bildes zurück oder legt sie fest. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lese-/Schreib-Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur lesend [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lese-/Schreib-Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Benutzerpasswort festlegen, um das PDF-Dokument zu schützen. Lese-/Schreib-String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Gibt an, ob Text als Bitmap rasterisiert und im PDF gespeichert werden soll, wenn die Schriftart die fette Formatierung nicht unterstützt. Dieser Ansatz kann die Qualität des Textes im resultierenden PDF für bestimmte Schriftarten verbessern. Lese-/Schreib-Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lese-/Schreib-Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Gibt an, ob das generierte Dokument versteckte Folien enthalten soll oder nicht. Standard ist `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Gibt den Modus an, in dem Folien beim Export einer Präsentation auf der Seite platziert werden [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Gibt einen Wert zurück oder legt ihn fest, der die Auflösung von Bildern im PDF-Dokument bestimmt. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Gibt den Kompressionstyp an, der für alle textuellen Inhalte im Dokument verwendet werden soll. Lese-/Schreib- [`PdfTextCompression`](../pdftextcompression). |

### Siehe auch

* Schnittstelle [ISaveOptions](../isaveoptions)
* Namespace [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->