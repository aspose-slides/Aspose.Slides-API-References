---
title: Presentation
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/presentation/
---

## Presentation class

  Represents a Microsoft PowerPoint presentation.
 
| [Presentation]() | This function creates new presentation from scratch. Created presentation has one empty slide. |

### Result
Presentation


---


| [Presentation]([LoadOptions]) | This function creates new presentation from scratch. Created presentation has one empty slide. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions] | Additional load options. |

### Result
Presentation


---


| [createPresentationFromStream ]([ReadStream], Function) | This function is the primary mechanism for reading an existing Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | [ReadStream] | Input stream. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Presentation |

### Result
Presentation


---


| [createPresentationFromStream ]([ReadStream], [LoadOptions], Function) | This function is the primary mechanism for reading an existing Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | [ReadStream] | Input stream. |
| loadOptions | [LoadOptions] | Additional load options. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Presentation |

### Result
Presentation


---


| [Presentation]([String]) | This function gets a source file path from which the contents of the Presentation are read. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| file | [String] | Input file. |

### Result
Presentation

### Error

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Thrown when input file has zero length |


---


| [Presentation]([String], [LoadOptions]) | This function gets a source file path from which the contents of the Presentation are read. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| file | [String] | Input file. |
| loadOptions | [LoadOptions] | Additional load options. |

### Result
Presentation

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when input file has zero length |


---


| [dispose] () Releases all resources used by this Presentation object. |


---


| [getAllCustomXmlParts] () Returns all custom data parts in the presentaion. Read-only ICustomXmlPart[]. |

### Result
[CustomXmlPart]


---


| [getAudios] () Returns the collection of all embedded audio files in the presentation. Read-only IAudioCollection. |

### Result
[AudioCollection]


---


| [getCommentAuthors] () Returns the collection of comments autors. Read-only ICommentAuthorCollection. |

### Result
[CommentAuthorCollection]


---


| [getCurrentDateTime] () Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date. |

### Result
Date


---


| [getCustomData] () Returns the presentation's custom data. Read-only ICustomData. |

### Result
[CustomData]


---


| [getDefaultTextStyle] () Returns default text style for shapes. Read-only ITextStyle. |

### Result
[TextStyle]


---


| [getDigitalSignatures] () Returns the collection of signatures used to sign the presentation. Read-only IDigitalSignatureCollection. |

### Result
[DigitalSignatureCollection]


---


| [getDocumentProperties] () Returns DocumentProperties object which contains standard and custom document properties. Read-only IDocumentProperties. |

### Result
[DocumentProperties]


---


| [getFirstSlideNumber] () Represents the first slide number in the presentation |

### Result
int


---


| [getFontsManager] () Returns fonts manager. Read-only IFontsManager. |

### Result
[FontsManager]


---


| [getHeaderFooterManager] () Returns actual HeaderFooter manager. Read-only IPresentationHeaderFooterManager. |

### Result
[PresentationHeaderFooterManager]


---


| [getHyperlinkQueries] () Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only IHyperlinkQueries. |

### Result
[HyperlinkQueries]


---


| [getImages] () Returns the collection of all images in the presentation. Read-only IImageCollection. |

### Result
[ImageCollection]


---


| [getLayoutSlides] () Returns a list of all layout slides that are defined in the presentation. Read-only IGlobalLayoutSlideCollection. You can access to alternative API for adding/inserting/removing/cloning layout slides by using IMasterSlide.LayoutSlides property. |

### Result
[GlobalLayoutSlideCollection]


---


| [getMasterHandoutSlideManager] () Returns handout master manager. Read-only IMasterHandoutSlideManager. |

### Result
[MasterHandoutSlideManager]


---


| [getMasterNotesSlideManager] () Returns notes master manager. Read-only IMasterNotesSlideManager. |

### Result
[MasterNotesSlideManager]


---


| [getMasterTheme] () Returns master theme. Read-only IMasterTheme. |

### Result
[MasterTheme]


---


| [getMasters] () Returns a list of all master slides that are defined in the presentation. Read-only IMasterSlideCollection. |

### Result
[MasterSlideCollection]


---


| [getNotesSize] () Returns notes slide size object. Read-only INotesSize. |

