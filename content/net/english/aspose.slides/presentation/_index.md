---
title: Presentation
second_title: Aspose.Sildes for .NET API Reference
description: Represents a Microsoft PowerPoint presentation.
type: docs
weight: 9150
url: /aspose.slides/presentation/
---

## Presentation class

Represents a Microsoft PowerPoint presentation.

```csharp
public sealed class Presentation : IPresentation
```

## Constructors

| Name | Description |
| --- | --- |
| [Presentation](presentation#constructor)() | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
| [Presentation](presentation#constructor_1)(LoadOptions) | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
| [Presentation](presentation#constructor_2)(Stream) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation](presentation#constructor_4)(string) | This constructor gets a source file path from which the contents of the Presentation are read. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | This constructor gets a source file path from which the contents of the Presentation are read. |

## Properties

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Returns all custom data parts in the presentaion. Read-only [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Returns the collection of all embedded audio files in the presentation. Read-only [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Returns the collection of comments autors. Read-only [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Returns the presentation's custom data. Read-only [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Returns default text style for shapes. Read-only [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Returns the collection of signatures used to sign the presentation. Read-only [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Returns DocumentProperties object which contains standard and custom document properties. Read-only [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Represents the first slide number in the presentation |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Returns fonts manager. Read-only [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Returns actual HeaderFooter manager. Read-only [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Returns the collection of all images in the presentation. Read-only [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Returns a list of all layout slides that are defined in the presentation. Read-only [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Returns handout master manager. Read-only [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Returns notes master manager. Read-only [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Returns a list of all master slides that are defined in the presentation. Read-only [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Returns master theme. Read-only [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Returns notes slide size object. Read-only [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Gets manager of the permissions for this presentation. Read-only [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Returns a list of all slides sections that are defined in the presentation. Read-only [`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Returns a list of all slides that are defined in the presentation. Read-only [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Returns the slide show settings for the presentation. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Returns slide size object. Read-only [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Returns information about from which format presentation was loaded. Read-only [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Gets or sets VBA project with presentation macros. Read/write [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Returns the collection of all embedded video files in the presentation. Read-only [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Gets presentation wide view properties. Read-only [`IViewProperties`](../iviewproperties). |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Releases all resources used by this Presentation object. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Returns a Image objects for all slides of a presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Returns a Thumbnail Image objects for specified slides of a presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Returns a Thumbnail Image objects for all slides of a presentation with specified size. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Returns a Thumbnail Image objects for all slides of a presentation with custom scaling. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Returns a Thumbnail Image objects for specified slides of a presentation with specified size. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Saves all slides of a presentation to a stream in the specified format. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Saves all slides of a presentation to a file with the specified format. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [Save](../../aspose.slides/presentation/save#save_9)(string, int[], SaveFormat) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [Save](../../aspose.slides/presentation/save#save_10)(string, int[], SaveFormat, ISaveOptions) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Examples

The following example shows how to create PowerPoint Presentation.

```csharp
[C#]
// Instantiate a Presentation object that represents a presentation file
using (Presentation presentation = new Presentation())
{
    // Get the first slide
    ISlide slide = presentation.Slides[0];
    // Add an autoshape of type line
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Save the presentation file.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

The following example shows how to open and save Presentation.

```csharp
[C#]
// Load any supported file in Presentation e.g. ppt, pptx, odp etc.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Save the presentation file.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
