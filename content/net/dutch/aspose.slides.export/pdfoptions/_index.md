---
title: PdfOptions
second_title: Aspose.Sildes voor .NET API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.
type: docs
weight: 4330
url: /nl/aspose.slides.export/pdfoptions/
---
## PdfOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PdfOptions](pdfoptions)() | Standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Geeft of stelt een array van door de gebruiker gedefinieerde namen van lettertypefamilies in die Aspose.Slides als gemeenschappelijk moet beschouwen. Lezen/Schrijven String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Past de opgegeven transparante kleur toe op een afbeelding als `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. Als ingesteld op Boolean.true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere PDF-grootte. De beste compressieverhouding is rekenintensief en vereist extra RAM; deze optie is Boolean.false standaard. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. Lezen/Schrijven [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Geeft of stelt het lettertype in dat moet worden gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen/Schrijven String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | Waar als er een zwart kader rond elke dia moet worden getekend. Lezen/Schrijven Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Bepaalt of alle tekens van het lettertype moeten worden ingebed of alleen een subset. Lezen/Schrijven Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Bepaalt of Aspose.Slides gemeenschappelijke lettertypen voor ASCII-tekst (codebereik 33..127) zal inbedden. Lettertypen voor tekens met codes boven 127 worden altijd ingebed. De lijst met gemeenschappelijke lettertypen omvat de basis-14 lettertypen van PDF en extra door de gebruiker gespecificeerde lettertypen. Lezen/Schrijven Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Geeft of of de visuele stijl van de gradient moet worden opgegeven. Lezen/Schrijven [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Haalt of stelt de transparante kleur van de afbeelding in. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | Waar als alle OLE-gegevens uit de presentatie moeten worden omgezet naar ingebedde bestanden in het resulterende PDF-document. Lezen/Schrijven Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Biedt opties die bepalen hoe Ink-objecten eruitzien in het geëxporteerde document. Alleen-lezen [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Geeft of stelt een waarde in die de kwaliteit van JPEG-afbeeldingen in het PDF-document bepaalt. Lezen/Schrijven Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Instellen van gebruikers-wachtwoord om het PDF-document te beveiligen. Lezen/Schrijven String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Vertegenwoordigt een callback-object voor voortgangsupdates bij het opslaan in percentage. Zie [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Geeft aan of tekst moet worden gerasterd als bitmap en opgeslagen in PDF wanneer het lettertype geen vette stijl ondersteunt. Deze aanpak kan de kwaliteit van tekst in het resulterende PDF-document voor bepaalde lettertypen verbeteren. Lezen/Schrijven Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | Waar als alle metafiles die in een presentatie worden gebruikt moeten worden omgezet naar PNG-afbeeldingen. Lezen/Schrijven Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Bepaalt of het gegenereerde document verborgen dia's moet bevatten. Standaard is `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Bepaalt of hyperlinks met JavaScript-oproepen moeten worden overgeslagen bij het opslaan van de presentatie. Lezen/Schrijven Boolean. De standaardwaarde is **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Haalt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Geeft of stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Bepaalt het compressietype dat moet worden gebruikt voor alle tekstuele inhoud in het document. Lezen/Schrijven [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Geeft of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/Schrijven [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voorbeelden

Het volgende voorbeeld toont hoe PowerPoint naar PDF kan worden geconverteerd met aangepaste opties.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instantieert de PdfOptions-klasse
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

Het volgende voorbeeld toont hoe PowerPoint naar PDF kan worden geconverteerd met verborgen dia's.

```csharp
[C#]
// Instantieert een Presentation-klasse die een PowerPoint-bestand voorstelt
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instantieert de PdfOptions-klasse
	PdfOptions pdfOptions = new PdfOptions();
	// Voegt verborgen dia's toe
	pdfOptions.ShowHiddenSlides = true;
	// Slaat de presentatie op als PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Het volgende voorbeeld toont hoe PowerPoint naar een met wachtwoord beveiligde PDF kan worden geconverteerd.

```csharp
[C#]
// Instantieert een Presentation-object dat een PowerPoint-bestand voorstelt
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

Het volgende voorbeeld toont hoe PowerPoint naar PDF kan worden geconverteerd met notities.

```csharp
[C#]
// Instantieert een Presentation-object dat een presentatiebestand voorstelt
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Instellen van dia-type en grootte
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
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->