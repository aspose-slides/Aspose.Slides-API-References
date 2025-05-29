---
title: IPdfOptions
second_title: Aspose.Slides für .NET API Referenz
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
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Enthält eine Reihe von Flags, die angeben, welche Zugriffsrechte gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. Siehe [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder legt es fest, die Aspose.Slides als üblich betrachten soll. Lese-/Schreibzugriff auf String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Wendet die angegebene transparente Farbe auf ein Bild an, wenn `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Gibt die ISaveOptions-Schnittstelle zurück. Nur Lesezugriff auf [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Gibt an, ob die effektivste Kompression (anstatt der Standardkompression) für jedes Bild automatisch ausgewählt werden muss. Wenn auf Boolean.true gesetzt, wird für jedes Bild in der Präsentation der am besten geeignete Komprimierungsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt. Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und benötigt zusätzlichen RAM; diese Option ist standardmäßig auf Boolean.false gesetzt. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Gewünschtes Konformitätsniveau für das generierte PDF-Dokument. Lese-/Schreibzugriff auf [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lese-/Schreibzugriff auf Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Legt fest, ob alle Zeichen der Schrift eingebettet oder nur der verwendete Teil eingebettet werden soll. Lese-/Schreibzugriff auf Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True, um TrueType-Schriften für ASCII-Zeichen 32-127 einzubetten. Schriften für Zeichencodes größer als 127 werden immer eingebettet. Lese-/Schreibzugriff auf Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Ruft die transparente Farbe des Bildes ab oder legt sie fest. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lese-/Schreibzugriff auf Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Bietet Optionen, die das Erscheinungsbild von Tintenobjekten im exportierten Dokument steuern. Nur Lesezugriff auf [`IInkOptions`](../iinkoptions). |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lese-/Schreibzugriff auf Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Setzt ein Benutzerpasswort, um das PDF-Dokument zu schützen. Lese-/Schreibzugriff auf String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Gibt an, ob Text als Bitmap gerastert und im PDF gespeichert werden soll, wenn die Schriftart keine fetten Stile unterstützt. Dieser Ansatz kann die Qualität des Textes im resultierenden PDF für bestimmte Schriften verbessern. Lese-/Schreibzugriff auf Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True, um alle in der Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lese-/Schreibzugriff auf Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Gibt an, ob das generierte Dokument versteckte Folien enthalten soll oder nicht. Standard ist `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Ruft den Modus ab oder legt ihn fest, in dem Folien beim Exportieren einer Präsentation auf der Seite platziert werden [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Gibt den Kompressionstyp an, der für alle Textinhalte im Dokument verwendet werden soll. Lese-/Schreibzugriff auf [`PdfTextCompression`](../pdftextcompression). |

### Siehe auch

* Schnittstelle [ISaveOptions](../isaveoptions)
* Namespace [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->