### Result
[NotesSize]


---


| [getPresentation] () Returns the parent presentation of a text. Read-only IPresentation. |

### Result
[Presentation]


---


| [getProtectionManager] () Gets manager of the permissions for this presentation. Read-only IProtectionManager. |

### Result
[ProtectionManager]


---


| [getSections] () Returns a list of all slides sections that are defined in the presentation. Read-only ISectionCollection. |

### Result
[SectionCollection]


---


| [getSlideById] ([long]) Returns a Slide, MasterSlide or LayoutSlide by Id. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| id | [long] | Id of a slide. |

### Result
[MasterNotesSlide], [MasterHandoutSlide], [BaseSlide], [NotesSlide], [LayoutSlide], [Slide], [MasterSlide]


---


| [getSlideShowSettings] () Returns the slide show settings for the presentation. |

### Result
SlideShowSettings


---


| [getSlideSize] () Returns slide size object. Read-only ISlideSize. |

### Result
[SlideSize]


---


| [getSlides] () Returns a list of all slides that are defined in the presentation. Read-only ISlideCollection. |

### Result
[SlideCollection]


---


| [getSourceFormat] () Returns information about from which format presentation was loaded. Read-only SourceFormat. |

### Result
int


---


| [getThumbnails] ([NotesCommentsLayoutingOptions]) Returns a Thumbnail BufferedImage objects for all slides of a presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions] | Options for notes and comments layouting. |

### Result
BufferedImage


---


| [getThumbnails] ([NotesCommentsLayoutingOptions], [int[]]) Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions] | Options for notes and comments layouting. |
| slides | [int[]] | Array with slide positions, starting from 1. |

### Result
BufferedImage


---


| [getThumbnails] ([NotesCommentsLayoutingOptions], [float], [float]) Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions] | Options for notes and comments layouting. |
| scaleX | [float] | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | [float] | The value by which to scale this Thumbnail in the y-axis direction. |

### Result
BufferedImage


---


| [getThumbnails] ([NotesCommentsLayoutingOptions], [int[]], [float], [float]) Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions] | Options for notes and comments layouting. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| scaleX | [float] | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | [float] | The value by which to scale this Thumbnail in the y-axis direction. |

### Result
BufferedImage


---


| [getThumbnails] ([NotesCommentsLayoutingOptions], [Dimension]) Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions] | Options for notes and comments layouting. |
| imageSize | [Dimension] | Size of the image to create. |

### Result
BufferedImage


---


| [getThumbnails] ([NotesCommentsLayoutingOptions], [int[]], [Dimension]) Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions] | Options for notes and comments layouting. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| imageSize | [Dimension] | Size of the image to create. |

### Result
BufferedImage


---


| [getThumbnails] ([RenderingOptions]) Returns a Thumbnail BufferedImage objects for all slides of a presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions] | Tiff options. |

### Result
BufferedImage


---


| [getThumbnails] ([RenderingOptions], [int[]]) Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions] | Tiff options. |
| slides | [int[]] | Array with slide positions, starting from 1. |

### Result
BufferedImage


---


| [getThumbnails] ([RenderingOptions], [float], [float]) Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions] | Tiff options. |
| scaleX | [float] | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | [float] | The value by which to scale this Thumbnail in the y-axis direction. |

### Result
BufferedImage


---


| [getThumbnails] ([RenderingOptions], [int[]], [float], [float]) Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions] | Tiff options. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| scaleX | [float] | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | [float] | The value by which to scale this Thumbnail in the y-axis direction. |

### Result
BufferedImage


---


| [getThumbnails] ([RenderingOptions], [Dimension]) Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions] | Tiff options. |
| imageSize | [Dimension] | Size of the image to create. |

### Result
BufferedImage


---


| [getThumbnails] ([RenderingOptions], [int[]], [Dimension]) Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions] | Tiff options. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| imageSize | [Dimension] | Size of the image to create. |

### Result
BufferedImage


---


| [getVbaProject] () Gets or sets VBA project with presentation macros. Read/write IVbaProject. |

### Result
[VbaProject]


---


| [getVideos] () Returns the collection of all embedded video files in the presentation. Read-only IVideoCollection. |

