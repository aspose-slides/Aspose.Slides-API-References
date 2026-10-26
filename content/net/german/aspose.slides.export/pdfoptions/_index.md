---
title: PdfOptions
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt Optionen bereit, die steuern, wie eine Präsentation im PDF-Format gespeichert wird.
type: docs
weight: 4330
url: /de/aspose.slides.export/pdfoptions/
---
## PdfOptions Klasse

Stellt Optionen bereit, die steuern, wie eine Präsentation im PDF-Format gespeichert wird.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfOptions](pdfoptions)() | Standardkonstruktor. |

## Properties

| Name | Description |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte beim Öffnen des Dokuments mit Benutzerauswahl gewährt werden sollen. Siehe [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Gibt ein Array benutzerdefinierter Namen von Schriftfamilien zurück oder legt es fest, die Aspose.Slides als allgemein betrachten soll. Lese-/Schreibzugriff String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Wendet die angegebene transparente Farbe auf ein Bild an, falls `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Gibt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden soll. Wenn sie auf Boolean.true gesetzt ist, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt. Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und verbraucht zusätzlichen RAM; diese Option ist standardmäßig Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Lese-/Schreibzugriff [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-/Schreibzugriff String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lese-/Schreibzugriff Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. Lese-/Schreibzugriff Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Bestimmt, ob Aspose.Slides gängige Schriften für ASCII-Text (Code-Bereich 33..127) einbetten wird. Schriften für Zeichencodes über 127 werden immer eingebettet. Die Liste gängiger Schriften umfasst die 14 Basis-Schriften von PDF und zusätzlich vom Benutzer angegebene Schriften. Lese-/Schreibzugriff Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest. Lese-/Schreibzugriff [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Liest oder legt die transparente Farbe des Bildes fest. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lese-/Schreibzugriff Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur Lesezugriff [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lese-/Schreibzugriff Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Setzt ein Benutzerkennwort zum Schutz des PDF-Dokuments. Lese-/Schreibzugriff String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stellt ein Callback-Objekt für Fortschrittsupdates beim Speichern in Prozent dar. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Gibt an, ob Text als Bitmap gerastert und in das PDF gespeichert werden soll, wenn die Schriftart keine fette Darstellung unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriften verbessern. Lese-/Schreibzugriff Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lese-/Schreibzugriff Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standard ist `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Gibt an, ob beim Speichern der Präsentation Hyperlinks mit JavaScript-Aufrufen übersprungen werden sollen. Lese-/Schreibzugriff Boolean. Der Standardwert ist **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation auf die Seite platziert werden [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Gibt den Kompressionstyp an, der für sämtlichen Textinhalt im Dokument verwendet wird. Lese-/Schreibzugriff [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lese-/Schreibzugriff [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Examples

Das folgende Beispiel zeigt, wie PowerPoint mit benutzerdefinierten Optionen in PDF konvertiert wird.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instanziiert die PdfOptions-Klasse
	PdfOptions pdfOptions = new PdfOptions();
	// Setzt die Jpeg-Qualität
	pdfOptions.JpegQuality = 90;
	// Legt das Verhalten für Metadateien fest
	pdfOptions.SaveMetafilesAsPng = true;
	// Setzt die Textkomprimierungsstufe
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Definiert den PDF-Standard
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Speichert die Präsentation als PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Das folgende Beispiel zeigt, wie PowerPoint mit versteckten Folien in PDF konvertiert wird.

```csharp
[C#]
// Instanziiert eine Presentation-Klasse, die eine PowerPoint-Datei darstellt
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instanziiert die PdfOptions-Klasse
	PdfOptions pdfOptions = new PdfOptions();
	// Fügt versteckte Folien hinzu
	pdfOptions.ShowHiddenSlides = true;
	// Speichert die Präsentation als PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Das folgende Beispiel zeigt, wie PowerPoint in ein passwortgeschütztes PDF konvertiert wird.

```csharp
[C#]
// Instanziiert ein Presentation-Objekt, das eine PowerPoint-Datei darstellt
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Instanziiert die PdfOptions-Klasse
	PdfOptions pdfOptions = new PdfOptions();
	// Setzt das PDF-Passwort und die Zugriffsrechte
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Speichert die Präsentation als PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Das folgende Beispiel zeigt, wie PowerPoint mit Notizen in PDF konvertiert wird.

```csharp
[C#]
// Instanziiert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Festlegen von Folientyp und -größe
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### See Also

* Klasse [SaveOptions](../saveoptions)
* Schnittstelle [IPdfOptions](../ipdfoptions)
* Namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->