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

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Presentation](presentation#constructor)() | Deze constructor maakt een nieuwe presentatie vanaf nul. De gemaakte presentatie bevat één lege dia. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Deze constructor maakt een nieuwe presentatie vanaf nul. De gemaakte presentatie bevat één lege dia. |
| [Presentation](presentation#constructor_2)(Stream) | Deze constructor is het primaire mechanisme om een bestaande Presentation te lezen. |
| [Presentation](presentation#constructor_4)(string) | Deze constructor haalt een bron-bestandspad op waarvan de inhoud van de Presentation wordt gelezen. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Deze constructor is het primaire mechanisme om een bestaande Presentation te lezen. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Deze constructor haalt een bron-bestandspad op waarvan de inhoud van de Presentation wordt gelezen. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Geeft alle aangepaste gegevensonderdelen in de presentatie terug. Alleen-lezen [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Geeft de verzameling van alle ingesloten audiobestanden in de presentatie terug. Alleen-lezen [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Geeft de verzameling van commentauteur-ID’s terug. Alleen-lezen [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Geeft de datum en tijd terug of stelt deze in die de inhoud van datum-tijd-velden zal vervangen. Standaard de tijd van creatie van dit Presentation-object. Lezen/Schrijven DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Geeft de aangepaste gegevens van de presentatie terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Geeft de standaard tekststijl voor vormen terug. Alleen-lezen [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Geeft de verzameling van handtekeningen die gebruikt worden om de presentatie te ondertekenen terug. Alleen-lezen [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Geeft het DocumentProperties-object terug dat standaard- en aangepaste documenteigenschappen bevat. Alleen-lezen [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Vertegenwoordigt het eerste dia-nummer in de presentatie. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Geeft de lettertype-manager terug. Alleen-lezen [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Geeft de huidige HeaderFooter-manager terug. Alleen-lezen [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Biedt eenvoudige toegang tot alle hyperlinks die in presentatiedia’s (niet in master-, layout- of notitiedia) zijn opgenomen. Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Geeft de verzameling van alle afbeeldingen in de presentatie terug. Alleen-lezen [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Geeft een lijst van alle layout-dia’s die in de presentatie gedefinieerd zijn terug. Alleen-lezen [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Geeft de handout-master-manager terug. Alleen-lezen [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Geeft de notities-master-manager terug. Alleen-lezen [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Geeft een lijst van alle master-dia’s die in de presentatie gedefinieerd zijn terug. Alleen-lezen [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Geeft het master-thema terug. Alleen-lezen [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Geeft het notitie-dia-grootte-object terug. Alleen-lezen [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Haalt de manager van de machtigingen voor deze presentatie op. Alleen-lezen [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Geeft een lijst van alle secties van dia’s die in de presentatie gedefinieerd zijn terug. Alleen-lezen [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Geeft de verzameling van gevoeligheidslabels die op het presentatiedocument zijn toegepast terug. Alleen-lezen [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Geeft een lijst van alle dia’s die in de presentatie gedefinieerd zijn terug. Alleen-lezen [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Geeft de instellingen voor de diavoorstelling van de presentatie terug. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Geeft het dia-grootte-object terug. Alleen-lezen [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Geeft informatie over het formaat waarvan de presentatie is geladen terug. Alleen-lezen [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Haalt het VBA-project met presentatiemacro’s op of stelt dit in. Lezen/Schrijven [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Geeft de verzameling van alle ingesloten videobestanden in de presentatie terug. Alleen-lezen [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Haalt de weergave-eigenschappen voor de hele presentatie op. Alleen-lezen [`IViewProperties`](../iviewproperties). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Vrijgeeft alle resources die door dit Presentation-object worden gebruikt. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Retourneert Image-objecten voor alle dia’s van een presentatie. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Retourneert Thumbnail-Image-objecten voor opgegeven dia’s van een presentatie. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Retourneert Thumbnail-Image-objecten voor alle dia’s van een presentatie met de opgegeven grootte. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Retourneert Thumbnail-Image-objecten voor alle dia’s van een presentatie met aangepaste schaal. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Retourneert Thumbnail-Image-objecten voor opgegeven dia’s van een presentatie met de opgegeven grootte. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Retourneert Thumbnail-Image-objecten voor opgegeven dia’s van een presentatie met aangepaste schaal. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Retourneert een Slide, MasterSlide of LayoutSlide op basis van Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea’s in alle geschikte vormen in alle dia’s. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekst. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Vervangt alle voorkomende exemplaren van de opgegeven tekst door een andere opgegeven tekst. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Slaat alle dia’s van een presentatie op in een set bestanden die XAML-markup vertegenwoordigen. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Slaat alle dia’s van een presentatie op in een stream in het opgegeven formaat. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Slaat alle dia’s van een presentatie op in een bestand met het opgegeven formaat. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Slaat opgegeven dia’s van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummer. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Slaat alle dia’s van een presentatie op in een stream in het opgegeven formaat en met extra opties. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Slaat opgegeven dia’s van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummer. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Slaat opgegeven dia’s van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummer. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Slaat opgegeven dia’s van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummer. |

### Voorbeelden

Het volgende voorbeeld toont hoe een PowerPoint Presentation te maken.

```csharp
[C#]
// Maak een Presentation-object dat een presentatiebestand vertegenwoordigt
using (Presentation presentation = new Presentation())
{
    // Haal de eerste dia op
    ISlide slide = presentation.Slides[0];
    // Voeg een autovorm van het type lijn toe
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Sla het presentatiebestand op.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Het volgende voorbeeld toont hoe een Presentation te openen en op te slaan.

```csharp
[C#]
// Laad elk ondersteund bestand in Presentation, bijvoorbeeld ppt, pptx, odp enz.
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