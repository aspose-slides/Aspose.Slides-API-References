---
title: Presentation
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/presentation/
---

## Presentation class

  Represents a Microsoft PowerPoint presentation.
 

## Constructors

| Name | Description |
| --- | --- |
| [Presentation](presentation)() | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
| [Presentation](presentation)(LoadOptions) | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
| [Presentation](presentation)(InputStream) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation](presentation)(InputStream, LoadOptions) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation](presentation)(String) | This constructor gets a source file path from which the contents of the Presentation are read. |
| [Presentation](presentation)(String, LoadOptions) | This constructor gets a source file path from which the contents of the Presentation are read. |

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
| [getSlideSize](getslidesize)() | Returns slide size object. Read-only ISlideSize. |
| [getSlides](getslides)() | Returns a list of all slides that are defined in the presentation. Read-only ISlideCollection. |
| [getSourceFormat](getsourceformat)() | Returns information about from which format presentation was loaded. Read-only SourceFormat. |
| [getThumbnails](getthumbnails)(INotesCommentsLayoutingOptions) | Returns a Thumbnail BufferedImage objects for all slides of a presentation. |
| [getThumbnails](getthumbnails)(INotesCommentsLayoutingOptions, int[]) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |
| [getThumbnails](getthumbnails)(INotesCommentsLayoutingOptions, float, float) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |
| [getThumbnails](getthumbnails)(INotesCommentsLayoutingOptions, int[], float, float) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |
| [getThumbnails](getthumbnails)(INotesCommentsLayoutingOptions, Dimension) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |
| [getThumbnails](getthumbnails)(INotesCommentsLayoutingOptions, int[], Dimension) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |
| [getThumbnails](getthumbnails)(IRenderingOptions) | Returns a Thumbnail BufferedImage objects for all slides of a presentation. |
| [getThumbnails](getthumbnails)(IRenderingOptions, int[]) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |
| [getThumbnails](getthumbnails)(IRenderingOptions, float, float) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |
| [getThumbnails](getthumbnails)(IRenderingOptions, int[], float, float) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |
| [getThumbnails](getthumbnails)(IRenderingOptions, Dimension) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |
| [getThumbnails](getthumbnails)(IRenderingOptions, int[], Dimension) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |
| [getVbaProject](getvbaproject)() | Gets or sets VBA project with presentation macros. Read/write IVbaProject. |
| [getVideos](getvideos)() | Returns the collection of all embedded video files in the presentation. Read-only IVideoCollection. |
| [getViewProperties](getviewproperties)() | Gets presentation wide view properties. Read-only IViewProperties. |
| [joinPortionsWithSameFormatting](joinportionswithsameformatting)() | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [save](save)(String, int) | Saves all slides of a presentation to a file with the specified format. |
| [save](save)(OutputStream, int) | Saves all slides of a presentation to a stream in the specified format. |
| [save](save)(String, int, ISaveOptions) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](save)(OutputStream, int, ISaveOptions) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](save)(IXamlOptions) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [save](save)(String, int[], int) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(String, int[], int, ISaveOptions) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](save)(OutputStream, int[], int, ISaveOptions) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [setCurrentDateTime](setcurrentdatetime)(Date) | Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date. |
| [setFirstSlideNumber](setfirstslidenumber)(int) | Represents the first slide number in the presentation |
| [setVbaProject](setvbaproject)(IVbaProject) | Gets or sets VBA project with presentation macros. Read/write IVbaProject. |
