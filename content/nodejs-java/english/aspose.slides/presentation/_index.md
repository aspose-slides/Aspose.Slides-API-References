---
title: Presentation
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/presentation/
---

## Presentation class

  Represents a Microsoft PowerPoint presentation.
 
### Presentation {#Presentation}

| Name | Description |
| --- | --- |
| Presentation() | This function creates new presentation from scratch. Created presentation has one empty slide. |

 **Result:**
Presentation


---


### Presentation {#Presentation}

| Name | Description |
| --- | --- |
| Presentation([LoadOptions](../loadoptions)) | This function creates new presentation from scratch. Created presentation has one empty slide. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../loadoptions) | Additional load options. |

 **Result:**
Presentation


---


### createPresentationFromStream  {#createPresentationFromStream }

| Name | Description |
| --- | --- |
| createPresentationFromStream (ReadStream, Function) | This function is the primary mechanism for reading an existing Presentation. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | ReadStream | Input stream. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Presentation |

 **Result:**
Presentation


---


### createPresentationFromStream  {#createPresentationFromStream }

| Name | Description |
| --- | --- |
| createPresentationFromStream (ReadStream, [LoadOptions](../loadoptions), Function) | This function is the primary mechanism for reading an existing Presentation. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| stream | ReadStream | Input stream. |
| loadOptions | [LoadOptions](../loadoptions) | Additional load options. |
| callback | Function | callback(error, item) - Callback to be called when the class is created, item is the new instance of the Presentation |

 **Result:**
Presentation


---


### Presentation {#Presentation}

| Name | Description |
| --- | --- |
| Presentation(String) | This function gets a source file path from which the contents of the Presentation are read. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| file | String | Input file. |

 **Result:**
Presentation

 **Error**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Thrown when input file has zero length |


---


### Presentation {#Presentation}

| Name | Description |
| --- | --- |
| Presentation(String, [LoadOptions](../loadoptions)) | This function gets a source file path from which the contents of the Presentation are read. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| file | String | Input file. |
| loadOptions | [LoadOptions](../loadoptions) | Additional load options. |

 **Result:**
Presentation

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when input file has zero length |


---


### dispose {#dispose}

| Name | Description |
| --- | --- |
| dispose () | Releases all resources used by this Presentation object. |


---


### getAllCustomXmlParts {#getAllCustomXmlParts}

| Name | Description |
| --- | --- |
| getAllCustomXmlParts () | Returns all custom data parts in the presentaion. Read-only ICustomXmlPart[]. |

 **Result:**
[CustomXmlPart](../customxmlpart)


---


### getAudios {#getAudios}

| Name | Description |
| --- | --- |
| getAudios () | Returns the collection of all embedded audio files in the presentation. Read-only IAudioCollection. |

 **Result:**
[AudioCollection](../audiocollection)


---


### getCommentAuthors {#getCommentAuthors}

| Name | Description |
| --- | --- |
| getCommentAuthors () | Returns the collection of comments autors. Read-only ICommentAuthorCollection. |

 **Result:**
[CommentAuthorCollection](../commentauthorcollection)


---


### getCurrentDateTime {#getCurrentDateTime}

| Name | Description |
| --- | --- |
| getCurrentDateTime () | Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date. |

 **Result:**
Date


---


### getCustomData {#getCustomData}

| Name | Description |
| --- | --- |
| getCustomData () | Returns the presentation's custom data. Read-only ICustomData. |

 **Result:**
[CustomData](../customdata)


---


### getDefaultTextStyle {#getDefaultTextStyle}

| Name | Description |
| --- | --- |
| getDefaultTextStyle () | Returns default text style for shapes. Read-only ITextStyle. |

 **Result:**
[TextStyle](../textstyle)


---


### getDigitalSignatures {#getDigitalSignatures}

| Name | Description |
| --- | --- |
| getDigitalSignatures () | Returns the collection of signatures used to sign the presentation. Read-only IDigitalSignatureCollection. |

 **Result:**
[DigitalSignatureCollection](../digitalsignaturecollection)


---


### getDocumentProperties {#getDocumentProperties}

