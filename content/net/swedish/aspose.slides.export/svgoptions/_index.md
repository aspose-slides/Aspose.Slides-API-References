---
title: SVGOptions
second_title: Aspose.Sildes för .NET API-referens
description: Representerar ett SVG-alternativ.
type: docs
weight: 4450
url: /sv/aspose.slides.export/svgoptions/
---
## SVGOptions klass

Representerar ett SVG-alternativ.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Konstruktorer

| Namn | Beskrivning |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initierar en ny instans av SVGOptions-klassen. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initierar en ny instans av SVGOptions-klassen med angivet ILinkEmbedController-objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Returnerar standardinställningar. Skrivskyddad [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Returnerar inställningar för den enklaste och minsta SVG-filgenereringen. Skrivskyddad [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Returnerar inställningar för den mest exakta SVG-filgenereringen. Skrivskyddad [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Returnerar eller anger teckensnitt som används om källteckensnittet inte hittas. Läs/skriv String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | En boolesk flagga som indikerar om de beskurna delarna förblir som en del av dokumentet. Om true tas de beskurna delarna bort, om false kommer de att serialiseras i dokumentet (vilket eventuellt kan leda till en större fil). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Bestämmer om 3D-text är inaktiverad i SVG. Läs/skriv Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Hämtar eller anger ett värde som indikerar om text renderas utan ligaturer. När den är satt till `true` inaktiveras ligaturer i den renderade utskriften. Som standard är egenskapen satt till `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Inaktiverar delning av FromCornerX- och FromCenter-gradienter. Läs/skriv Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 saknar möjlighet att definiera insets för markörer. Aspose.Slides SVG-skrivningsmotor har en lösning för detta problem: den beskär linjeändan med pil, så att linjen inte överlappar markörer. Detta alternativ stänger av sådant beteende. Läs/skriv Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Bestämmer ett sätt att hantera externt laddade teckensnitt. Läs/skriv [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Returnerar eller anger den visuella stilen för gradienten. Läs/skriv [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument. Skrivskyddad [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Bestämmer JPEG-kodningskvaliteten. Läs/skriv Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Returnerar eller anger den lägre upplösningsgränsen för metafilrasterisering. Läs/skriv Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Representerar komprimeringsnivån för bilder |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representerar ett återuppringningsobjekt för att spara framstegsupdateringar i procent. Se [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Returnerar och anger ett återuppringningsgränssnitt som tillåter användaren att kontrollera formkonvertering. Läs/skriv [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Läs/skriv Boolean. Standardvärdet är **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Bestämmer om den angivna rotationen av formen ska utföras vid rendering eller inte. Läs/skriv Boolean. Standardvärdet är true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Bestämmer om textramen ska inkluderas i ett renderingsområde eller inte. Läs/skriv Boolean. Standardvärdet är false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Bestämmer om texten på en bild ska sparas som grafik. Läs/skriv Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Returnerar eller anger ett objekt som tar emot varningar och avgör om inläsningsprocessen ska fortsätta eller avbrytas. Läs/skriv [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Se även

* klass [SaveOptions](../saveoptions)
* gränssnitt [ISVGOptions](../isvgoptions)
* namnrymd [Aspose.Slides.Export](../../aspose.slides.export)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->