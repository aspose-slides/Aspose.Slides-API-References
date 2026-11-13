---
title: IPdfOptions
second_title: Aspose.Sildes för .NET API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i Pdf-format.
type: docs
weight: 4020
url: /sv/aspose.slides.export/ipdfoptions/
---
## IPdfOptions gränssnitt

Tillhandahåller alternativ som styr hur en presentation sparas i PDF-format.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Returnerar eller anger en array av användardefinierade namn på teckensnittsfamiljer som Aspose.Slides bör betrakta som gemensamma. Läs/skriv String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Tillämpar den angivna transparenta färgen på en bild om `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Returnerar ISaveOptions-gränssnitt. Endast läs [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Anger om den mest effektiva kompressionen (istället för standard) för varje bild ska väljas automatiskt. Om den är inställd på Boolean.true, kommer för varje bild i presentationen det mest lämpliga kompressionsalgoritmet att väljas, vilket leder till en mindre storlek på det resulterande PDF-dokumentet. Val av bästa bildkompressionsförhållande är beräkningsmässigt dyrt och kräver ytterligare RAM, och detta alternativ är Boolean.false som standard. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Önskad kompatibilitetsnivå för genererat PDF-dokument. Läs/skriv [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Sätt till true för att rita en svart ram runt varje bild. Läs/skriv Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Bestämmer om alla tecken i teckensnittet ska bäddas in eller endast en använd delmängd. Läs/skriv Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | Sätt till true för att bädda in TrueType-teckensnitt för ASCII-tecken 32-127. Teckensnitt för teckenkoder över 127 är alltid inbäddade. Läs/skriv Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Hämtar eller anger bildens transparenta färg. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | Sätt till true för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF:en. Läs/skriv Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Tillhandahåller alternativ som styr utseendet på bläckobjekt i exporterat dokument. Endast läs [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet. Läs/skriv Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Ställer in användarlösenord för att skydda PDF-dokumentet. Läs/skriv String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Anger om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stöder fet stil. Detta tillvägagångssätt kan förbättra textkvaliteten i den resulterande PDF:en för vissa teckensnitt. Läs/skriv Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | Sätt till true för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs/skriv Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standardvärdet är `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Hämtar eller anger läget där bilder placeras på sidan vid export av en presentation [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Returnerar eller anger ett värde som bestämmer upplösning för bilder i PDF-dokumentet. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Anger kompressionstyp som ska användas för allt textinnehåll i dokumentet. Läs/skriv [`PdfTextCompression`](../pdftextcompression). |

### Se också

* gränssnitt [ISaveOptions](../isaveoptions)
* namnrymd [Aspose.Slides.Export](../../aspose.slides.export)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->