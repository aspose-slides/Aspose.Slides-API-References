---
title: PdfOptions
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt Optionen bereit, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.
type: docs
weight: 4350
url: /de/aspose.slides.export/pdfoptions/
---
## PdfOptions Klasse

Stellt Optionen bereit, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfOptions](pdfoptions)() | Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. Siehe [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder legt es fest, das Aspose.Slides als gemeinsam betrachten soll. Lesen/Schreiben String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Wendet die angegebene transparente Farbe auf ein Bild an, wenn `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Gibt an, ob für jedes Bild die effektivste Kompression (statt der Standardkompression) automatisch ausgewählt werden soll. Wenn auf Boolean.true gesetzt, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt. Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und benötigt zusätzlichen Arbeitsspeicher, und diese Option ist standardmäßig Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Lesen/Schreiben [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lesen/Schreiben String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True, um um jede Folie einen schwarzen Rahmen zu zeichnen. Lesen/Schreiben Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein genutzter Teilbereich. Lesen/Schreiben Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Bestimmt, ob Aspose.Slides gängige Schriften für ASCII-Text (Code-Bereich 33..127) einbetten wird. Schriften für Zeichencodes größer als 127 werden immer eingebettet. Die Liste der gängigen Schriften umfasst die 14 Basis-PDF-Schriften und zusätzlich vom Benutzer angegebene Schriften. Lesen/Schreiben Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest. Lesen/Schreiben [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Liest oder legt die transparente Farbe des Bildes fest. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lesen/Schreiben Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Stellt Optionen bereit, die das Aussehen von Tintenobjekten im exportierten Dokument steuern. Nur lesen [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/Schreiben Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Festlegen des Benutzerkennworts zum Schutz des PDF-Dokuments. Lesen/Schreiben String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Repräsentiert ein Callback-Objekt für das Speichern von Fortschrittsaktualisierungen in Prozent. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Gibt an, ob Text als Bitmap gerastert und in das PDF gespeichert werden soll, wenn die Schriftart keine fette Formatierung unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriften verbessern. Lesen/Schreiben Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lesen/Schreiben Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standard ist `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Gibt an, ob beim Speichern der Präsentation Hyperlinks mit JavaScript-Aufrufen übersprungen werden sollen. Lesen/Schreiben Boolean. Der Standardwert ist **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation auf die Seite platziert werden [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Gibt den Kompressionstyp an, der für sämtlichen Textinhalt im Dokument verwendet werden soll. Lesen/Schreiben [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Beispiele

Das folgende Beispiel zeigt, wie PowerPoint mit benutzerdefinierten Optionen in PDF konvertiert wird.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instanziiert die PdfOptions-Klasse
	PdfOptions pdfOptions = new PdfOptions();
	// Setzt die JPEG-Qualität
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

Das folgende Beispiel zeigt, wie PowerPoint mit verborgenen Folien in PDF konvertiert wird.

```csharp
[C#]
// Instanziiert eine Presentation-Klasse, die eine PowerPoint-Datei darstellt
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instanziiert die PdfOptions-Klasse
	PdfOptions pdfOptions = new PdfOptions();
	// Fügt verborgene Folien hinzu
	pdfOptions.ShowHiddenSlides = true;
	// Speichert die Präsentation als PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Das folgende Beispiel zeigt, wie PowerPoint in ein kennwortgeschütztes PDF konvertiert wird.

```csharp
[C#]
// Instanziiert ein Presentation-Objekt, das eine PowerPoint-Datei darstellt
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Instanziiert die PdfOptions-Klasse
	PdfOptions pdfOptions = new PdfOptions();
	// Legt das PDF-Passwort und die Zugriffsberechtigungen fest
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

### Siehe auch

* Klasse [SaveOptions](../saveoptions)
* Schnittstelle [IPdfOptions](../ipdfoptions)
* Namensraum [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->