| Name | Description |
| --- | --- |
| getDocumentProperties () | Returns DocumentProperties object which contains standard and custom document properties. Read-only IDocumentProperties. |

 **Result:**
[DocumentProperties](../documentproperties)


---


### getFirstSlideNumber {#getFirstSlideNumber}

| Name | Description |
| --- | --- |
| getFirstSlideNumber () | Represents the first slide number in the presentation |

 **Result:**
int


---


### getFontsManager {#getFontsManager}

| Name | Description |
| --- | --- |
| getFontsManager () | Returns fonts manager. Read-only IFontsManager. |

 **Result:**
[FontsManager](../fontsmanager)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| Name | Description |
| --- | --- |
| getHeaderFooterManager () | Returns actual HeaderFooter manager. Read-only IPresentationHeaderFooterManager. |

 **Result:**
[PresentationHeaderFooterManager](../presentationheaderfootermanager)


---


### getHyperlinkQueries {#getHyperlinkQueries}

| Name | Description |
| --- | --- |
| getHyperlinkQueries () | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only IHyperlinkQueries. |

 **Result:**
[HyperlinkQueries](../hyperlinkqueries)


---


### getImages {#getImages}

| Name | Description |
| --- | --- |
| getImages () | Returns the collection of all images in the presentation. Read-only IImageCollection. |

 **Result:**
[ImageCollection](../imagecollection)


---


### getLayoutSlides {#getLayoutSlides}

| Name | Description |
| --- | --- |
| getLayoutSlides () | Returns a list of all layout slides that are defined in the presentation. Read-only IGlobalLayoutSlideCollection. You can access to alternative API for adding/inserting/removing/cloning layout slides by using IMasterSlide.LayoutSlides property. |

 **Result:**
[GlobalLayoutSlideCollection](../globallayoutslidecollection)


---


### getMasterHandoutSlideManager {#getMasterHandoutSlideManager}

| Name | Description |
| --- | --- |
| getMasterHandoutSlideManager () | Returns handout master manager. Read-only IMasterHandoutSlideManager. |

 **Result:**
MasterHandoutSlideManager


---


### getMasterNotesSlideManager {#getMasterNotesSlideManager}

| Name | Description |
| --- | --- |
| getMasterNotesSlideManager () | Returns notes master manager. Read-only IMasterNotesSlideManager. |

 **Result:**
MasterNotesSlideManager


---


### getMasterTheme {#getMasterTheme}

| Name | Description |
| --- | --- |
| getMasterTheme () | Returns master theme. Read-only IMasterTheme. |

 **Result:**
[MasterTheme](../mastertheme)


---


### getMasters {#getMasters}

| Name | Description |
| --- | --- |
| getMasters () | Returns a list of all master slides that are defined in the presentation. Read-only IMasterSlideCollection. |

 **Result:**
[MasterSlideCollection](../masterslidecollection)


---


### getNotesSize {#getNotesSize}

| Name | Description |
| --- | --- |
| getNotesSize () | Returns notes slide size object. Read-only INotesSize. |

 **Result:**
[NotesSize](../notessize)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a text. Read-only IPresentation. |

 **Result:**
[Presentation](../presentation)


---


### getProtectionManager {#getProtectionManager}

| Name | Description |
| --- | --- |
| getProtectionManager () | Gets manager of the permissions for this presentation. Read-only IProtectionManager. |

 **Result:**
[ProtectionManager](../protectionmanager)


---


### getSections {#getSections}

| Name | Description |
| --- | --- |
| getSections () | Returns a list of all slides sections that are defined in the presentation. Read-only ISectionCollection. |

 **Result:**
[SectionCollection](../sectioncollection)


---


### getSlideById {#getSlideById}

| Name | Description |
| --- | --- |
| getSlideById (long) | Returns a Slide, MasterSlide or LayoutSlide by Id. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| id | long | Id of a slide. |

 **Result:**
