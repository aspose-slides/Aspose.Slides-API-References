---
title: PdfOptions
second_title: Aspose.Sildes für .NET API-Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.
type: docs
weight: 4140
url: /de/aspose.slides.export/pdfoptions/
---

## PdfOptions-Klasse

Bietet Optionen, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.

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
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Beinhaltet eine Menge von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. Siehe [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder setzt es, die Aspose.Slides als gewöhnlich betrachten sollte. Lese-/Schreibzugriff String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Wendet die angegebene transparente Farbe auf ein Bild an, wenn `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Gibt an, ob die effektivste Komprimierung (anstatt der Standardkomprimierung) für jedes Bild automatisch ausgewählt werden muss. Wenn auf Boolean.true gesetzt, wird für jedes Bild in der Präsentation der passendste Komprimierungsalgorithmus ausgewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt. Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und benötigt eine zusätzliche Menge an RAM, und diese Option ist standardmäßig auf Boolean.false gesetzt. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Gewünschtes Konformitätsniveau für das generierte PDF-Dokument. Lese-/Schreibzugriff [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Gibt die Schriftart zurück oder setzt sie, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Lese-/Schreibzugriff String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lese-/Schreibzugriff Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Bestimmt, ob alle Zeichen einer Schriftart eingebettet werden sollen oder nur der verwendete Teil. Lese-/Schreibzugriff Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Bestimmt, ob Aspose.Slides gängige Schriftarten für ASCII (Codebereich 33..127) Texte einbetten wird. Schriftarten für Zeichen-Codes größer als 127 werden immer eingebettet. Die Liste der gängigen Schriftarten umfasst die 14 Basis-Schriftarten von PDF und zusätzlich vom Benutzer angegebene Schriftarten. Lese-/Schreibzugriff Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Gibt den visuellen Stil des Verlaufs zurück oder setzt ihn. Lese-/Schreibzugriff [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Holt oder setzt die transparente Farbe des Bildes. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lese-/Schreibzugriff Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Bietet Optionen, die das Aussehen von Tintobjekten im exportierten Dokument steuern. Schreibgeschützt [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Gibt einen Wert zurück oder setzt ihn, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lese-/Schreibzugriff Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Setzt ein Benutzerpasswort zum Schutz des PDF-Dokuments. Lese-/Schreibzugriff String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stellt ein Callback-Objekt für die Speichervorgangsaktualisierungen in Prozent dar. Siehe [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Gibt an, ob Text als Bitmap gerastert und im PDF gespeichert werden soll, wenn die Schriftart keine fetten Stile unterstützt. Dieser Ansatz kann die Qualität des Textes im resultierenden PDF für bestimmte Schriftarten verbessern. Lese-/Schreibzugriff Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lese-/Schreibzugriff Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Gibt an, ob das generierte Dokument versteckte Folien enthalten soll oder nicht. Standard ist `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lese-/Schreibzugriff Boolean. Der Standardwert ist **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Holt oder setzt den Modus, in dem Folien beim Export einer Präsentation auf der Seite platziert werden [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Gibt einen Wert zurück oder setzt ihn, der die Auflösung von Bildern im PDF-Dokument bestimmt. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Gibt den Kompressionstyp an, der für alle textuellen Inhalte im Dokument verwendet werden soll. Lese-/Schreibzugriff [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Gibt ein Objekt zurück oder setzt es, das Warnungen empfängt und entscheidet, ob der Ladeprozess fortgesetzt oder abgebrochen wird. Lese-/Schreibzugriff [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

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
	// Setzt das Verhalten für Metadateien
	pdfOptions.SaveMetafilesAsPng = true;
	// Setzt das Textkompressionsniveau
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
// Instanziiert eine Präsentationsklasse, die eine PowerPoint-Datei darstellt
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
// Instanziiert ein Präsentationsobjekt, das eine PowerPoint-Datei darstellt
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Instanziiert die PdfOptions-Klasse
	PdfOptions pdfOptions = new PdfOptions();
	// Setzt das PDF-Passwort und die Zugriffsberechtigungen
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Speichert die Präsentation als PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Das folgende Beispiel zeigt, wie PowerPoint mit Notizen in PDF konvertiert wird.

```csharp
[C#]
// Instanziiert ein Präsentationsobjekt, das eine Präsentationsdatei darstellt
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Einstellung von Folientyp und -größe
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Siehe auch

* Klasse [SaveOptions](../saveoptions)
* Schnittstelle [IPdfOptions](../ipdfoptions)
* Namespace [Aspose.Slides.Export](../../aspose.slides.export)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->