---
title: Presentation
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en Microsoft PowerPoint-presentation.
type: docs
weight: 9590
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
| [Presentation](presentation#constructor)() | Den här konstruktorn skapar en ny presentation från grunden. Den skapade presentationen har en tom bild. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Den här konstruktorn skapar en ny presentation från grunden. Den skapade presentationen har en tom bild. |
| [Presentation](presentation#constructor_2)(Stream) | Den här konstruktorn är det primära sättet att läsa en befintlig Presentation. |
| [Presentation](presentation#constructor_4)(string) | Den här konstruktorn får en sökväg till källfilen varifrån innehållet i Presentationen läses. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Den här konstruktorn är det primära sättet att läsa en befintlig Presentation. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Den här konstruktorn får en sökväg till källfilen varifrån innehållet i Presentationen läses. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Returnerar alla anpassade dataparts i presentationen. Skrivskyddad [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Returnerar samlingen av alla inbäddade ljudfiler i presentationen. Skrivskyddad [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Returnerar samlingen av kommentarsförfattare. Skrivskyddad [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Returnerar eller anger datum och tid som kommer att ersätta innehållet i datum-tidsfält. Standard är den tid då detta Presentation-objekt skapades. Läs/skriv DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Returnerar presentationens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Returnerar standardtextstil för former. Skrivskyddad [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Returnerar samlingen av signaturer som används för att signera presentationen. Skrivskyddad [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Returnerar DocumentProperties-objekt som innehåller standard- och anpassade dokumentegenskaper. Skrivskyddad [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Representerar det första bildnumret i presentationen |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Returnerar teckensnittshanterare. Skrivskyddad [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Returnerar aktuell HeaderFooter-hanterare. Skrivskyddad [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Ger enkel åtkomst till alla hyperlänkar i alla presentationsbilder (inte i master-, layout- eller noteringsbilder). Skrivskyddad [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Returnerar samlingen av alla bilder i presentationen. Skrivskyddad [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Returnerar en lista över alla layout-bilder som definierats i presentationen. Skrivskyddad [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Returnerar handout-master-hanterare. Skrivskyddad [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Returnerar notes-master-hanterare. Skrivskyddad [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Returnerar en lista över alla master-bilder som definierats i presentationen. Skrivskyddad [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Returnerar master-tema. Skrivskyddad [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Returnerar objekt för noteringsbildens storlek. Skrivskyddad [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Hämtar hanterare för behörigheter för denna presentation. Skrivskyddad [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Returnerar en lista över alla bildsektioner som definierats i presentationen. Skrivskyddad [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Returnerar samlingen av känslighetsetiketter som tillämpats på presentationsdokumentet. Skrivskyddad [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Returnerar en lista över alla bilder som definierats i presentationen. Skrivskyddad [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Returnerar bildspelsinställningarna för presentationen. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Returnerar objekt för bildstorlek. Skrivskyddad [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Returnerar information om från vilket format presentationen laddades. Skrivskyddad [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Hämtar eller anger VBA-projekt med presentationsmakron. Läs/skriv [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Returnerar samlingen av alla inbäddade videofiler i presentationen. Skrivskyddad [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Hämtar vy-egenskaper för hela presentationen. Skrivskyddad [`IViewProperties`](../iviewproperties). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Frigör alla resurser som används av detta Presentation-objekt. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Returnerar bildobjekt för alla bilder i en presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Returnerar miniatyrbildobjekt för angivna bilder i en presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Returnerar miniatyrbildobjekt för alla bilder i en presentation med angiven storlek. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Returnerar miniatyrbildobjekt för alla bilder i en presentation med anpassad skalning. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Returnerar miniatyrbildobjekt för angivna bilder i en presentation med angiven storlek. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Returnerar miniatyrbildobjekt för angivna bilder i en presentation med anpassad skalning. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Returnerar en Slide, MasterSlide eller LayoutSlide efter Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Markerar alla matchningar av reguljära uttrycket med den angivna färgen. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Markerar alla matchningar av provtexten med den angivna färgen. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Markerar alla matchningar av provtexten med den angivna färgen. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Sammanfogar löp med samma formatering i alla stycken i alla lämpliga former i alla bilder. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Ersätter alla matchningar av reguljära uttrycket med den angivna strängen. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Sparar alla bilder i en presentation till ett antal filer som representerar XAML-markup. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Sparar alla bilder i en presentation till en ström i det angivna formatet. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Sparar alla bilder i en presentation till en fil med det angivna formatet. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Sparar angivna bilder i en presentation till en ström i det angivna formatet med sidnummer bevarat. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Sparar alla bilder i en presentation till en ström i det angivna formatet och med ytterligare alternativ. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Sparar angivna bilder i en presentation till en fil med det angivna formatet med sidnummer bevarat. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Sparar angivna bilder i en presentation till en ström i det angivna formatet med sidnummer bevarat. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Sparar angivna bilder i en presentation till en fil med det angivna formatet med sidnummer bevarat. |

### Exempel

Följande exempel visar hur man skapar en PowerPoint-Presentation.

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
// Ladda vilken som helst stödjande fil i Presentation t.ex. ppt, pptx, odp osv.
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