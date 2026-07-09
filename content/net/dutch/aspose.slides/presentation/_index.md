---
title: Presentation
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een Microsoft PowerPoint-presentatie voor.
type: docs
weight: 9590
url: /nl/aspose.slides/presentation/
---
## Presentation klasse

Stelt een Microsoft PowerPoint-presentatie voor.

```csharp
public sealed class Presentation : IPresentation
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [Presentation](presentation#constructor)() | Deze constructor maakt een nieuwe presentatie vanaf nul. De gemaakte presentatie heeft één lege dia. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Deze constructor maakt een nieuwe presentatie vanaf nul. De gemaakte presentatie heeft één lege dia. |
| [Presentation](presentation#constructor_2)(Stream) | Deze constructor is de primaire manier om een bestaande Presentation te lezen. |
| [Presentation](presentation#constructor_4)(string) | Deze constructor haalt een bronbestandspad op waaruit de inhoud van de Presentation wordt gelezen. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Deze constructor is de primaire manier om een bestaande Presentation te lezen. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Deze constructor haalt een bronbestandspad op waaruit de inhoud van de Presentation wordt gelezen. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Retourneert alle aangepaste gegevensonderdelen in de presentatie. Alleen-lezen [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Retourneert de verzameling van alle ingebedde audiobestanden in de presentatie. Alleen-lezen [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Retourneert de verzameling van commentaarauteurs. Alleen-lezen [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. Standaard de tijd van creatie van dit Presentation-object. Lezen/Schrijven DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Retourneert de aangepaste gegevens van de presentatie. Alleen-lezen [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Retourneert de standaard tekststijl voor vormen. Alleen-lezen [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Retourneert de verzameling handtekeningen die gebruikt worden om de presentatie te ondertekenen. Alleen-lezen [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Retourneert DocumentProperties-object dat standaard- en aangepaste documenteigenschappen bevat. Alleen-lezen [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Stelt het eerste dia-nummer in de presentatie voor |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Retourneert de lettertypebeheerder. Alleen-lezen [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Retourneert de huidige HeaderFooter-beheerder. Alleen-lezen [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatiedia's staan (niet in master-, lay-out- of notitiesdia's). Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Retourneert de verzameling van alle afbeeldingen in de presentatie. Alleen-lezen [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Retourneert een lijst van alle lay-outdia's die in de presentatie zijn gedefinieerd. Alleen-lezen [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Retourneert handout master-beheerder. Alleen-lezen [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Retourneert notities master-beheerder. Alleen-lezen [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Retourneert een lijst van alle masterdia's die in de presentatie zijn gedefinieerd. Alleen-lezen [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Retourneert het master-thema. Alleen-lezen [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Retourneert notitie-dia-grootte-object. Alleen-lezen [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Haalt beheerder van de permissies voor deze presentatie op. Alleen-lezen [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Retourneert een lijst van alle secties van dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Retourneert de verzameling van sensitiviteitslabels die op het presentatiedocument zijn toegepast. Alleen-lezen [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Retourneert de diavoorstellingsinstellingen voor de presentatie. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Retourneert dia-grootte-object. Alleen-lezen [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Retourneert informatie over uit welk formaat de presentatie is geladen. Alleen-lezen [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Haalt op of stelt VBA-project met presentatiemacro’s in. Lezen/Schrijven [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Retourneert de verzameling van alle ingebedde videobestanden in de presentatie. Alleen-lezen [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Haalt presentatiebrede weergaveeigenschappen op. Alleen-lezen [`IViewProperties`](../iviewproperties). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Geeft alle resources die door dit Presentation-object worden gebruikt vrij. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Retourneert Image-objecten voor alle dia's van een presentatie. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Retourneert Thumbnail Image-objecten voor de opgegeven dia's van een presentatie. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie met de opgegeven grootte. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie met aangepaste schaal. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Retourneert Thumbnail Image-objecten voor de opgegeven dia's van een presentatie met de opgegeven grootte. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Retourneert Thumbnail Image-objecten voor de opgegeven dia's van een presentatie met aangepaste schaal. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Retourneert een Slide, MasterSlide of LayoutSlide op basis van Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea's in alle geschikte vormen in alle dia's. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Slaat alle dia's van een presentatie op in een set bestanden die XAML-markup vertegenwoordigen. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummers. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat en met extra opties. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat en behoud van paginanummers. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummers. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat en behoud van paginanummers. |

### Voorbeelden

Het volgende voorbeeld toont hoe een PowerPoint Presentation te maken.

```csharp
[C#]
// Maak een Presentation-object dat een presentatiebestand voorstelt
using (Presentation presentation = new Presentation())
{
    // Haal de eerste dia op
    ISlide slide = presentation.Slides[0];
    // Voeg een autoshape van het type lijn toe
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Sla het presentatiebestand op.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Het volgende voorbeeld toont hoe een Presentation te openen en op te slaan.

```csharp
[C#]
// Laad elk ondersteund bestand in Presentation, bijv. ppt, pptx, odp enz.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Sla het presentatiebestand op.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* interface [IPresentation](../ipresentation)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->