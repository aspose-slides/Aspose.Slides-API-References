---
title: SwfOptions
second_title: Aspose.Sildes för .NET API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i Swf-format.
type: docs
weight: 4510
url: /sv/aspose.slides.export/swfoptions/
---
## SwfOptions klass

Tillhandahåller alternativ som styr hur en presentation sparas i Swf-format.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SwfOptions](swfoptions)() | Standardkonstruktör. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Anger om det genererade SWF-dokumentet ska komprimeras eller inte. Standardvärdet är `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Returnerar eller anger teckensnittet som används om källteckensnittet inte hittas. Läs/skriv String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Aktivera/inaktivera snabbmenyn. Standardvärdet är true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Returnerar eller anger den visuella stilen för gradienten. Läs/skriv [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Anger kvaliteten på JPEG-bilder. Standardvärdet är 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Bild som kommer att visas som logotyp i det övre högra hörnet av visaren. Bilden bör vara en 32x64 pixlar PNG-bild, annars kan logotypen visas felaktigt. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Hämtar eller anger den fullständiga hyperlänkadressen för en logotyp. Har endast effekt om en [`LogoImageBytes`](./logoimagebytes) anges. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representerar ett återuppringningsobjekt för sparande av förloppsuppdateringar i procent. Se [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Visa/dölj nedre panelen. Kan åsidosättas i flashvars. Standardvärdet är true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Visa/dölj helskärmsknapp. Kan åsidosättas i flashvars. Standardvärdet är true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standardvärdet är `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Visa/dölj vänstra panelen. Kan åsidosättas i flashvars. Standardvärdet är true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Anger om kantlinjen runt sidor ska visas. Standardvärdet är true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Visa/dölj sidstegsgivare. Kan åsidosättas i flashvars. Standardvärdet är true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Visa/dölj söksektion. Kan åsidosättas i flashvars. Standardvärdet är true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Visa/dölj hela översta panelen. Kan åsidosättas i flashvars. Standardvärdet är true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Läs/skriv Boolean. Standardvärdet är **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Hämtar eller anger det läge i vilket bilder placeras på sidan vid export av en presentation [`ISlidesLayoutOptions`](../islideslayoutoptions). Denna egenskap stöder inte tilldelning av objekt av typen [`HandoutLayoutingOptions`](../handoutlayoutingoptions). |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Starta med öppnad vänster panel. Kan åsidosättas i flashvars. Standardvärdet är false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. Standardvärdet är `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Returnerar eller anger ett objekt som mottar varningar och beslutar om inläsningsprocessen ska fortsätta eller avbrytas. Läs/skriv [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exempel

```csharp
[C#]
// Skapa ett Presentation-objekt som representerar en presentationsfil
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Spara presentation och notssidor
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Se även

* klass [SaveOptions](../saveoptions)
* gränssnitt [ISwfOptions](../iswfoptions)
* namnområde [Aspose.Slides.Export](../../aspose.slides.export)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->