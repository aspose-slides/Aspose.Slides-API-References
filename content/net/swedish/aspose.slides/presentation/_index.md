---
title: Presentation
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en Microsoft PowerPoint-presentation.
type: docs
weight: 9610
url: /sv/aspose.slides/presentation/
---
## Presentation klass

Representerar en Microsoft PowerPoint-presentation.

```csharp
public sealed class Presentation : IPresentation
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Presentation](presentation#constructor)() | Denna konstruktor skapar en ny presentation från grunden. Den skapade presentationen har en tom bild. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Denna konstruktor skapar en ny presentation från grunden. Den skapade presentationen har en tom bild. |
| [Presentation](presentation#constructor_2)(Stream) | Denna konstruktor är den primära mekanismen för att läsa en befintlig Presentation. |
| [Presentation](presentation#constructor_4)(string) | Denna konstruktor hämtar en källfilssökväg från vilken innehållet i Presentationen läses. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Denna konstruktor är den primära mekanismen för att läsa en befintlig Presentation. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Denna konstruktor hämtar en källfilssökväg från vilken innehållet i Presentationen läses. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Returnerar alla anpassade dataparts i presentationen. Skrivskyddad [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Returnerar samlingen av alla inbäddade ljudfiler i presentationen. Skrivskyddad [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Returnerar samlingen av kommentarsförfattare. Skrivskyddad [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Returnerar eller anger datum och tid som kommer att ersätta innehållet i datum/tid-fält. Standardvärdet är tidpunkten för skapandet av detta Presentation-objekt. Läs/skriv DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Returnerar presentationens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Returnerar standardtextstilen för former. Skrivskyddad [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Returnerar samlingen av signaturer som används för att signera presentationen. Skrivskyddad [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Returnerar DocumentProperties-objektet som innehåller standard- och anpassade dokumentegenskaper. Skrivskyddad [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Representerar det första bildnumret i presentationen. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Returnerar teckensnittsadministratören. Skrivskyddad [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Returnerar aktuell HeaderFooter-administratör. Skrivskyddad [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Tillhandahåller enkel åtkomst till alla hyperlänkar i alla presentationsbilder (ej i huvud-, layout- eller notbild). Skrivskyddad [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Returnerar samlingen av alla bilder i presentationen. Skrivskyddad [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Returnerar en lista över alla layoutbilder som definierats i presentationen. Skrivskyddad [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Returnerar handout-master-administratören. Skrivskyddad [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Returnerar notes-master-administratören. Skrivskyddad [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Returnerar en lista över alla masterslides som definierats i presentationen. Skrivskyddad [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Returnerar mastertema. Skrivskyddad [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Returnerar objektet för notes-bildstorlek. Skrivskyddad [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Returnerar hanteraren för behörigheter för denna presentation. Skrivskyddad [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Returnerar en lista över alla bildsektioner som definierats i presentationen. Skrivskyddad [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Returnerar samlingen av känslighetsetiketter som tillämpats på presentationsdokumentet. Skrivskyddad [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Returnerar en lista över alla bilder som definierats i presentationen. Skrivskyddad [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Returnerar bildspelsinställningarna för presentationen. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Returnerar bildstorleksobjektet. Skrivskyddad [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Returnerar information om från vilket format presentationen laddades. Skrivskyddad [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Hämtar eller anger VBA-projektet med presentationsmakron. Läs/skriv [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Returnerar samlingen av alla inbäddade videofiler i presentationen. Skrivskyddad [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Hämtar vyegenskaper för hela presentationen. Skrivskyddad [`IViewProperties`](../iviewproperties). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Frigör alla resurser som används av detta Presentation-objekt. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Returnerar Image-objekt för alla bilder i en presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Returnerar Thumbnail Image-objekt för angivna bilder i en presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Returnerar Thumbnail Image-objekt för alla bilder i en presentation med angiven storlek. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Returnerar Thumbnail Image-objekt för alla bilder i en presentation med anpassad skalning. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Returnerar Thumbnail Image-objekt för angivna bilder i en presentation med angiven storlek. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Returnerar Thumbnail Image-objekt för angivna bilder i en presentation med anpassad skalning. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Returnerar en Slide, MasterSlide eller LayoutSlide efter Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Markerar alla träffar av reguljära uttrycket med den angivna färgen. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Markerar alla förekomster av exempeltexten med den angivna färgen. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Markerar alla förekomster av exempeltexten med den angivna färgen. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Sammanfogar körningar med samma formatering i alla stycken i alla godkända former i alla bilder. |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | Laddar om data för alla diagram i presentationen från deras källarbok. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Ersätter alla träffar av reguljära uttrycket med den angivna strängen. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Sparar alla bilder i en presentation till en ström i det angivna formatet. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Sparar alla bilder i en presentation till en fil med det angivna formatet. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Sparar angivna bilder i en presentation till en ström i det angivna formatet med bevarade sidnummer. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Sparar alla bilder i en presentation till en ström i det angivna formatet och med ytterligare alternativ. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Sparar angivna bilder i en presentation till en fil med det angivna formatet med bevarade sidnummer. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Sparar angivna bilder i en presentation till en ström i det angivna formatet med bevarade sidnummer. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Sparar angivna bilder i en presentation till en fil med det angivna formatet med bevarade sidnummer. |

### Exempel

Följande exempel visar hur man skapar en PowerPoint-presentation.

```csharp
[C#]
// Skapa ett Presentation-objekt som representerar en presentationsfil
using (Presentation presentation = new Presentation())
{
    // Hämta den första bilden
    ISlide slide = presentation.Slides[0];
    // Lägg till en autoshape av typen linje
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Spara presentationsfilen.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Följande exempel visar hur man öppnar och sparar en Presentation.

```csharp
[C#]
// Läs in någon fil som stöds i Presentation, t.ex. ppt, pptx, odp osv.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Spara presentationsfilen.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Se även

* gränssnitt [IPresentation](../ipresentation)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->