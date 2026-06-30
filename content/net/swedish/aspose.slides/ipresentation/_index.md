---
title: IPresentation
second_title: Aspose.Sildes för .NET API-referens
description: Presentationsdokument
type: docs
weight: 6730
url: /sv/aspose.slides/ipresentation/
---
## IPresentation gränssnitt

Presentationsdokument

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Returnerar alla anpassade dataparts i presentationen. Skrivskyddad [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Returnerar IDisposable-gränssnittet. Skrivskyddad IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Tillåter att hämta bas-IPresentationComponent-gränssnittet. Skrivskyddad [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Returnerar samlingen av alla inbäddade ljudfiler i presentationen. Skrivskyddad [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Returnerar samlingen av kommentarförfattare. Skrivskyddad [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält. Tid för skapandet av detta Presentation-objekt som standard. Läs/skriv DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Returnerar presentationens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Returnerar standardtextstilen för former. Skrivskyddad [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Returnerar samlingen av signaturer som används för att signera presentationen. Skrivskyddad [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Returnerar DocumentProperties-objektet som innehåller standard- och anpassade dokumentegenskaper. Skrivskyddad [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Representerar det första bildnumret i presentationen. Läs/skriv Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Returnerar teckensnittshanteraren. Skrivskyddad [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Returnerar HeaderFooter-hanteraren för presentationen. Skrivskyddad [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Erbjuder enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (ej i master-, layout- och noterbilder). Skrivskyddad [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Returnerar samlingen av alla bilder i presentationen. Skrivskyddad [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Returnerar en lista med alla layoutbilder som definierats i presentationen. Skrivskyddad [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Returnerar handout-master-hanteraren. Skrivskyddad [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Returnerar notes-master-hanteraren. Skrivskyddad [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Returnerar en lista med alla masterbilder som definierats i presentationen. Skrivskyddad [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Returnerar mastertema för presentationen. Skrivskyddad [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Returnerar objektet för notisbildens storlek. Skrivskyddad [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Hämtar hanteraren för behörigheter för denna presentation. Skrivskyddad [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Returnerar en lista med alla bildsektioner som definierats i presentationen. Skrivskyddad [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Returnerar samlingen av känslighetsetiketter som tillämpats på presentationsdokumentet. Skrivskyddad [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Returnerar en lista med alla bilder som definierats i presentationen. Skrivskyddad [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Returnerar bildstorleksobjektet. Skrivskyddad [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Returnerar information om från vilket format presentationen laddades. Skrivskyddad [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Hämtar VBA-projektet med presentationsmakron. Läs/skriv [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Returnerar samlingen av alla inbäddade videofiler i presentationen. Skrivskyddad [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Hämtar presentationsomfattande vyegenskaper. Skrivskyddad [`IViewProperties`](../iviewproperties). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Returnerar Thumbnail Image-objekt för alla bilder i en presentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Returnerar Thumbnail Bitmap-objekt för angivna bilder i en presentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Returnerar Thumbnail Image-objekt för alla bilder i en presentation med angiven storlek. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Returnerar Thumbnail Image-objekt för alla bilder i en presentation med anpassad skalning. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Returnerar Thumbnail Image-objekt för angivna bilder i en presentation med angiven storlek. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Returnerar Thumbnail Image-objekt för angivna bilder i en presentation med anpassad skalning. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Returnerar en Slide, MasterSlide eller LayoutSlide enligt Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Markerar alla träffar av det reguljära uttrycket med den angivna färgen. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Slår ihop körningar med samma formatering i alla stycken i alla accepterade former i alla bilder. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Ersätter alla träffar av det reguljära uttrycket med den angivna strängen. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Sparar alla bilder i en presentation till en ström i det angivna formatet. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Sparar alla bilder i en presentation till en fil med det angivna formatet. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Sparar angivna bilder i en presentation till en ström i det angivna formatet. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Sparar alla bilder i en presentation till en ström i det angivna formatet och med extra alternativ. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Sparar angivna bilder i en presentation till en fil med det angivna formatet. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Sparar alla bilder i en presentation till en fil med det angivna formatet och med extra alternativ. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Sparar angivna bilder i en presentation till en ström i det angivna formatet. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Sparar angivna bilder i en presentation till en fil med det angivna formatet. |

### Se även

* gränssnitt [IPresentationComponent](../ipresentationcomponent)
* namnrymd [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->