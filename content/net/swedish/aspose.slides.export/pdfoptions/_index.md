---
title: PdfOptions
second_title: Aspose.Sildes för .NET API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i PDF-format.
type: docs
weight: 4310
url: /sv/aspose.slides.export/pdfoptions/
---
## PdfOptions-klass

Tillhandahåller alternativ som styr hur en presentation sparas i PDF-format.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfOptions](pdfoptions)() | Standardkonstruktor. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Innehåller en uppsättning flaggor som anger vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Returnerar eller anger en matris med användardefinierade namn på teckensnittsfamiljer som Aspose.Slides ska betrakta som vanliga. Läs/skriv String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Tillämpar den angivna transparenta färgen på en bild om `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Indikerar om den mest effektiva komprimeringen (istället för standard) för varje bild ska väljas automatiskt. Om satt till Boolean.true, kommer den mest lämpliga komprimeringsalgoritmen att väljas för varje bild i presentationen, vilket leder till en mindre storlek på den resulterande PDF-dokumentet. Valet av bästa bildkomprimeringsförhållande är beräkningsintensivt och kräver extra RAM, och detta alternativ är Boolean.false som standard. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Önskad kompatibilitetsnivå för genererat PDF-dokument. Läs/skriv [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Returnerar eller anger teckensnitt som används om källteckensnittet inte hittas. Läs/skriv String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True för att rita en svart ram runt varje bild. Läs/skriv Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Bestämmer om alla tecken i teckensnittet ska bäddas in eller endast en delmängd. Läs/skriv Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Bestämmer om Aspose.Slides ska bädda in vanliga teckensnitt för ASCII (33..127) text. Teckensnitt för teckenkoder över 127 bäddas alltid in. Listan med vanliga teckensnitt inkluderar PDF:ens grundläggande 14 teckensnitt och ytterligare användarspecificerade teckensnitt. Läs/skriv Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Returnerar eller anger den visuella stilen för gradienten. Läs/skriv [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Hämtar eller anger bildens transparenta färg. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF-en. Läs/skriv Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Tillhandahåller alternativ som styr hur bläckobjekt ser ut i exporterat dokument. Endast läsning [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet. Läs/skriv Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Ange användarlösenord för att skydda PDF-dokumentet. Läs/skriv String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representerar ett återuppringningsobjekt för sparande av förloppsuppdateringar i procent. Se [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indikerar om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stödjer fet stil. Detta tillvägagångssätt kan förbättra textkvaliteten i den resulterande PDF för vissa teckensnitt. Läs/skriv Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs/skriv Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Läs/skriv Boolean. Standardvärdet är **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Returnerar eller anger ett värde som bestämmer upplösningen för bilder i PDF-dokumentet. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Anger komprimeringstyp som ska användas för allt textinnehåll i dokumentet. Läs/skriv [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Returnerar eller anger ett objekt som tar emot varningar och bestämmer om inläsningsprocessen ska fortsätta eller avbrytas. Läs/skriv [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exempel

Följande exempel visar hur man konverterar PowerPoint till PDF med anpassade alternativ.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instansierar PdfOptions-klassen
	PdfOptions pdfOptions = new PdfOptions();
	// Anger JPEG-kvaliteten
	pdfOptions.JpegQuality = 90;
	// Anger beteendet för metafiler
	pdfOptions.SaveMetafilesAsPng = true;
	// Anger nivå för textkomprimering
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Definierar PDF-standarden
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Sparar presentationen som en PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Följande exempel visar hur man konverterar PowerPoint till PDF med dolda bilder.

```csharp
[C#]
// Instansierar en Presentation-klass som representerar en PowerPoint-fil
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instansierar PdfOptions-klassen
	PdfOptions pdfOptions = new PdfOptions();
	// Lägger till dolda bilder
	pdfOptions.ShowHiddenSlides = true;
	// Sparar presentationen som en PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Följande exempel visar hur man konverterar PowerPoint till lösenordsskyddad PDF.

```csharp
[C#]
// Instansierar ett Presentation-objekt som representerar en PowerPoint-fil
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Instansierar PdfOptions-klassen
	PdfOptions pdfOptions = new PdfOptions();
	// Anger PDF-lösenord och åtkomstbehörigheter
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Sparar presentationen som en PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Följande exempel visar hur man konverterar PowerPoint till PDF med anteckningar.

```csharp
[C#]
// Instansierar ett Presentation-objekt som representerar en presentationsfil
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Ställer in bildtyp och storlek
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Se också

* klass [SaveOptions](../saveoptions)
* gränssnitt [IPdfOptions](../ipdfoptions)
* namnrymd [Aspose.Slides.Export](../../aspose.slides.export)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->