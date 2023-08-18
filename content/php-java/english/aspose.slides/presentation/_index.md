---
title: Presentation
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/presentation/
---

## Presentation class

  Represents a Microsoft PowerPoint presentation.
 

## Constructors

| Name | Description |
| --- | --- |
| [Presentation](presentation)() | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
| [Presentation](presentation)([LoadOptions](../loadoptions)) | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
| [Presentation](presentation)(InputStream) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation](presentation)(InputStream, [LoadOptions](../loadoptions)) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation](presentation)(String) | This constructor gets a source file path from which the contents of the Presentation are read. |
| [Presentation](presentation)(String, [LoadOptions](../loadoptions)) | This constructor gets a source file path from which the contents of the Presentation are read. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](dispose)() | Releases all resources used by this Presentation object. |
| [getAllCustomXmlParts](getallcustomxmlparts)() | Returns all custom data parts in the presentaion. Read-only ICustomXmlPart[]. |
| [getAudios](getaudios)() | Returns the collection of all embedded audio files in the presentation. Read-only IAudioCollection. |
| [getCommentAuthors](getcommentauthors)() | Returns the collection of comments autors. Read-only ICommentAuthorCollection. |
| [getCurrentDateTime](getcurrentdatetime)() | Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date. |
| [getCustomData](getcustomdata)() | Returns the presentation's custom data. Read-only ICustomData. |
| [getDefaultTextStyle](getdefaulttextstyle)() | Returns default text style for shapes. Read-only ITextStyle. |
| [getDigitalSignatures](getdigitalsignatures)() | Returns the collection of signatures used to sign the presentation. Read-only IDigitalSignatureCollection. |
| [getDocumentProperties](getdocumentproperties)() | Returns DocumentProperties object which contains standard and custom document properties. Read-only IDocumentProperties. |
| [getFirstSlideNumber](getfirstslidenumber)() | Represents the first slide number in the presentation |
| [getFontsManager](getfontsmanager)() | Returns fonts manager. Read-only IFontsManager. |
| [getHeaderFooterManager](getheaderfootermanager)() | Returns actual HeaderFooter manager. Read-only IPresentationHeaderFooterManager. |
| [getHyperlinkQueries](gethyperlinkqueries)() | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only IHyperlinkQueries. |
| [getImages](getimages)() | Returns the collection of all images in the presentation. Read-only IImageCollection. |
| [getLayoutSlides](getlayoutslides)() | Returns a list of all layout slides that are defined in the presentation. Read-only IGlobalLayoutSlideCollection. You can access to alternative API for adding/inserting/removing/cloning layout slides by using IMasterSlide.LayoutSlides property. |
| [getMasterHandoutSlideManager](getmasterhandoutslidemanager)() | Returns handout master manager. Read-only IMasterHandoutSlideManager. |
| [getMasterNotesSlideManager](getmasternotesslidemanager)() | Returns notes master manager. Read-only IMasterNotesSlideManager. |
| [getMasterTheme](getmastertheme)() | Returns master theme. Read-only IMasterTheme. |
| [getMasters](getmasters)() | Returns a list of all master slides that are defined in the presentation. Read-only IMasterSlideCollection. |
| [getNotesSize](getnotessize)() | Returns notes slide size object. Read-only INotesSize. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a text. Read-only IPresentation. |
| [getProtectionManager](getprotectionmanager)() | Gets manager of the permissions for this presentation. Read-only IProtectionManager. |
| [getSections](getsections)() | Returns a list of all slides sections that are defined in the presentation. Read-only ISectionCollection. |
| [getSlideById](getslidebyid)(long) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [getSlideShowSettings](getslideshowsettings)() | Returns the slide show settings for the presentation. |
| [getSlideSize](getslidesize)() | Returns slide size object. Read-only ISlideSize. |
| [getSlides](getslides)() | Returns a list of all slides that are defined in the presentation. Read-only ISlideCollection. |
| [getSourceFormat](getsourceformat)() | Returns information about from which format presentation was loaded. Read-only SourceFormat. |
| [getThumbnails](getthumbnails)([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Returns a Thumbnail BufferedImage objects for all slides of a presentation. |
| [getThumbnails](getthumbnails)([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), int[]) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |
| [getThumbnails](getthumbnails)([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), float, float) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |
| [getThumbnails](getthumbnails)([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), int[], float, float) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |
| [getThumbnails](getthumbnails)([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), Dimension) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |
| [getThumbnails](getthumbnails)([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), int[], Dimension) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |
| [getThumbnails](getthumbnails)([RenderingOptions](../renderingoptions)) | Returns a Thumbnail BufferedImage objects for all slides of a presentation. |
| [getThumbnails](getthumbnails)([RenderingOptions](../renderingoptions), int[]) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |
| [getThumbnails](getthumbnails)([RenderingOptions](../renderingoptions), float, float) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |
| [getThumbnails](getthumbnails)([RenderingOptions](../renderingoptions), int[], float, float) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |
| [getThumbnails](getthumbnails)([RenderingOptions](../renderingoptions), Dimension) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |
| [getThumbnails](getthumbnails)([RenderingOptions](../renderingoptions), int[], Dimension) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |
| [getVbaProject](getvbaproject)() | Gets or sets VBA project with presentation macros. Read/write IVbaProject. |
| [getVideos](getvideos)() | Returns the collection of all embedded video files in the presentation. Read-only IVideoCollection. |
| [getViewProperties](getviewproperties)() | Gets presentation wide view properties. Read-only IViewProperties. |
| [joinPortionsWithSameFormatting](joinportionswithsameformatting)() | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [save](save)(String, int) | Saves all slides of a presentation to a file with the specified format. |
| [save](save)(OutputStream, int) | Saves all slides of a presentation to a stream in the specified format. |
| [save](save)(String, int, [RenderingOptions](../renderingoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(String, int, [PptOptions](../pptoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(String, int, [XamlOptions](../xamloptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(String, int, [SVGOptions](../svgoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(String, int, [PdfOptions](../pdfoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(String, int, [HtmlOptions](../htmloptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(String, int, [SwfOptions](../swfoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(String, int, [Html5Options](../html5options)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(String, int, [TiffOptions](../tiffoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(String, int, [XpsOptions](../xpsoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(String, int, [GifOptions](../gifoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(String, int, [PptxOptions](../pptxoptions)) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(OutputStream, int, [RenderingOptions](../renderingoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(OutputStream, int, [PptOptions](../pptoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(OutputStream, int, [XamlOptions](../xamloptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(OutputStream, int, [SVGOptions](../svgoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(OutputStream, int, [PdfOptions](../pdfoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(OutputStream, int, [HtmlOptions](../htmloptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(OutputStream, int, [SwfOptions](../swfoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(OutputStream, int, [Html5Options](../html5options)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(OutputStream, int, [TiffOptions](../tiffoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(OutputStream, int, [XpsOptions](../xpsoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(OutputStream, int, [GifOptions](../gifoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(OutputStream, int, [PptxOptions](../pptxoptions)) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)([XamlOptions](../xamloptions)) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [save](save)(String, int[], int) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [RenderingOptions](../renderingoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [PptOptions](../pptoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [XamlOptions](../xamloptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [SVGOptions](../svgoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [PdfOptions](../pdfoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [HtmlOptions](../htmloptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [SwfOptions](../swfoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [Html5Options](../html5options)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [TiffOptions](../tiffoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [XpsOptions](../xpsoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [GifOptions](../gifoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, [PptxOptions](../pptxoptions)) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [RenderingOptions](../renderingoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [PptOptions](../pptoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [XamlOptions](../xamloptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [SVGOptions](../svgoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [PdfOptions](../pdfoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [HtmlOptions](../htmloptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [SwfOptions](../swfoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [Html5Options](../html5options)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [TiffOptions](../tiffoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [XpsOptions](../xpsoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [GifOptions](../gifoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, [PptxOptions](../pptxoptions)) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [setCurrentDateTime](setcurrentdatetime)(Date) | Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date. |
| [setFirstSlideNumber](setfirstslidenumber)(int) | Represents the first slide number in the presentation |
| [setVbaProject](setvbaproject)([VbaProject](../vbaproject)) | Gets or sets VBA project with presentation macros. Read/write IVbaProject. |
