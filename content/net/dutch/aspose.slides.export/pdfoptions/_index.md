---
title: PdfOptions
second_title: Aspose.Sildes voor .NET API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.
type: docs
weight: 4330
url: /nl/aspose.slides.export/pdfoptions/
---
## PdfOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in PDF-formaat.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PdfOptions](pdfoptions)() | Standaardconstructor. |

## Properties

| Naam | Beschrijving |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Bevat een set vlaggen die specificeren welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Geeft een array van door de gebruiker gedefinieerde namen van lettertypefamilies terug of stelt deze in, die Aspose.Slides als gangbaar moet beschouwen. Lezen/schrijven String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Past de opgegeven transparante kleur toe op een afbeelding als `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. Indien ingesteld op Boolean.true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere grootte van het resulterende PDF-document. Het selecteren van de optimale compressieverhouding is rekenkundig intensief en vereist extra RAM, en deze optie is standaard Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. Lezen/schrijven [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Geeft het lettertype terug of stelt het in dat gebruikt wordt wanneer het bronlettertype niet wordt gevonden. Lezen/schrijven String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True om een zwart kader rond elke dia te tekenen. Lezen/schrijven Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een subset. Lezen/schrijven Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Bepaalt of Aspose.Slides gangbare lettertypen inbedt voor ASCII-tekst (codebereik 33..127). Lettertypen voor tekencodes hoger dan 127 worden altijd ingesloten. De lijst met gangbare lettertypen omvat de basis-14 lettertypen van PDF en extra door de gebruiker opgegeven lettertypen. Lezen/schrijven Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Geeft de visuele stijl van de gradiënt terug of stelt deze in. Lezen/schrijven [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Haalt de transparante kleur van de afbeelding op of stelt deze in. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True om alle OLE-gegevens van de presentatie om te zetten naar ingesloten bestanden in het resulterende PDF. Lezen/schrijven Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Geeft een waarde terug of stelt deze in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. Lezen/schrijven Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Stelt het gebruikerswachtwoord in om het PDF-document te beveiligen. Lezen/schrijven String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stelt een callback-object voor het opslaan van voortgangsupdates in percentages voor. Zie [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Geeft aan of tekst moet worden gerasterd als bitmap en opgeslagen in PDF wanneer het lettertype geen vetstijl ondersteunt. Deze aanpak kan de kwaliteit van tekst in het resulterende PDF voor bepaalde lettertypen verbeteren. Lezen/schrijven Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Lezen/schrijven Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specificeert of hyperlinks met JavaScript-oproepen overgeslagen moeten worden bij het opslaan van de presentatie. Lezen/schrijven Boolean. De standaardwaarde is **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Haalt de modus op of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Geeft een waarde terug of stelt deze in die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Specificeert het compressietype dat wordt gebruikt voor alle tekstuele inhoud in het document. Lezen/schrijven [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Geeft een object terug of stelt dit in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of afgebroken. Lezen/schrijven [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voorbeelden

Het volgende voorbeeld toont hoe PowerPoint naar PDF te converteren met aangepaste opties.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instantiëert de PdfOptions-klasse
	PdfOptions pdfOptions = new PdfOptions();
	// Stelt de Jpeg-kwaliteit in
	pdfOptions.JpegQuality = 90;
	// Stelt het gedrag voor metafiles in
	pdfOptions.SaveMetafilesAsPng = true;
	// Stelt het tekstcompressieniveau in
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Definieert de PDF-standaard
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Slaat de presentatie op als PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Het volgende voorbeeld toont hoe PowerPoint naar PDF te converteren met verborgen dia's.

```csharp
[C#]
// Instantiëert een Presentation-klasse die een PowerPoint-bestand vertegenwoordigt
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instantiëert de PdfOptions-klasse
	PdfOptions pdfOptions = new PdfOptions();
	// Voegt verborgen dia's toe
	pdfOptions.ShowHiddenSlides = true;
	// Slaat de presentatie op als PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Het volgende voorbeeld toont hoe PowerPoint naar een met wachtwoord beveiligde PDF te converteren.

```csharp
[C#]
// Instantieert een Presentation-object dat een PowerPoint-bestand vertegenwoordigt
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Instantieert de PdfOptions-klasse
	PdfOptions pdfOptions = new PdfOptions();
	// Stelt het PDF-wachtwoord en de toegangsrechten in
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Slaat de presentatie op als PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Het volgende voorbeeld toont hoe PowerPoint naar PDF te converteren met notities.

```csharp
[C#]
// Instantieert een Presentation-object dat een presentatiebestand vertegenwoordigt
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Instellen van dia-type en -grootte
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Zie ook

* klasse [SaveOptions](../saveoptions)
* interface [IPdfOptions](../ipdfoptions)
* naamruimte [Aspose.Slides.Export](../../aspose.slides.export)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->