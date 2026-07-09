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

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [SwfOptions](swfoptions)() | Standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Specificeert of het gegenereerde SWF-document al dan niet gecomprimeerd moet worden. Standaard is `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Geeft het lettertype terug of stelt het in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lezen/Schrijven String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Activeer/deactiveer contextmenu. Standaard is true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Geeft de visuele stijl van de gradient terug of stelt deze in. Lezen/Schrijven [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Specificeert de kwaliteit van JPEG-afbeeldingen. Standaard is 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Afbeelding die wordt weergegeven als logo in de rechterbovenhoek van de viewer. De afbeelding moet een PNG van 32x64 pixels zijn, anders kan het logo onjuist worden weergegeven. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Geeft het volledige hyperlinkadres voor een logo terug of stelt dit in. Heeft alleen effect als een [`LogoImageBytes`](./logoimagebytes) is gespecificeerd. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Stelt een callback-object voor het opslaan van voortgangsupdates in procenten voor. Zie [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Toon/verberg onderste deelvenster. Kan worden overschreven in flashvars. Standaard is true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Toon/verberg volledigschermknop. Kan worden overschreven in flashvars. Standaard is true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Toon/verberg linker paneel. Kan worden overschreven in flashvars. Standaard is true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Specificeert of een rand rond pagina's moet worden weergegeven. Standaard is true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Toon/verberg paginastepper. Kan worden overschreven in flashvars. Standaard is true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Toon/verberg zoeksectie. Kan worden overschreven in flashvars. Standaard is true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Toon/verberg volledig bovenpaneel. Kan worden overschreven in flashvars. Standaard is true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specificeert of hyperlinks met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. Lezen/Schrijven Boolean. De standaardwaarde is **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Geeft de modus terug of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [`ISlidesLayoutOptions`](../islideslayoutoptions). Deze eigenschap ondersteunt het toewijzen van objecten van het type [`HandoutLayoutingOptions`](../handoutlayoutingoptions) niet. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Start met geopend linker paneel. Kan worden overschreven in flashvars. Standaard is false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Specificeert of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. Standaard is `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Geeft een object terug of stelt het in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/Schrijven [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voorbeelden

Het volgende voorbeeld laat zien hoe PowerPoint naar SWF Flash wordt geconverteerd.

```csharp
[C#]
// Maak een Presentation-object aan dat een presentatiebestand vertegenwoordigt
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Presentatie en notitiepagina's opslaan
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Zie ook

* klasse [SaveOptions](../saveoptions)
* interface [ISwfOptions](../iswfoptions)
* naamruimte [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->