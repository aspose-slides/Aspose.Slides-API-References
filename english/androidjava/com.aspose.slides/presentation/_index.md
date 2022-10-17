---
title: Presentation
second_title: Aspose.Slides for Android via Java API Reference
description:   Represents a Microsoft PowerPoint presentation.
type: docs
weight: 442
url: /androidjava/com.aspose.slides/presentation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Represents a Microsoft PowerPoint presentation.
## Constructors

| Constructor | Description |
| --- | --- |
| [Presentation()](#Presentation--) | This constructor creates new presentation from scratch. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | This constructor creates new presentation from scratch. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation(String file)](#Presentation-java.lang.String-) | This constructor gets a source file path from which the contents of the Presentation are read. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | This constructor gets a source file path from which the contents of the Presentation are read. |
## Methods

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Returns or sets date and time which will substitute content of datetime fields. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Returns or sets date and time which will substitute content of datetime fields. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns actual HeaderFooter manager. |
| [getProtectionManager()](#getProtectionManager--) | Gets manager of the permissions for this presentation. |
| [getSlides()](#getSlides--) | Returns a list of all slides that are defined in the presentation. |
| [getSections()](#getSections--) | Returns a list of all slides sections that are defined in the presentation. |
| [getSlideSize()](#getSlideSize--) | Returns slide size object. |
| [getNotesSize()](#getNotesSize--) | Returns notes slide size object. |
| [getLayoutSlides()](#getLayoutSlides--) | Returns a list of all layout slides that are defined in the presentation. |
| [getMasters()](#getMasters--) | Returns a list of all master slides that are defined in the presentation. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Returns notes master manager. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Returns handout master manager. |
| [getFontsManager()](#getFontsManager--) | Returns fonts manager. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Returns default text style for shapes. |
| [getCommentAuthors()](#getCommentAuthors--) | Returns the collection of comments autors. |
| [getDocumentProperties()](#getDocumentProperties--) | Returns DocumentProperties object which contains standard and custom document properties. |
| [getImages()](#getImages--) | Returns the collection of all images in the presentation. |
| [getAudios()](#getAudios--) | Returns the collection of all embedded audio files in the presentation. |
| [getVideos()](#getVideos--) | Returns the collection of all embedded video files in the presentation. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Returns the slide show settings for the presentation. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Returns the collection of signatures used to sign the presentation. |
| [getCustomData()](#getCustomData--) | Returns the presentation's custom data. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Returns all custom data parts in the presentaion. |
| [getVbaProject()](#getVbaProject--) | Gets or sets VBA project with presentation macros. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Gets or sets VBA project with presentation macros. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). |
| [getViewProperties()](#getViewProperties--) | Gets presentation wide view properties. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Represents the first slide number in the presentation |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Represents the first slide number in the presentation |
| [getSlideById(long id)](#getSlideById-long-) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [getSourceFormat()](#getSourceFormat--) | Returns information about from which format presentation was loaded. |
| [getMasterTheme()](#getMasterTheme--) | Returns master theme. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Saves all slides of a presentation to a file with the specified format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Saves all slides of a presentation to a stream in the specified format. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-) | Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---) | Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-float-float-) | Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation with custom scaling. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, float scaleX, float scaleY)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---float-float-) | Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation with custom scaling. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, Size imageSize)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-com.aspose.slides.android.Size-) | Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation with specified size. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, Size imageSize)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---com.aspose.slides.android.Size-) | Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation with specified size. |
| [getThumbnails(IRenderingOptions options)](#getThumbnails-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation. |
| [getThumbnails(IRenderingOptions options, int[] slides)](#getThumbnails-com.aspose.slides.IRenderingOptions-int---) | Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation. |
| [getThumbnails(IRenderingOptions options, float scaleX, float scaleY)](#getThumbnails-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation with custom scaling. |
| [getThumbnails(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getThumbnails-com.aspose.slides.IRenderingOptions-int---float-float-) | Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation with custom scaling. |
| [getThumbnails(IRenderingOptions options, Size imageSize)](#getThumbnails-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation with specified size. |
| [getThumbnails(IRenderingOptions options, int[] slides, Size imageSize)](#getThumbnails-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation with specified size. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [dispose()](#dispose--) | Releases all resources used by this Presentation object. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a text. |
### Presentation() {#Presentation--}
```
public Presentation()
```


This constructor creates new presentation from scratch. Created presentation has one empty slide.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```


This constructor creates new presentation from scratch. Created presentation has one empty slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Additional load options. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```


This constructor is the primary mechanism for reading an existing Presentation.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Input stream. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```


This constructor is the primary mechanism for reading an existing Presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Input stream. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Additional load options. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```


This constructor gets a source file path from which the contents of the Presentation are read.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Input file. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```


This constructor gets a source file path from which the contents of the Presentation are read.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Input file. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Additional load options. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```


Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date.

**Returns:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```


Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```


Returns actual HeaderFooter manager. Read-only [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Returns:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```


Gets manager of the permissions for this presentation. Read-only [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Returns:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```


Returns a list of all slides that are defined in the presentation. Read-only [ISlideCollection](../../com.aspose.slides/islidecollection).

**Returns:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```


Returns a list of all slides sections that are defined in the presentation. Read-only [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Returns:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```


Returns slide size object. Read-only [ISlideSize](../../com.aspose.slides/islidesize).

**Returns:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```


Returns notes slide size object. Read-only [INotesSize](../../com.aspose.slides/inotessize).

**Returns:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```


Returns a list of all layout slides that are defined in the presentation. Read-only [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

You can access to alternative API for adding/inserting/removing/cloning layout slides by using IMasterSlide.LayoutSlides property.

**Returns:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```


Returns a list of all master slides that are defined in the presentation. Read-only [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Returns:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```


Returns notes master manager. Read-only [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Returns:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```


Returns handout master manager. Read-only [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Returns:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```


Returns fonts manager. Read-only [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Returns:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```


Returns default text style for shapes. Read-only [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```


Returns the collection of comments autors. Read-only [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Returns:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```


Returns DocumentProperties object which contains standard and custom document properties. Read-only [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```


Returns the collection of all images in the presentation. Read-only [IImageCollection](../../com.aspose.slides/iimagecollection).

**Returns:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```


Returns the collection of all embedded audio files in the presentation. Read-only [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Returns:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```


Returns the collection of all embedded video files in the presentation. Read-only [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Returns:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```


Returns the slide show settings for the presentation.

**Returns:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```


Returns the collection of signatures used to sign the presentation. Read-only [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Returns the presentation's custom data. Read-only [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```


Returns all custom data parts in the presentaion. Read-only ICustomXmlPart[].

**Returns:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```


Gets or sets VBA project with presentation macros. Read/write [IVbaProject](../../com.aspose.slides/ivbaproject).

**Returns:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```


Gets or sets VBA project with presentation macros. Read/write [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returns:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


Gets presentation wide view properties. Read-only [IViewProperties](../../com.aspose.slides/iviewproperties).

**Returns:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```


Represents the first slide number in the presentation

**Returns:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```


Represents the first slide number in the presentation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```


Returns a Slide, MasterSlide or LayoutSlide by Id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | Id of a slide. |

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```


Returns information about from which format presentation was loaded. Read-only [SourceFormat](../../com.aspose.slides/sourceformat).

**Returns:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```


Returns master theme. Read-only [IMasterTheme](../../com.aspose.slides/imastertheme).

**Returns:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```


Saves all slides of a presentation to a file with the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Saves all slides of a presentation to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


Saves all slides of a presentation to a file with the specified format and with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


Saves all slides of a presentation to a stream in the specified format and with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```


Saves all slides of a presentation to a set of files representing XAML markup.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | The XAML format options. |

### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-}
```
public final Bitmap[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting)
```


Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---}
```
public final Bitmap[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides)
```


Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| slides | int[] | Array with slide positions, starting from 1. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-float-float-}
```
public final Bitmap[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY)
```


Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, float scaleX, float scaleY) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---float-float-}
```
public final Bitmap[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, float scaleX, float scaleY)
```


Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| slides | int[] | Array with slide positions, starting from 1. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, Size imageSize) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-com.aspose.slides.android.Size-}
```
public final Bitmap[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, Size imageSize)
```


Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, Size imageSize) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---com.aspose.slides.android.Size-}
```
public final Bitmap[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, Size imageSize)
```


Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| slides | int[] | Array with slide positions, starting from 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### getThumbnails(IRenderingOptions options) {#getThumbnails-com.aspose.slides.IRenderingOptions-}
```
public final Bitmap[] getThumbnails(IRenderingOptions options)
```


Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### getThumbnails(IRenderingOptions options, int[] slides) {#getThumbnails-com.aspose.slides.IRenderingOptions-int---}
```
public final Bitmap[] getThumbnails(IRenderingOptions options, int[] slides)
```


Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |
| slides | int[] | Array with slide positions, starting from 1. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### getThumbnails(IRenderingOptions options, float scaleX, float scaleY) {#getThumbnails-com.aspose.slides.IRenderingOptions-float-float-}
```
public final Bitmap[] getThumbnails(IRenderingOptions options, float scaleX, float scaleY)
```


Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### getThumbnails(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getThumbnails-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final Bitmap[] getThumbnails(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |
| slides | int[] | Array with slide positions, starting from 1. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### getThumbnails(IRenderingOptions options, Size imageSize) {#getThumbnails-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final Bitmap[] getThumbnails(IRenderingOptions options, Size imageSize)
```


Returns a Thumbnail android.graphics.Bitmap objects for all slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### getThumbnails(IRenderingOptions options, int[] slides, Size imageSize) {#getThumbnails-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final Bitmap[] getThumbnails(IRenderingOptions options, int[] slides, Size imageSize)
```


Returns a Thumbnail android.graphics.Bitmap objects for specified slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |
| slides | int[] | Array with slide positions, starting from 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
android.graphics.Bitmap[] - android.graphics.Bitmap objects.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


Saves specified slides of a presentation to a file with the specified format with page number keeping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


Saves specified slides of a presentation to a file with the specified format with page number keeping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


Saves specified slides of a presentation to a stream in the specified format with page number keeping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Saves specified slides of a presentation to a stream in the specified format with page number keeping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides.

### dispose() {#dispose--}
```
public final void dispose()
```


Releases all resources used by this Presentation object.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a text. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