### Result
[VideoCollection]


---


| [getViewProperties] () Gets presentation wide view properties. Read-only IViewProperties. |

### Result
[ViewProperties]


---


| [joinPortionsWithSameFormatting] () Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |


---


| [save] ([String], [int]) Saves all slides of a presentation to a file with the specified format. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |


---


| [saveToStream ] (Presentation, [WriteStream], [int]) Saves all slides of a presentation to a stream in the specified format. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |


---


| [save] ([String], [int], [MarkdownSaveOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [MarkdownSaveOptions] | Additional format options. |


---


| [save] ([String], [int], [XamlOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [XamlOptions] | Additional format options. |


---


| [save] ([String], [int], [RenderingOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [RenderingOptions] | Additional format options. |


---


| [save] ([String], [int], [HtmlOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [HtmlOptions] | Additional format options. |


---


| [save] ([String], [int], [XpsOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [XpsOptions] | Additional format options. |


---


| [save] ([String], [int], [TiffOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [TiffOptions] | Additional format options. |


---


| [save] ([String], [int], [PptxOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [PptxOptions] | Additional format options. |


---


| [save] ([String], [int], [PptOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [PptOptions] | Additional format options. |


---


| [save] ([String], [int], [PdfOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [PdfOptions] | Additional format options. |


---


| [save] ([String], [int], [SwfOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [SwfOptions] | Additional format options. |


---


| [save] ([String], [int], [SVGOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [SVGOptions] | Additional format options. |


---


| [save] ([String], [int], [GifOptions]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [GifOptions] | Additional format options. |


---


| [save] ([String], [int], [Html5Options]) Saves all slides of a presentation to a file with the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| format | [int] | Format of the exported data. |
| options | [Html5Options] | Additional format options. |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [MarkdownSaveOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [MarkdownSaveOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [XamlOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [XamlOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [RenderingOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [RenderingOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [HtmlOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [HtmlOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [XpsOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [XpsOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [TiffOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [TiffOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [PptxOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [PptxOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [PptOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [PptOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [PdfOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [PdfOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [SwfOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [SwfOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [SVGOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [SVGOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [GifOptions]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [GifOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [saveToStream ] (Presentation, [WriteStream], [int], [Html5Options]) Saves all slides of a presentation to a stream in the specified format and with additional options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| format | [int] | Format of the exported data. |
| options | [Html5Options] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


| [save] ([XamlOptions]) Saves all slides of a presentation to a set of files representing XAML markup. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [XamlOptions] | The XAML format options. |


---


| [save] ([String], [int[]], [int]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [save] ([String], [int[]], [int], [MarkdownSaveOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [MarkdownSaveOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [XamlOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [XamlOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [RenderingOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [RenderingOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [HtmlOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [HtmlOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [XpsOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [XpsOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [TiffOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [TiffOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [PptxOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [PptxOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [PptOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [PptOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [PdfOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [PdfOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [SwfOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [SwfOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [SVGOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [SVGOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [GifOptions]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [GifOptions] | Additional format options. |


---


| [save] ([String], [int[]], [int], [Html5Options]) Saves specified slides of a presentation to a file with the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| fname | [String] | Path to the created file. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [Html5Options] | Additional format options. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [MarkdownSaveOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [MarkdownSaveOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [XamlOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [XamlOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [RenderingOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [RenderingOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [HtmlOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [HtmlOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [XpsOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [XpsOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [TiffOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [TiffOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [PptxOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [PptxOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [PptOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [PptOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [PdfOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [PdfOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [SwfOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [SwfOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [SVGOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [SVGOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [GifOptions]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [GifOptions] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [saveToStream ] (Presentation, [WriteStream], [int[]], [int], [Html5Options]) Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | [WriteStream] | Output stream. |
| slides | [int[]] | Array with slide positions, starting from 1. |
| format | [int] | Format of the exported data. |
| options | [Html5Options] | Additional format options. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


| [setCurrentDateTime] ([Date]) Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date. |


---


| [setFirstSlideNumber] ([int]) Represents the first slide number in the presentation |


---


| [setVbaProject] ([VbaProject]) Gets or sets VBA project with presentation macros. Read/write IVbaProject. |


---


