---
title: Presentation
second_title: Aspose.Sildes voor .NET API-referentie
description: Representeert een Microsoft PowerPoint-presentatie.
type: docs
weight: 9610
url: /nl/aspose.slides/presentation/
---
## Presentation klasse

Representeert een Microsoft PowerPoint-presentatie.

```csharp
public sealed class Presentation : IPresentation
```

## Constructors

| Name | Description |
| --- | --- |
| [Presentation](presentation#constructor)() | Deze constructor maakt een nieuwe presentatie vanaf nul. De gemaakte presentatie bevat één lege dia. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Deze constructor maakt een nieuwe presentatie vanaf nul. De gemaakte presentatie bevat één lege dia. |
| [Presentation](presentation#constructor_2)(Stream) | Deze constructor is het primaire mechanisme voor het lezen van een bestaande Presentation. |
| [Presentation](presentation#constructor_4)(string) | Deze constructor krijgt een bronbestandspad waaruit de inhoud van de Presentation wordt gelezen. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Deze constructor is het primaire mechanisme voor het lezen van een bestaande Presentation. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Deze constructor krijgt een bronbestandspad waaruit de inhoud van de Presentation wordt gelezen. |

## Properties

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Retourneert alle aangepaste gegevensonderdelen in de presentatie. Alleen-lezen [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Retourneert de collectie van alle ingebedde audio-bestanden in de presentatie. Alleen-lezen [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Retourneert de collectie van commentaarauteurs. Alleen-lezen [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. Standaard de tijd van creatie van dit Presentation-object. Lezen/schrijven DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Retourneert de aangepaste gegevens van de presentatie. Alleen-lezen [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Retourneert de standaard tekststijl voor vormen. Alleen-lezen [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Retourneert de collectie van handtekeningen die worden gebruikt om de presentatie te ondertekenen. Alleen-lezen [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Retourneert DocumentProperties-object dat standaard- en aangepaste documenteigenschappen bevat. Alleen-lezen [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Geeft het eerste diapnummer in de presentatie weer |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Retourneert de font-manager. Alleen-lezen [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Retourneert de actuele HeaderFooter-manager. Alleen-lezen [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Biedt eenvoudige toegang tot alle hyperlinks in alle presentatiedia's (niet in master-, lay- of notitieslides). Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Retourneert de collectie van alle afbeeldingen in de presentatie. Alleen-lezen [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Retourneert een lijst van alle lay-outdia's die in de presentatie zijn gedefinieerd. Alleen-lezen [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Retourneert de handout-master-manager. Alleen-lezen [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Retourneert de notities-master-manager. Alleen-lezen [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Retourneert een lijst van alle master-dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Retourneert het master-thema. Alleen-lezen [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Retourneert het notities-dia-grootte-object. Alleen-lezen [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Haalt de manager van de permissies voor deze presentatie op. Alleen-lezen [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Retourneert een lijst van alle diasecties die in de presentatie zijn gedefinieerd. Alleen-lezen [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Retourneert de collectie van gevoeligheidslabels toegepast op het presentatiedocument. Alleen-lezen [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Retourneert de diavoorstellingsinstellingen voor de presentatie. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Retourneert het dia-grootte-object. Alleen-lezen [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Retourneert informatie over het formaat waaruit de presentatie is geladen. Alleen-lezen [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Haalt of stelt het VBA-project met presentatiemacro's in. Lezen/schrijven [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Retourneert de collectie van alle ingebedde videobestanden in de presentatie. Alleen-lezen [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Haalt de weergave-eigenschappen van de volledige presentatie op. Alleen-lezen [`IViewProperties`](../iviewproperties). |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Vrijgeeft alle bronnen die door dit Presentation-object worden gebruikt. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Retourneert Image-objecten voor alle dia's van een presentatie. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Retourneert miniatuur-Image-objecten voor de opgegeven dia's van een presentatie. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Retourneert miniatuur-Image-objecten voor alle dia's van een presentatie met opgegeven grootte. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Retourneert miniatuur-Image-objecten voor alle dia's van een presentatie met aangepaste schaal. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Retourneert miniatuur-Image-objecten voor de opgegeven dia's van een presentatie met opgegeven grootte. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Retourneert miniatuur-Image-objecten voor de opgegeven dia's van een presentatie met aangepaste schaal. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Retourneert een Slide, MasterSlide of LayoutSlide op basis van Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen in alle dia's. |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | Laadt de gegevens voor alle grafieken in de presentatie opnieuw vanuit hun bronwerkboeken. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekst. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Slaat alle dia's van een presentatie op in een reeks bestanden die XAML-markup vertegenwoordigen. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummer. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat en met extra opties. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummer. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummer. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummer. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe je een PowerPoint-Presentation maakt.

```csharp
[C#]
// Een Presentation-object maken dat een presentatiebestand voorstelt
using (Presentation presentation = new Presentation())
{
    // Haal de eerste dia op
    ISlide slide = presentation.Slides[0];
    // Voeg een autovorm van het type line toe
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Sla het presentatiebestand op.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Het volgende voorbeeld laat zien hoe je een Presentation opent en opslaat.

```csharp
[C#]
// Laad elk ondersteund bestand in Presentation bijv. ppt, pptx, odp etc.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Sla het presentatiebestand op.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->