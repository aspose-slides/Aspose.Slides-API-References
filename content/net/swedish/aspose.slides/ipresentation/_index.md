---
title: IPresentation
second_title: Aspose.Sildes för .NET API-referens
description: Presentationsdokument
type: docs
weight: 6770
url: /sv/aspose.slides/ipresentation/
---
## IPresentation gränssnitt

Presentation document

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Egenskaper

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Returnerar alla anpassade datadelar i presentationen. Skrivskyddad [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Returnerar IDisposable-gränssnitt. Skrivskyddad IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Gör det möjligt att hämta bas-IPresentationComponent-gränssnitt. Skrivskyddad [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Returnerar samlingen av alla inbäddade ljudfiler i presentationen. Skrivskyddad [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Returnerar samlingen av kommentarsförfattare. Skrivskyddad [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Returnerar eller anger datum och tid som kommer ersätta innehållet i datumtidsfält. Tid för detta Presentation-objekts skapande som standard. Läs/skriv DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Returnerar presentationens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Returnerar standardtextstil för former. Skrivskyddad [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Returnerar samlingen av signaturer som används för att signera presentationen. Skrivskyddad [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Returnerar DocumentProperties-objektet som innehåller standard- och anpassade dokumentegenskaper. Skrivskyddad [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Representerar det första bildnumret i presentationen. Läs/skriv Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Returnerar teckensnittshanteraren. Skrivskyddad [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Returnerar HeaderFooter-hanteraren för presentationen. Skrivskyddad [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Ger enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (ej i grund-, layout- eller noteringsbilder). Skrivskyddad [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Returnerar samlingen av alla bilder i presentationen. Skrivskyddad [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Returnerar en lista över alla layoutbilder som definieras i presentationen. Skrivskyddad [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Returnerar handout-grundhanteraren. Skrivskyddad [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Returnerar noterings-grundhanteraren. Skrivskyddad [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Returnerar en lista över alla grundbilder som definieras i presentationen. Skrivskyddad [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Returnerar huvudtema för presentationen. Skrivskyddad [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Returnerar objektet för noteringsbildens storlek. Skrivskyddad [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Hämtar hanteraren för behörigheterna för denna presentation. Skrivskyddad [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Returnerar en lista över alla bildsektioner som definieras i presentationen. Skrivskyddad [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Returnerar samlingen av känslighetsetiketter som tillämpas på presentationsdokumentet. Skrivskyddad [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Returnerar en lista över alla bilder som definieras i presentationen. Skrivskyddad [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Returnerar bildstorleksobjektet. Skrivskyddad [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Returnerar information om från vilket format presentationen laddades. Skrivskyddad [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Hämtar VBA-projektet med presentationsmakron. Läs/skriv [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Returnerar samlingen av alla inbäddade videofiler i presentationen. Skrivskyddad [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Hämtar presentationsomfattande vyegenskaper. Skrivskyddad [`IViewProperties`](../iviewproperties). |

## Metoder

| Name | Description |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Returnerar ett miniatyrbilds-Image-objekt för alla bilder i en presentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Returnerar ett miniatyr-Bitmap-objekt för angivna bilder i en presentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Returnerar ett miniatyr-Image-objekt för alla bilder i en presentation med angiven storlek. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Returnerar ett miniatyr-Image-objekt för alla bilder i en presentation med anpassad skalning. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Returnerar ett miniatyr-Image-objekt för angivna bilder i en presentation med angiven storlek. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Returnerar ett miniatyr-Image-objekt för angivna bilder i en presentation med anpassad skalning. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Returnerar en Slide, MasterSlide eller LayoutSlide enligt Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Markerar alla träffar av reguljära uttrycket med den angivna färgen. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Sammanfogar körningar med samma formatering i alla stycken i alla godkända former i alla bilder. |
| [RefreshChartsData](../../aspose.slides/ipresentation/refreshchartsdata)(bool) | Laddar om data för alla diagram i presentationen från deras källarbetsböcker. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Ersätter alla träffar av reguljära uttrycket med den angivna strängen. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Sparar alla bilder i en presentation till en ström i det angivna formatet. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Sparar alla bilder i en presentation till en fil med det angivna formatet. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Sparar angivna bilder i en presentation till en ström i det angivna formatet. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Sparar alla bilder i en presentation till en ström i det angivna formatet och med ytterligare alternativ. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Sparar angivna bilder i en presentation till en fil med det angivna formatet. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Sparar alla bilder i en presentation till en fil med det angivna formatet och med ytterligare alternativ. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Sparar angivna bilder i en presentation till en ström i det angivna formatet. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Sparar angivna bilder i en presentation till en fil med det angivna formatet. |

### Se även

* gränssnitt [IPresentationComponent](../ipresentationcomponent)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->