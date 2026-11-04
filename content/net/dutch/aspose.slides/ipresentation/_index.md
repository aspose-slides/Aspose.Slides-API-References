---
title: IPresentation
second_title: Aspose.Sildes voor .NET API-referentie
description: Presentatiedocument
type: docs
weight: 6770
url: /nl/aspose.slides/ipresentation/
---
## IPresentation interface

Presentation document

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Retourneert alle aangepaste gegevensonderdelen in de presentatie. Alleen-lezen [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Retourneert IDisposable interface. Alleen-lezen IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Staat toe om de basis IPresentationComponent interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Retourneert de verzameling van alle ingebedde audiobestanden in de presentatie. Alleen-lezen [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Retourneert de verzameling van commentaarauteurs. Alleen-lezen [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. Tijd van aanmaak van dit Presentation-object standaard. Lezen/schrijven DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Retourneert de aangepaste gegevens van de presentatie. Alleen-lezen [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Retourneert de standaardtekststijl voor vormen. Alleen-lezen [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Retourneert de verzameling handtekeningen die gebruikt worden om de presentatie te ondertekenen. Alleen-lezen [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Retourneert DocumentProperties-object dat standaard- en aangepaste documenteigenschappen bevat. Alleen-lezen [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Stelt het eerste slide-nummer in de presentatie voor. Lezen/schrijven Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Retourneert de lettertypebeheerder. Alleen-lezen [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Retourneert HeaderFooter-beheerder van de presentatie. Alleen-lezen [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatieslides zitten (niet in master-, lay- of notitieslides). Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Retourneert de verzameling van alle afbeeldingen in de presentatie. Alleen-lezen [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Retourneert een lijst van alle layout-slides die in de presentatie zijn gedefinieerd. Alleen-lezen [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Retourneert handout-master-beheerder. Alleen-lezen [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Retourneert notities-master-beheerder. Alleen-lezen [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Retourneert een lijst van alle master-slides die in de presentatie zijn gedefinieerd. Alleen-lezen [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Retourneert het master-thema van de presentatie. Alleen-lezen [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Retourneert notities-slide-grootte-object. Alleen-lezen [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Haalt de beheerder van de permissies voor deze presentatie op. Alleen-lezen [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Retourneert een lijst van alle slide-secties die in de presentatie zijn gedefinieerd. Alleen-lezen [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Retourneert de verzameling van gevoeligheidslabels die op het presentatiedocument zijn toegepast. Alleen-lezen [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Retourneert een lijst van alle slides die in de presentatie zijn gedefinieerd. Alleen-lezen [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Retourneert slide-grootte-object. Alleen-lezen [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Retourneert informatie over het formaat waaruit de presentatie is geladen. Alleen-lezen [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Haal VBA-project met presentatiemacro's op. Lezen/schrijven [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Retourneert de verzameling van alle ingebedde videobestanden in de presentatie. Alleen-lezen [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Haal presentatieweide weergave-eigenschappen op. Alleen-lezen [`IViewProperties`](../iviewproperties). |

## Methoden

| Name | Description |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Retourneert miniatuuropbeeldobjecten voor alle slides van een presentatie. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Retourneert miniatuur-Bitmap-objecten voor opgegeven slides van een presentatie. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Retourneert miniatuuropbeeldobjecten voor alle slides van een presentatie met opgegeven grootte. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Retourneert miniatuuropbeeldobjecten voor alle slides van een presentatie met aangepaste schaal. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Retourneert miniatuuropbeeldobjecten voor opgegeven slides van een presentatie met opgegeven grootte. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Retourneert miniatuuropbeeldobjecten voor opgegeven slides van een presentatie met aangepaste schaal. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Retourneert een Slide, MasterSlide of LayoutSlide op basis van Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea's in alle toegestane vormen in alle slides. |
| [RefreshChartsData](../../aspose.slides/ipresentation/refreshchartsdata)(bool) | Laadt de gegevens voor alle diagrammen in de presentatie opnieuw vanuit hun bron-werkboeken. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Slaat alle slides van een presentatie op naar een reeks bestanden die XAML-markup vertegenwoordigen. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Slaat alle slides van een presentatie op naar een stream in het opgegeven formaat. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Slaat alle slides van een presentatie op naar een bestand met het opgegeven formaat. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Slaat opgegeven slides van een presentatie op naar een stream in het opgegeven formaat. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Slaat alle slides van een presentatie op naar een stream in het opgegeven formaat en met extra opties. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Slaat opgegeven slides van een presentatie op naar een bestand met het opgegeven formaat. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Slaat alle slides van een presentatie op naar een bestand met het opgegeven formaat en met extra opties. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Slaat opgegeven slides van een presentatie op naar een stream in het opgegeven formaat. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Slaat opgegeven slides van een presentatie op naar een bestand met het opgegeven formaat. |

### Zie ook

* interface [IPresentationComponent](../ipresentationcomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->