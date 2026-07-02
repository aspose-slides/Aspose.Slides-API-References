---
title: SwfOptions
second_title: Aspose.Sildes voor .NET API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Swf-indeling.
type: docs
weight: 4530
url: /nl/aspose.slides.export/swfoptions/
---
## SwfOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Swf-indeling.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SwfOptions](swfoptions)() | Standaardconstructor. |

## Eigenschappen

| Name | Description |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Geeft aan of het gegenereerde SWF-document gecomprimeerd moet worden of niet. Standaard is `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Geeft het lettertype terug of stelt het in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lees-schrijf String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Inschakelen/uitschakelen contextmenu. Standaard is true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Geeft de visuele stijl van de gradient terug of stelt deze in. Lees-schrijf [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Geef de kwaliteit van JPEG-afbeeldingen op. Standaard is 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Afbeelding die wordt weergegeven als logo in de rechterbovenhoek van de viewer. Afbeelding moet een PNG-afbeelding van 32×64 pixels zijn, anders kan het logo onjuist worden weergegeven. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Geeft het volledige hyperlink-adres van een logo terug of stelt dit in. Heeft alleen effect als een [`LogoImageBytes`](./logoimagebytes) is opgegeven. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stelt een callback-object voor dat voortgangsupdates bij het opslaan in procenten aangeeft. Zie [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Toon/verberg onderpaneel. Kan worden overschreven in flashvars. Standaard is true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Toon/verberg volledig-schermknop. Kan worden overschreven in flashvars. Standaard is true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Geeft aan of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Toon/verberg linkerpaneel. Kan worden overschreven in flashvars. Standaard is true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Geeft aan of de rand rond pagina's moet worden getoond. Standaard is true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Toon/verberg paginastepper. Kan worden overschreven in flashvars. Standaard is true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Toon/verberg zoeksectie. Kan worden overschreven in flashvars. Standaard is true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Toon/verberg complete bovenste paneel. Kan worden overschreven in flashvars. Standaard is true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Geeft aan of hyperlinks met JavaScript-oproepen moeten worden overgeslagen bij het opslaan van de presentatie. Lees-schrijf Boolean. De standaardwaarde is **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Geeft de modus terug of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](../islideslayoutoptions). Deze eigenschap ondersteunt het toewijzen van objecten van type [`HandoutLayoutingOptions`](../handoutlayoutingoptions) niet. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Start met geopend linkerpaneel. Kan worden overschreven in flashvars. Standaard is false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Geeft aan of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. Standaard is `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Geeft een object terug of stelt dit in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lees-schrijf [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voorbeelden

Het volgende voorbeeld toont hoe PowerPoint naar SWF Flash kan worden geconverteerd.

```csharp
[C#]
// Instantieer een Presentation-object dat een presentatiebestand vertegenwoordigt
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Opslaan van presentatie en notitiepagina's
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Zie ook

* klasse [SaveOptions](../saveoptions)
* interface [ISwfOptions](../iswfoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->