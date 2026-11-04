---
title: IPdfOptions
second_title: Aspose.Sildes voor .NET API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in PDF-formaat.
type: docs
weight: 4020
url: /nl/aspose.slides.export/ipdfoptions/
---
## IPdfOptions interface

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in PDF-formaat.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Properties

| Naam | Beschrijving |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Bevat een reeks vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Geeft een array van door de gebruiker gedefinieerde namen van lettertypefamilies terug of stelt deze in, die Aspose.Slides als gangbaar moet beschouwen. Lezen/Schrijven String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Past de opgegeven transparante kleur toe op een afbeelding als `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Geeft de ISaveOptions interface terug. Alleen-lezen [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Geeft aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd. Indien ingesteld op Boolean.true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere omvang van het resulterende PDF-document. Het selecteren van de beste afbeeldingscompressieverhouding is rekenintensief en kost extra RAM, en deze optie is standaard Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. Lezen/Schrijven [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True om een zwart kader rond elke dia te tekenen. Lezen/Schrijven Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een subset. Lezen/Schrijven Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True om TrueType-lettertypen in te sluiten voor ASCII-tekens 32-127. Lettertypen voor tekencodes groter dan 127 worden altijd ingesloten. Lezen/Schrijven Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Geeft de transparante kleur van de afbeelding terug of stelt deze in. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in het resulterende PDF-document. Lezen/Schrijven Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document bepalen. Alleen-lezen [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Geeft een waarde terug of stelt deze in die de kwaliteit van JPEG-afbeeldingen in het PDF-document bepaalt. Lezen/Schrijven Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Instellen van het gebruikerswachtwoord om het PDF-document te beveiligen. Lezen/Schrijven String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Geeft aan of tekst moet worden gerasterd als bitmap en opgeslagen in PDF wanneer het lettertype geen vette stijl ondersteunt. Deze benadering kan de kwaliteit van tekst in het resulterende PDF-document verbeteren voor bepaalde lettertypen. Lezen/Schrijven Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Lezen/Schrijven Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Geeft de modus terug of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Geeft een waarde terug of stelt deze in die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Specificeert het compressietype dat moet worden gebruikt voor alle tekstuele inhoud in het document. Lezen/Schrijven [`PdfTextCompression`](../pdftextcompression). |

### See Also

* interface [ISaveOptions](../isaveoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->