[NotesSlide](../notesslide), [MasterHandoutSlide](../masterhandoutslide), [LayoutSlide](../layoutslide), [MasterSlide](../masterslide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [Slide](../slide)


---


### getSlideShowSettings {#getSlideShowSettings}

| Name | Description |
| --- | --- |
| getSlideShowSettings () | Returns the slide show settings for the presentation. |

 **Result:**
SlideShowSettings


---


### getSlideSize {#getSlideSize}

| Name | Description |
| --- | --- |
| getSlideSize () | Returns slide size object. Read-only ISlideSize. |

 **Result:**
[SlideSize](../slidesize)


---


### getSlides {#getSlides}

| Name | Description |
| --- | --- |
| getSlides () | Returns a list of all slides that are defined in the presentation. Read-only ISlideCollection. |

 **Result:**
[SlideCollection](../slidecollection)


---


### getSourceFormat {#getSourceFormat}

| Name | Description |
| --- | --- |
| getSourceFormat () | Returns information about from which format presentation was loaded. Read-only SourceFormat. |

 **Result:**
int


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Returns a Thumbnail BufferedImage objects for all slides of a presentation. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |

 **Result:**
BufferedImage


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), int[]) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| slides | int[] | Array with slide positions, starting from 1. |

 **Result:**
BufferedImage


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), float, float) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

 **Result:**
BufferedImage


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), int[], float, float) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| slides | int[] | Array with slide positions, starting from 1. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

 **Result:**
BufferedImage


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), Dimension) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| imageSize | Dimension | Size of the image to create. |

 **Result:**
BufferedImage


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), int[], Dimension) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| slides | int[] | Array with slide positions, starting from 1. |
| imageSize | Dimension | Size of the image to create. |

 **Result:**
BufferedImage


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([RenderingOptions](../renderingoptions)) | Returns a Thumbnail BufferedImage objects for all slides of a presentation. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff options. |

 **Result:**
BufferedImage


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([RenderingOptions](../renderingoptions), int[]) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff options. |
| slides | int[] | Array with slide positions, starting from 1. |

 **Result:**
BufferedImage


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([RenderingOptions](../renderingoptions), float, float) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

 **Result:**
BufferedImage


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([RenderingOptions](../renderingoptions), int[], float, float) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff options. |
| slides | int[] | Array with slide positions, starting from 1. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

 **Result:**
BufferedImage


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([RenderingOptions](../renderingoptions), Dimension) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff options. |
| imageSize | Dimension | Size of the image to create. |

 **Result:**
BufferedImage


---


### getThumbnails {#getThumbnails}

| Name | Description |
| --- | --- |
| getThumbnails ([RenderingOptions](../renderingoptions), int[], Dimension) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff options. |
| slides | int[] | Array with slide positions, starting from 1. |
| imageSize | Dimension | Size of the image to create. |

 **Result:**
BufferedImage


---


### getVbaProject {#getVbaProject}

| Name | Description |
| --- | --- |
| getVbaProject () | Gets or sets VBA project with presentation macros. Read/write IVbaProject. |

 **Result:**
[VbaProject](../vbaproject)


---


### getVideos {#getVideos}

| Name | Description |
| --- | --- |
| getVideos () | Returns the collection of all embedded video files in the presentation. Read-only IVideoCollection. |

 **Result:**
[VideoCollection](../videocollection)


---


### getViewProperties {#getViewProperties}

| Name | Description |
| --- | --- |
| getViewProperties () | Gets presentation wide view properties. Read-only IViewProperties. |

 **Result:**
