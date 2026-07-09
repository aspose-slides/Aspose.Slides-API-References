---
title: IPresentation
second_title: Aspose.Sildes för .NET API-referens
description: Presentationsdokument
type: docs
weight: 6750
url: /sv/aspose.slides/ipresentation/
---
## IPresentation gränssnitt

Presentationsdokument

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Egenskaper

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Returnerar alla anpassade datadelar i presentationen. Skrivskyddad [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Returnerar IDisposable-gränssnittet. Skrivskyddad IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Tillåter att hämta bas-IPresentationComponent-gränssnittet. Skrivskyddad [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Returnerar samlingen av alla inbäddade ljudfiler i presentationen. Skrivskyddad [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Returnerar samlingen av kommentar-författare. Skrivskyddad [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält. Tid för detta Presentation-objekts skapande som standard. Läs/skriv DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Returnerar presentationens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Returnerar standardtextstil för former. Skrivskyddad [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Returnerar samlingen av signaturer som används för att signera presentationen. Skrivskyddad [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Returnerar DocumentProperties-objekt som innehåller standard- och anpassade dokumentegenskaper. Skrivskyddad [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Representerar det första bildnumret i presentationen. Läs/skriv Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Returnerar teckensnittshanterare. Skrivskyddad [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Returnerar HeaderFooter-hanterare för presentationen. Skrivskyddad [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Tillhandahåller enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (ej i master-, layout- eller notbild-bilder). Skrivskyddad [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Returnerar samlingen av alla bilder i presentationen. Skrivskyddad [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Returnerar en lista över alla layout-bilder som definierats i presentationen. Skrivskyddad [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Returnerar handout-master-hanterare. Skrivskyddad [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Returnerar notes-master-hanterare. Skrivskyddad [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Returnerar en lista över alla master-bilder som definierats i presentationen. Skrivskyddad [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Returnerar master-tema för presentationen. Skrivskyddad [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Returnerar notes-bildstorleks-objekt. Skrivskyddad [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Hämtar hanterare för behörigheter för denna presentation. Skrivskyddad [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Returnerar en lista över alla bildsektioner som definierats i presentationen. Skrivskyddad [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Returnerar samlingen av känslighets-etiketter som tillämpats på presentationsdokumentet. Skrivskyddad [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Returnerar en lista över alla bilder som definierats i presentationen. Skrivskyddad [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Returnerar bildstorleks-objekt. Skrivskyddad [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Returnerar information om från vilket format presentationen laddades. Skrivskyddad [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Hämtar VBA-projekt med presentations-makron. Läs/skriv [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Returnerar samlingen av alla inbäddade videofiler i presentationen. Skrivskyddad [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Hämtar presentationsomfattande vy-egenskaper. Skrivskyddad [`IViewProperties`](../iviewproperties). |

## Metoder

| Name | Description |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Returnerar en Thumbnail Image-objekt för alla bilder i en presentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Returnerar en Thumbnail Bitmap-objekt för specificerade bilder i en presentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Returnerar en Thumbnail Image-objekt för alla bilder i en presentation med angiven storlek. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Returnerar en Thumbnail Image-objekt för alla bilder i en presentation med anpassad skalning. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Returnerar en Thumbnail Image-objekt för specificerade bilder i en presentation med angiven storlek. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Returnerar en Thumbnail Image-objekt för specificerade bilder i en presentation med anpassad skalning. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Returnerar en Slide, MasterSlide eller LayoutSlide efter Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Markerar alla matchningar av reguljära uttrycket med den angivna färgen. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Sammanfogar körningar med samma formatering i alla stycken i alla accepterade former i alla bilder. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Ersätter alla matchningar av reguljära uttrycket med den angivna strängen. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Sparar alla bilder i en presentation till en ström i angivet format. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Sparar alla bilder i en presentation till en fil med angivet format. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Sparar specificerade bilder i en presentation till en ström i angivet format. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Sparar alla bilder i en presentation till en ström i angivet format och med ytterligare alternativ. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Sparar specificerade bilder i en presentation till en fil med angivet format. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Sparar alla bilder i en presentation till en fil med angivet format och med ytterligare alternativ. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Sparar specificerade bilder i en presentation till en ström i angivet format. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Sparar specificerade bilder i en presentation till en fil med angivet format. |

### Se även

* gränssnitt [IPresentationComponent](../ipresentationcomponent)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->