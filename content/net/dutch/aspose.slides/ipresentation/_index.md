---
title: IPresentation
second_title: Aspose.Sildes voor .NET API-referentie
description: Presentatiedocument
type: docs
weight: 6750
url: /nl/aspose.slides/ipresentation/
---
## IPresentation interface

Presentatiedocument

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Geeft alle aangepaste gegevensonderdelen in de presentatie terug. Alleen-lezen [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Geeft IDisposable interface terug. Alleen-lezen IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Staat toe de basis IPresentationComponent interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Geeft de collectie van alle ingesloten audiobestanden in de presentatie terug. Alleen-lezen [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Geeft de collectie van commentaarauteurs terug. Alleen-lezen [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Geeft de datum en tijd terug of stelt deze in die de inhoud van datetime-velden zal vervangen. Tijd van de creatie van dit Presentation-object standaard. Lezen/Schrijven DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Geeft de aangepaste gegevens van de presentatie terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Geeft de standaardtekststijl voor vormen terug. Alleen-lezen [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Geeft de collectie van handtekeningen die gebruikt werden om de presentatie te ondertekenen terug. Alleen-lezen [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Geeft DocumentProperties-object terug dat standaard- en aangepaste documenteigenschappen bevat. Alleen-lezen [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Stelt het eerste dia-nummer in de presentatie voor. Lezen/Schrijven Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Geeft de fontsmanager terug. Alleen-lezen [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Geeft de HeaderFooter-manager van de presentatie terug. Alleen-lezen [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Biedt eenvoudige toegang tot alle hyperlinks die in de presentatiedia's voorkomen (niet in master-, lay-out- en notitieslides). Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Geeft de collectie van alle afbeeldingen in de presentatie terug. Alleen-lezen [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Geeft een lijst van alle lay-outdia's die in de presentatie zijn gedefinieerd terug. Alleen-lezen [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Geeft de handout master-manager terug. Alleen-lezen [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Geeft de notities master-manager terug. Alleen-lezen [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Geeft een lijst van alle masterdia's die in de presentatie zijn gedefinieerd terug. Alleen-lezen [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Geeft het masterthema van de presentatie terug. Alleen-lezen [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Geeft het object voor de grootte van notitieslides terug. Alleen-lezen [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Verkrijgt de manager van de rechten voor deze presentatie. Alleen-lezen [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Geeft een lijst van alle dia-secties die in de presentatie zijn gedefinieerd terug. Alleen-lezen [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Geeft de collectie van gevoeligheidslabels die op het presentatiedocument zijn toegepast terug. Alleen-lezen [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Geeft een lijst van alle dia's die in de presentatie zijn gedefinieerd terug. Alleen-lezen [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Geeft het object voor dia-afmeting terug. Alleen-lezen [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Geeft informatie over het formaat waaruit de presentatie is geladen terug. Alleen-lezen [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Verkrijgt het VBA-project met presentatiemacro's. Lezen/Schrijven [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Geeft de collectie van alle ingesloten videobestanden in de presentatie terug. Alleen-lezen [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Verkrijgt de weergave-eigenschappen die gelden voor de volledige presentatie. Alleen-lezen [`IViewProperties`](../iviewproperties). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Geeft miniatuurafbeeldingsobjecten terug voor alle dia's van een presentatie. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Geeft miniatuur-Bitmap-objecten terug voor opgegeven dia's van een presentatie. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Geeft miniatuurafbeeldingsobjecten terug voor alle dia's van een presentatie met opgegeven grootte. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Geeft miniatuurafbeeldingsobjecten terug voor alle dia's van een presentatie met aangepaste schaal. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Geeft miniatuurafbeeldingsobjecten terug voor opgegeven dia's van een presentatie met opgegeven grootte. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Geeft miniatuurafbeeldingsobjecten terug voor opgegeven dia's van een presentatie met aangepaste schaal. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Geeft een Slide, MasterSlide of LayoutSlide terug op basis van Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea's in alle toepasselijke vormen in alle dia's. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Vervangt alle voorkomen van de opgegeven tekst door een andere opgegeven tekst. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Slaat alle dia's van een presentatie op in een reeks bestanden die XAML-markup vertegenwoordigen. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat en met extra opties. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat en met extra opties. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat. |

### Zie ook

* interface [IPresentationComponent](../ipresentationcomponent)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->