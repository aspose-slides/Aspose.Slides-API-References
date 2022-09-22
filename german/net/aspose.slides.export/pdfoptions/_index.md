---
title: PdfOptions
second_title: Aspose.Slides für .NET-API-Referenz
description: Bietet Optionen die steuern wie eine Präsentation im PDFFormat gespeichert wird.
type: docs
weight: 3950
url: /de/net/aspose.slides.export/pdfoptions/
---
## PdfOptions class

Bietet Optionen, die steuern, wie eine Präsentation im PDF-Format gespeichert wird.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfOptions](pdfoptions)() | Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Enthält eine Reihe von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. Sehen[`PdfAccessPermissions`](../pdfaccesspermissions) . |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder legt sie fest, die Aspose.Slides als gemeinsam betrachten sollte. Lesen/SchreibenString []. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Wendet die angegebene transparente Farbe auf ein Bild an, wenn`Stimmt` . |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Gibt an, ob die effektivste Komprimierung (anstelle der Standardkomprimierung) für jedes Bild automatisch ausgewählt werden muss. Wenn eingestelltBoolean.true, für jedes Bild in der Präsentation wird der am besten geeignete Komprimierungsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt.  Die Auswahl des besten Bildkomprimierungsverhältnisses ist rechenintensiv und benötigt eine zusätzliche Menge an RAM, und diese Option ist esBoolean.false standardmäßig. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Gewünschte Konformitätsstufe für generiertes PDF-Dokument. Lesen/Schreiben[`PdfCompliance`](../pdfcompliance) . |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die verwendete Schriftart zurück oder legt sie fest, falls die Quellschriftart nicht gefunden wird. Lesen/SchreibenString . |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lesen/SchreibenBoolean . |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Legt fest, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur eine Teilmenge verwendet wird. Lesen/SchreibenBoolean . |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Legt fest, ob Aspose.Slides gängige Schriftarten für ASCII-Text (Codebereich 33..127) einbettet. Schriftarten für Zeichencodes größer als 127 werden immer eingebettet. Die Liste der gängigen Schriftarten enthält die Basis-14-Schriftarten von PDF und zusätzliche benutzerdefinierte Schriftarten. Lesen SchreibenBoolean . |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Ruft die transparente Farbe des Bildes ab oder legt sie fest. |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Gibt einen Wert zurück oder legt einen Wert fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/SchreibenByte . |
| [NotesCommentsLayouting](../../aspose.slides.export/pdfoptions/notescommentslayouting) { get; } | Bietet Optionen, die steuern, wie Notizen und Kommentare im exportierten Dokument platziert werden. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Einstellen des Benutzerkennworts zum Schutz des PDF-Dokuments. Lesen/SchreibenString . |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Repräsentiert ein Callback-Objekt zum Speichern von Fortschrittsaktualisierungen in Prozent. Siehe[`IProgressCallback`](../../aspose.slides/iprogresscallback) . |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lesen/SchreibenBoolean . |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Gibt an, ob das generierte Dokument ausgeblendete Folien enthalten soll oder nicht. Standard ist`FALSCH` . |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Gibt einen Wert zurück oder legt einen Wert fest, der die Auflösung von Bildern im PDF-Dokument bestimmt. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Gibt den Komprimierungstyp an, der für den gesamten Textinhalt im Dokument verwendet werden soll. Lesen/Schreiben[`PdfTextCompression`](../pdftextcompression) . |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Siehe auch

* class [SaveOptions](../saveoptions)
* interface [IPdfOptions](../ipdfoptions)
* namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
