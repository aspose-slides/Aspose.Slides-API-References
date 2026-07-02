---
title: IPdfOptions
second_title: Aspose.Sildes voor .NET API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-indeling.
type: docs
weight: 4000
url: /nl/aspose.slides.export/ipdfoptions/
---
## IPdfOptions interface

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-indeling.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden toegekend wanneer het document wordt geopend met gebruikersrechten. Zie [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Geeft een array van door de gebruiker gedefinieerde namen van lettertypefamilies terug of stelt deze in, die Aspose.Slides als gangbaar moet beschouwen. Lezen/schrijven String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Past de opgegeven transparante kleur toe op een afbeelding als `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Geeft de ISaveOptions interface terug. Alleen-lezen [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. Als ingesteld op Boolean.true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere grootte van het resulterende PDF-document. Het selecteren van de beste compressieverhouding is rekenkundig intensief en vereist extra RAM, en deze optie is standaard Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Gewenst conformiteitsniveau voor het gegenereerde PDF-document. Lezen/schrijven [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Waar om een zwart kader rond elke dia te tekenen. Lezen/schrijven Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een gebruikte subset. Lezen/schrijven Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | Waar om TrueType-lettertypen in te sluiten voor ASCII-tekens 32-127. Lettertypen voor teken-codes groter dan 127 worden altijd ingesloten. Lezen/schrijven Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Geeft de transparante kleur van de afbeelding terug of stelt deze in. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | Waar om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in de resulterende PDF. Lezen/schrijven Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Biedt opties die het uiterlijk van inktobjecten in het geëxporteerde document regelen. Alleen-lezen [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Geeft een waarde terug of stelt deze in die de kwaliteit van JPEG-afbeeldingen in het PDF-document bepaalt. Lezen/schrijven Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Stelt het gebruikerswachtwoord in om het PDF-document te beveiligen. Lezen/schrijven String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Geeft aan of tekst moet worden gerasterd als bitmap en opgeslagen in PDF wanneer het lettertype geen vetgedrukte stijl ondersteunt. Deze benadering kan de kwaliteit van tekst in de resulterende PDF voor bepaalde lettertypen verbeteren. Lezen/schrijven Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | Waar om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Lezen/schrijven Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Geeft de modus terug of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Geeft een waarde terug of stelt deze in die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Specificeert het compressietype dat moet worden gebruikt voor alle tekstuele inhoud in het document. Lezen/schrijven [`PdfTextCompression`](../pdftextcompression). |

### Zie ook

* interface [ISaveOptions](../isaveoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->