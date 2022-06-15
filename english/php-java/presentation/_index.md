---
title: Presentation
type: docs
weight: 0
url: /php-java/presentation/
---

# Presentation class

  Represents a Microsoft PowerPoint presentation.
 

## Constructors

| name | description |
| --- | --- |
| [Presentation](/php-java/presentation/presentation/)() | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
| [Presentation](/php-java/presentation/presentation/)(LoadOptions) | This constructor creates new presentation from scratch. Created presentation has one empty slide. |
| [Presentation](/php-java/presentation/presentation/)(InputStream) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation](/php-java/presentation/presentation/)(InputStream, LoadOptions) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation](/php-java/presentation/presentation/)(String) | This constructor gets a source file path from which the contents of the Presentation are read. |
| [Presentation](/php-java/presentation/presentation/)(String, LoadOptions) | This constructor gets a source file path from which the contents of the Presentation are read. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [dispose](/php-java/presentation/dispose/)() | void | Releases all resources used by this Presentation object. |
| [getAllCustomXmlParts](/php-java/presentation/getallcustomxmlparts/)() | ICustomXmlPart | Returns all custom data parts in the presentaion. Read-only ICustomXmlPart[]. |
| [getAudios](/php-java/presentation/getaudios/)() | IAudioCollection | Returns the collection of all embedded audio files in the presentation. Read-only IAudioCollection. |
| [getCommentAuthors](/php-java/presentation/getcommentauthors/)() | ICommentAuthorCollection | Returns the collection of comments autors. Read-only ICommentAuthorCollection. |
| [getCurrentDateTime](/php-java/presentation/getcurrentdatetime/)() | Date | Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date. |
| [getCustomData](/php-java/presentation/getcustomdata/)() | ICustomData | Returns the presentation's custom data. Read-only ICustomData. |
| [getDefaultTextStyle](/php-java/presentation/getdefaulttextstyle/)() | ITextStyle | Returns default text style for shapes. Read-only ITextStyle. |
| [getDigitalSignatures](/php-java/presentation/getdigitalsignatures/)() | IDigitalSignatureCollection | Returns the collection of signatures used to sign the presentation. Read-only IDigitalSignatureCollection. |
| [getDocumentProperties](/php-java/presentation/getdocumentproperties/)() | IDocumentProperties | Returns DocumentProperties object which contains standard and custom document properties. Read-only IDocumentProperties. |
| [getFirstSlideNumber](/php-java/presentation/getfirstslidenumber/)() | int | Represents the first slide number in the presentation |
| [getFontsManager](/php-java/presentation/getfontsmanager/)() | IFontsManager | Returns fonts manager. Read-only IFontsManager. |
| [getHeaderFooterManager](/php-java/presentation/getheaderfootermanager/)() | IPresentationHeaderFooterManager | Returns actual HeaderFooter manager. Read-only IPresentationHeaderFooterManager. |
| [getHyperlinkQueries](/php-java/presentation/gethyperlinkqueries/)() | IHyperlinkQueries | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only IHyperlinkQueries. |
| [getImages](/php-java/presentation/getimages/)() | IImageCollection | Returns the collection of all images in the presentation. Read-only IImageCollection. |
| [getLayoutSlides](/php-java/presentation/getlayoutslides/)() | IGlobalLayoutSlideCollection | Returns a list of all layout slides that are defined in the presentation. Read-only IGlobalLayoutSlideCollection. You can access to alternative API for adding/inserting/removing/cloning layout slides by using IMasterSlide.LayoutSlides property. |
| [getMasterHandoutSlideManager](/php-java/presentation/getmasterhandoutslidemanager/)() | IMasterHandoutSlideManager | Returns handout master manager. Read-only IMasterHandoutSlideManager. |
| [getMasterNotesSlideManager](/php-java/presentation/getmasternotesslidemanager/)() | IMasterNotesSlideManager | Returns notes master manager. Read-only IMasterNotesSlideManager. |
| [getMasterTheme](/php-java/presentation/getmastertheme/)() | IMasterTheme | Returns master theme. Read-only IMasterTheme. |
| [getMasters](/php-java/presentation/getmasters/)() | IMasterSlideCollection | Returns a list of all master slides that are defined in the presentation. Read-only IMasterSlideCollection. |
| [getNotesSize](/php-java/presentation/getnotessize/)() | INotesSize | Returns notes slide size object. Read-only INotesSize. |
| [getPresentation](/php-java/presentation/getpresentation/)() | IPresentation | Returns the parent presentation of a text. Read-only IPresentation. |
| [getProtectionManager](/php-java/presentation/getprotectionmanager/)() | IProtectionManager | Gets manager of the permissions for this presentation. Read-only IProtectionManager. |
| [getSections](/php-java/presentation/getsections/)() | ISectionCollection | Returns a list of all slides sections that are defined in the presentation. Read-only ISectionCollection. |
| [getSlideById](/php-java/presentation/getslidebyid/)(long) | IBaseSlide | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [getSlideSize](/php-java/presentation/getslidesize/)() | ISlideSize | Returns slide size object. Read-only ISlideSize. |
| [getSlides](/php-java/presentation/getslides/)() | ISlideCollection | Returns a list of all slides that are defined in the presentation. Read-only ISlideCollection. |
| [getSourceFormat](/php-java/presentation/getsourceformat/)() | int | Returns information about from which format presentation was loaded. Read-only SourceFormat. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(INotesCommentsLayoutingOptions) | BufferedImage | Returns a Thumbnail BufferedImage objects for all slides of a presentation. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(INotesCommentsLayoutingOptions, int[]) | BufferedImage | Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(INotesCommentsLayoutingOptions, float, float) | BufferedImage | Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(INotesCommentsLayoutingOptions, int[], float, float) | BufferedImage | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(INotesCommentsLayoutingOptions, Dimension) | BufferedImage | Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(INotesCommentsLayoutingOptions, int[], Dimension) | BufferedImage | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(IRenderingOptions) | BufferedImage | Returns a Thumbnail BufferedImage objects for all slides of a presentation. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(IRenderingOptions, int[]) | BufferedImage | Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(IRenderingOptions, float, float) | BufferedImage | Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(IRenderingOptions, int[], float, float) | BufferedImage | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(IRenderingOptions, Dimension) | BufferedImage | Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |
| [getThumbnails](/php-java/presentation/getthumbnails/)(IRenderingOptions, int[], Dimension) | BufferedImage | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |
| [getVbaProject](/php-java/presentation/getvbaproject/)() | IVbaProject | Gets or sets VBA project with presentation macros. Read/write IVbaProject. |
| [getVideos](/php-java/presentation/getvideos/)() | IVideoCollection | Returns the collection of all embedded video files in the presentation. Read-only IVideoCollection. |
| [getViewProperties](/php-java/presentation/getviewproperties/)() | IViewProperties | Gets presentation wide view properties. Read-only IViewProperties. |
| [joinPortionsWithSameFormatting](/php-java/presentation/joinportionswithsameformatting/)() | void | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [save](/php-java/presentation/save/)(String, int) | void | Saves all slides of a presentation to a file with the specified format. |
| [save](/php-java/presentation/save/)(OutputStream, int) | void | Saves all slides of a presentation to a stream in the specified format. |
| [save](/php-java/presentation/save/)(String, int, ISaveOptions) | void | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save](/php-java/presentation/save/)(OutputStream, int, ISaveOptions) | void | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save](/php-java/presentation/save/)(IXamlOptions) | void | Saves all slides of a presentation to a set of files representing XAML markup. |
| [save](/php-java/presentation/save/)(String, int[], int) | void | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](/php-java/presentation/save/)(String, int[], int, ISaveOptions) | void | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save](/php-java/presentation/save/)(OutputStream, int[], int) | void | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save](/php-java/presentation/save/)(OutputStream, int[], int, ISaveOptions) | void | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [setCurrentDateTime](/php-java/presentation/setcurrentdatetime/)(Date) | void | Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date. |
| [setFirstSlideNumber](/php-java/presentation/setfirstslidenumber/)(int) | void | Represents the first slide number in the presentation |
| [setVbaProject](/php-java/presentation/setvbaproject/)(IVbaProject) | void | Gets or sets VBA project with presentation macros. Read/write IVbaProject. |
