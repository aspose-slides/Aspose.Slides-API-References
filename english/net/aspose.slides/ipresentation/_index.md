---
title: IPresentation
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 6190
url: /net/aspose.slides/ipresentation/
---
## IPresentation interface

Presentation document

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Properties

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](allcustomxmlparts) { get; } | Returns all custom data parts in the presentaion. Read-only [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](asidisposable) { get; } | Returns IDisposable interface. Read-only IDisposable. |
| [AsIPresentationComponent](asipresentationcomponent) { get; } | Allows to get base IPresentationComponent interface. Read-only [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](audios) { get; } | Returns the collection of all embedded audio files in the presentation. Read-only [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](commentauthors) { get; } | Returns the collection of comments autors. Read-only [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](currentdatetime) { get; set; } | Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write DateTime. |
| [CustomData](customdata) { get; } | Returns the presentation's custom data. Read-only [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](defaulttextstyle) { get; } | Returns default text style for shapes. Read-only [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](digitalsignatures) { get; } | Returns the collection of signatures used to sign the presentation. Read-only [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](documentproperties) { get; } | Returns DocumentProperties object which contains standard and custom document properties. Read-only [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](firstslidenumber) { get; set; } | Represents the first slide number in the presentation. Read/write Int32. |
| [FontsManager](fontsmanager) { get; } | Returns fonts manager. Read-only [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](headerfootermanager) { get; } | Returns HeaderFooter manager of the presentation. Read-only [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](hyperlinkqueries) { get; } | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](images) { get; } | Returns the collection of all images in the presentation. Read-only [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](layoutslides) { get; } | Returns a list of all layout slides that are defined in the presentation. Read-only [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](masterhandoutslidemanager) { get; } | Returns handout master manager. Read-only [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](masternotesslidemanager) { get; } | Returns notes master manager. Read-only [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](masters) { get; } | Returns a list of all master slides that are defined in the presentation. Read-only [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](mastertheme) { get; } | Returns master theme of the presentation. Read-only [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](notessize) { get; } | Returns notes slide size object. Read-only [`INotesSize`](../inotessize). |
| [ProtectionManager](protectionmanager) { get; } | Gets manager of the permissions for this presentation. Read-only [`IProtectionManager`](../iprotectionmanager). |
| [Sections](sections) { get; } | Returns a list of all slides sections that are defined in the presentation. Read-only [`ISectionCollection`](../isectioncollection). |
| [Slides](slides) { get; } | Returns a list of all slides that are defined in the presentation. Read-only [`ISlideCollection`](../islidecollection). |
| [SlideSize](slidesize) { get; } | Returns slide size object. Read-only [`ISlideSize`](../islidesize). |
| [SourceFormat](sourceformat) { get; } | Returns information about from which format presentation was loaded. Read-only [`SourceFormat`](./sourceformat). |
| [VbaProject](vbaproject) { get; set; } | Gets VBA project with presentation macros. Read/write [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](videos) { get; } | Returns the collection of all embedded video files in the presentation. Read-only [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](viewproperties) { get; } | Gets presentation wide view properties. Read-only [`IViewProperties`](../iviewproperties). |

## Methods

| Name | Description |
| --- | --- |
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
| [Save](save)(Stream, int[], SaveFormat) | Saves specified slides of a presentation to a stream in the specified format. |
| [Save](save)(Stream, SaveFormat, ISaveOptions) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [Save](save)(string, int[], SaveFormat) | Saves specified slides of a presentation to a file with the specified format. |
| [Save](save)(string, SaveFormat, ISaveOptions) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [Save](save)(Stream, int[], SaveFormat, ISaveOptions) | Saves specified slides of a presentation to a stream in the specified format. |
| [Save](save)(string, int[], SaveFormat, ISaveOptions) | Saves specified slides of a presentation to a file with the specified format. |

### See Also

* interface [IPresentationComponent](../ipresentationcomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
