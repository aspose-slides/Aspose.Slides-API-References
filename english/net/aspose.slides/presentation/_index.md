---
title: Presentation
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 8860
url: /net/aspose.slides/presentation/
---
## Presentation class

Represents a Microsoft PowerPoint presentation.

```csharp
public sealed class Presentation : IPresentation
```

## Constructors

| Name | Description |
| --- | --- |
| [Presentation](presentation)() | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
| [Presentation](presentation)(LoadOptions) | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
| [Presentation](presentation)(Stream) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation](presentation)(string) | This constructor gets a source file path from which the contents of the Presentation are read. |
| [Presentation](presentation)(Stream, LoadOptions) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation](presentation)(string, LoadOptions) | This constructor gets a source file path from which the contents of the Presentation are read. |

## Properties

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](allcustomxmlparts) { get; } | Returns all custom data parts in the presentaion. Read-only [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](audios) { get; } | Returns the collection of all embedded audio files in the presentation. Read-only [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](commentauthors) { get; } | Returns the collection of comments autors. Read-only [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](currentdatetime) { get; set; } | Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write DateTime. |
| [CustomData](customdata) { get; } | Returns the presentation's custom data. Read-only [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](defaulttextstyle) { get; } | Returns default text style for shapes. Read-only [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](digitalsignatures) { get; } | Returns the collection of signatures used to sign the presentation. Read-only [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](documentproperties) { get; } | Returns DocumentProperties object which contains standard and custom document properties. Read-only [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](firstslidenumber) { get; set; } | Represents the first slide number in the presentation |
| [FontsManager](fontsmanager) { get; } | Returns fonts manager. Read-only [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](headerfootermanager) { get; } | Returns actual HeaderFooter manager. Read-only [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](hyperlinkqueries) { get; } | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](images) { get; } | Returns the collection of all images in the presentation. Read-only [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](layoutslides) { get; } | Returns a list of all layout slides that are defined in the presentation. Read-only [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](masterhandoutslidemanager) { get; } | Returns handout master manager. Read-only [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](masternotesslidemanager) { get; } | Returns notes master manager. Read-only [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](masters) { get; } | Returns a list of all master slides that are defined in the presentation. Read-only [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](mastertheme) { get; } | Returns master theme. Read-only [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](notessize) { get; } | Returns notes slide size object. Read-only [`INotesSize`](../inotessize). |
| [ProtectionManager](protectionmanager) { get; } | Gets manager of the permissions for this presentation. Read-only [`IProtectionManager`](../iprotectionmanager). |
| [Sections](sections) { get; } | Returns a list of all slides sections that are defined in the presentation. Read-only [`ISectionCollection`](../isectioncollection). |
| [Slides](slides) { get; } | Returns a list of all slides that are defined in the presentation. Read-only [`ISlideCollection`](../islidecollection). |
| [SlideSize](slidesize) { get; } | Returns slide size object. Read-only [`ISlideSize`](../islidesize). |
| [SourceFormat](sourceformat) { get; } | Returns information about from which format presentation was loaded. Read-only [`SourceFormat`](../sourceformat). |
| [VbaProject](vbaproject) { get; set; } | Gets or sets VBA project with presentation macros. Read/write [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](videos) { get; } | Returns the collection of all embedded video files in the presentation. Read-only [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](viewproperties) { get; } | Gets presentation wide view properties. Read-only [`IViewProperties`](../iviewproperties). |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](dispose)() | Releases all resources used by this Presentation object. |
| [GetSlideById](getslidebyid)(uint) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [GetThumbnails](getthumbnails)(IRenderingOptions) | Returns a Thumbnail Bitmap objects for all slides of a presentation. |
| [GetThumbnails](getthumbnails)(IRenderingOptions, int[]) | Returns a Thumbnail Bitmap objects for specified slides of a presentation. |
| [GetThumbnails](getthumbnails)(IRenderingOptions, Size) | Returns a Thumbnail Bitmap objects for all slides of a presentation with specified size. |
| [GetThumbnails](getthumbnails)(IRenderingOptions, float, float) | Returns a Thumbnail Bitmap objects for all slides of a presentation with custom scaling. |
| [GetThumbnails](getthumbnails)(IRenderingOptions, int[], Size) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size. |
| [GetThumbnails](getthumbnails)(IRenderingOptions, int[], float, float) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with custom scaling. |
| [JoinPortionsWithSameFormatting](joinportionswithsameformatting)() | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [Print](print)() | Prints the whole presentation to the default printer. |
| [Print](print)(PrinterSettings) | Prints the presentation according to the specified printer settings, using the standard (no User Interface) print controller. |
| [Print](print)(string) | Print the whole presentation to the specified printer, using the standard (no User Interface) print controller. |
| [Print](print)(PrinterSettings, string) | Prints the document according to the specified printer settings, using the standard (no User Interface) print controller and a presentation name. |
| [Save](save)(IXamlOptions) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [Save](save)(Stream, SaveFormat) | Saves all slides of a presentation to a stream in the specified format. |
| [Save](save)(string, SaveFormat) | Saves all slides of a presentation to a file with the specified format. |
| [Save](save)(Stream, int[], SaveFormat) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [Save](save)(Stream, SaveFormat, ISaveOptions) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [Save](save)(string, int[], SaveFormat) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [Save](save)(string, SaveFormat, ISaveOptions) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [Save](save)(Stream, int[], SaveFormat, ISaveOptions) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [Save](save)(string, int[], SaveFormat, ISaveOptions) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### See Also

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
