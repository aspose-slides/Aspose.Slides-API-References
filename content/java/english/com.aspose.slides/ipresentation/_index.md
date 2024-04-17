---
title: IPresentation
second_title: Aspose.Slides for Java API Reference
description: Presentation document
type: docs
url: /com.aspose.slides/ipresentation/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Presentation document
## Methods

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Returns or sets date and time which will substitute content of datetime fields. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Returns or sets date and time which will substitute content of datetime fields. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns HeaderFooter manager of the presentation. |
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
| [getCustomData()](#getCustomData--) | Returns the presentation's custom data. |
| [getVbaProject()](#getVbaProject--) | Gets VBA project with presentation macros. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Gets VBA project with presentation macros. |
| [getSourceFormat()](#getSourceFormat--) | Returns information about from which format presentation was loaded. |
| [getMasterTheme()](#getMasterTheme--) | Returns master theme of the presentation. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). |
| [getViewProperties()](#getViewProperties--) | Gets presentation wide view properties. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Represents the first slide number in the presentation. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Represents the first slide number in the presentation. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Returns all custom data parts in the presentaion. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Returns the collection of signatures used to sign the presentation. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Saves all slides of a presentation to a file with the specified format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Saves all slides of a presentation to a stream in the specified format. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [getThumbnails(IRenderingOptions options)](#getThumbnails-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail BufferedImage objects for all slides of a presentation. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail Image objects for all slides of a presentation. |
| [getThumbnails(IRenderingOptions options, int[] slides)](#getThumbnails-com.aspose.slides.IRenderingOptions-int---) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Returns a Thumbnail Image objects for specified slides of a presentation. |
| [getThumbnails(IRenderingOptions options, float scaleX, float scaleY)](#getThumbnails-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail Image objects for all slides of a presentation with custom scaling. |
| [getThumbnails(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getThumbnails-com.aspose.slides.IRenderingOptions-int---float-float-) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling. |
| [getThumbnails(IRenderingOptions options, Dimension imageSize)](#getThumbnails-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Returns a Thumbnail Image objects for all slides of a presentation with specified size. |
| [getThumbnails(IRenderingOptions options, int[] slides, Dimension imageSize)](#getThumbnails-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Returns a Thumbnail Image objects for specified slides of a presentation with specified size. |
| [getSlideById(long id)](#getSlideById-long-) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```


Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date.

**Returns:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```


Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```


Returns HeaderFooter manager of the presentation. Read-only [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Returns:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```


Gets manager of the permissions for this presentation. Read-only [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Returns:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```


Returns a list of all slides that are defined in the presentation. Read-only [ISlideCollection](../../com.aspose.slides/islidecollection).

**Returns:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```


Returns a list of all slides sections that are defined in the presentation. Read-only [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Returns:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```


Returns slide size object. Read-only [ISlideSize](../../com.aspose.slides/islidesize).

**Returns:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```


Returns notes slide size object. Read-only [INotesSize](../../com.aspose.slides/inotessize).

**Returns:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```


Returns a list of all layout slides that are defined in the presentation. Read-only [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

You can access to alternative API for adding/inserting/removing/cloning layout slides by using IMasterSlide.LayoutSlides property.

**Returns:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```


Returns a list of all master slides that are defined in the presentation. Read-only [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Returns:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```


Returns notes master manager. Read-only [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Returns:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```


Returns handout master manager. Read-only [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Returns:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```


Returns fonts manager. Read-only [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Returns:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```


Returns default text style for shapes. Read-only [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```


Returns the collection of comments autors. Read-only [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Returns:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```


Returns DocumentProperties object which contains standard and custom document properties. Read-only [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```


Returns the collection of all images in the presentation. Read-only [IImageCollection](../../com.aspose.slides/iimagecollection).

**Returns:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```


Returns the collection of all embedded audio files in the presentation. Read-only [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Returns:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```


Returns the collection of all embedded video files in the presentation. Read-only [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Returns:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


Returns the presentation's custom data. Read-only [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```


Gets VBA project with presentation macros. Read/write [IVbaProject](../../com.aspose.slides/ivbaproject).

**Returns:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```


Gets VBA project with presentation macros. Read/write [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```


Returns information about from which format presentation was loaded. Read-only \#getSourceFormat.getSourceFormat.

**Returns:**
int
### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```


Returns master theme of the presentation. Read-only [IMasterTheme](../../com.aspose.slides/imastertheme).

**Returns:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returns:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```


Gets presentation wide view properties. Read-only [IViewProperties](../../com.aspose.slides/iviewproperties).

**Returns:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```


Represents the first slide number in the presentation. Read/write int.

**Returns:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```


Represents the first slide number in the presentation. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```


Returns all custom data parts in the presentaion. Read-only ICustomXmlPart[].

**Returns:**
com.aspose.slides.ICustomXmlPart[]
### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
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
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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
### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```


Saves all slides of a presentation to a file with the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```


Saves all slides of a presentation to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
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
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```


Saves all slides of a presentation to a stream in the specified format and with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```


Saves specified slides of a presentation to a file with the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```


Saves specified slides of a presentation to a file with the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```


Saves specified slides of a presentation to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Saves specified slides of a presentation to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
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

### getThumbnails(IRenderingOptions options) {#getThumbnails-com.aspose.slides.IRenderingOptions-}
```
public abstract BufferedImage[] getThumbnails(IRenderingOptions options)
```


Returns a Thumbnail BufferedImage objects for all slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```


Returns a Thumbnail Image objects for all slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**Returns:**
com.aspose.slides.IImage[] - Image objects.
### getThumbnails(IRenderingOptions options, int[] slides) {#getThumbnails-com.aspose.slides.IRenderingOptions-int---}
```
public abstract BufferedImage[] getThumbnails(IRenderingOptions options, int[] slides)
```


Returns a Thumbnail BufferedImage objects for specified slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```


Returns a Thumbnail Image objects for specified slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |

**Returns:**
com.aspose.slides.IImage[] - Image objects.
### getThumbnails(IRenderingOptions options, float scaleX, float scaleY) {#getThumbnails-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract BufferedImage[] getThumbnails(IRenderingOptions options, float scaleX, float scaleY)
```


Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Returns a Thumbnail Image objects for all slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
com.aspose.slides.IImage[] - Image objects.
### getThumbnails(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getThumbnails-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract BufferedImage[] getThumbnails(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
com.aspose.slides.IImage[] - Image objects.
### getThumbnails(IRenderingOptions options, Dimension imageSize) {#getThumbnails-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract BufferedImage[] getThumbnails(IRenderingOptions options, Dimension imageSize)
```


Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Returns a Thumbnail Image objects for all slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
com.aspose.slides.IImage[] - Image objects.
### getThumbnails(IRenderingOptions options, int[] slides, Dimension imageSize) {#getThumbnails-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract BufferedImage[] getThumbnails(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Returns a Thumbnail Bitmap objects for specified slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
java.awt.image.BufferedImage[] - Bitmap objects.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Returns a Thumbnail Image objects for specified slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
com.aspose.slides.IImage[] - Image objects.
### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```


Returns a Slide, MasterSlide or LayoutSlide by Id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | Id of a slide. |

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides.