[ViewProperties](../viewproperties)


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int) | Saves all slides of a presentation to a file with the specified format. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int) | Saves all slides of a presentation to a stream in the specified format. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [HtmlOptions](../htmloptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [HtmlOptions](../htmloptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [XpsOptions](../xpsoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [XpsOptions](../xpsoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [SwfOptions](../swfoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [SwfOptions](../swfoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [TiffOptions](../tiffoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [TiffOptions](../tiffoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [XamlOptions](../xamloptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [XamlOptions](../xamloptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [GifOptions](../gifoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [GifOptions](../gifoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [PptOptions](../pptoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [PptOptions](../pptoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [Html5Options](../html5options)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [Html5Options](../html5options) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [MarkdownSaveOptions](../markdownsaveoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [RenderingOptions](../renderingoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [RenderingOptions](../renderingoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [PdfOptions](../pdfoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [PdfOptions](../pdfoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [PptxOptions](../pptxoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [PptxOptions](../pptxoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [SVGOptions](../svgoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [SVGOptions](../svgoptions) | Additional format options. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [HtmlOptions](../htmloptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [HtmlOptions](../htmloptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [XpsOptions](../xpsoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [XpsOptions](../xpsoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [SwfOptions](../swfoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [SwfOptions](../swfoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [TiffOptions](../tiffoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [TiffOptions](../tiffoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [XamlOptions](../xamloptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [XamlOptions](../xamloptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [GifOptions](../gifoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [GifOptions](../gifoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [PptOptions](../pptoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [PptOptions](../pptoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [Html5Options](../html5options)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [Html5Options](../html5options) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [MarkdownSaveOptions](../markdownsaveoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [RenderingOptions](../renderingoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [RenderingOptions](../renderingoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [PdfOptions](../pdfoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [PdfOptions](../pdfoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [PptxOptions](../pptxoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [PptxOptions](../pptxoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int, [SVGOptions](../svgoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| format | int | Format of the exported data. |
| options | [SVGOptions](../svgoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


### save {#save}

| Name | Description |
| --- | --- |
| save ([XamlOptions](../xamloptions)) | Saves all slides of a presentation to a set of files representing XAML markup. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [XamlOptions](../xamloptions) | The XAML format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [HtmlOptions](../htmloptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [HtmlOptions](../htmloptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [XpsOptions](../xpsoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [XpsOptions](../xpsoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [SwfOptions](../swfoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [SwfOptions](../swfoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [TiffOptions](../tiffoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [TiffOptions](../tiffoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [XamlOptions](../xamloptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [XamlOptions](../xamloptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [GifOptions](../gifoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [GifOptions](../gifoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [PptOptions](../pptoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [PptOptions](../pptoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [Html5Options](../html5options)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [Html5Options](../html5options) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [MarkdownSaveOptions](../markdownsaveoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [RenderingOptions](../renderingoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [RenderingOptions](../renderingoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [PdfOptions](../pdfoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [PdfOptions](../pdfoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [PptxOptions](../pptxoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [PptxOptions](../pptxoptions) | Additional format options. |


---


### save {#save}

| Name | Description |
| --- | --- |
| save (String, int[], int, [SVGOptions](../svgoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [SVGOptions](../svgoptions) | Additional format options. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [HtmlOptions](../htmloptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [HtmlOptions](../htmloptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [XpsOptions](../xpsoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [XpsOptions](../xpsoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [SwfOptions](../swfoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [SwfOptions](../swfoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [TiffOptions](../tiffoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [TiffOptions](../tiffoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [XamlOptions](../xamloptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [XamlOptions](../xamloptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [GifOptions](../gifoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [GifOptions](../gifoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [PptOptions](../pptoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [PptOptions](../pptoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [Html5Options](../html5options)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [Html5Options](../html5options) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [MarkdownSaveOptions](../markdownsaveoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [RenderingOptions](../renderingoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [RenderingOptions](../renderingoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [PdfOptions](../pdfoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [PdfOptions](../pdfoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [PptxOptions](../pptxoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [PptxOptions](../pptxoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### saveToStream  {#saveToStream }

| Name | Description |
| --- | --- |
| saveToStream  (Presentation, WriteStream, int[], int, [SVGOptions](../svgoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presentation | Presentation  | link to self |
| stream | WriteStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [SVGOptions](../svgoptions) | Additional format options. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


### setCurrentDateTime {#setCurrentDateTime}

| Name | Description |
| --- | --- |
| setCurrentDateTime (Date) | Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date. |


---


### setFirstSlideNumber {#setFirstSlideNumber}

| Name | Description |
| --- | --- |
| setFirstSlideNumber (int) | Represents the first slide number in the presentation |


---


### setVbaProject {#setVbaProject}

| Name | Description |
| --- | --- |
| setVbaProject ([VbaProject](../vbaproject)) | Gets or sets VBA project with presentation macros. Read/write IVbaProject. |


---


