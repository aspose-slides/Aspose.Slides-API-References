---
title: ISlide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a slide in a presentation.
type: docs
url: /com.aspose.slides/islide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Represents a slide in a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns HeaderFooter manager of the slide. |
| [getSlideNumber()](#getSlideNumber--) | Returns a number of slide. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Returns a number of slide. |
| [getHidden()](#getHidden--) | Determines whether the specified slide is hidden during a slide show. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determines whether the specified slide is hidden during a slide show. |
| [getThumbnail(float scaleX, float scaleY)](#getThumbnail-float-float-) | Returns a Thumbnail Bitmap object with custom scaling. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Returns an image object with custom scaling. |
| [getThumbnail()](#getThumbnail--) | Returns a Thumbnail Image object (20% of real size). |
| [getImage()](#getImage--) | Returns a Thumbnail Image object (20% of real size). |
| [getThumbnail(Size imageSize)](#getThumbnail-com.aspose.slides.android.Size-) | Returns a Thumbnail Bitmap object with specified size. |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Returns an image object with specified size. |
| [getThumbnail(ITiffOptions options)](#getThumbnail-com.aspose.slides.ITiffOptions-) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [getThumbnail(IRenderingOptions options)](#getThumbnail-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail Bitmap object. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail Bitmap object. |
| [getThumbnail(IRenderingOptions options, float scaleX, float scaleY)](#getThumbnail-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail Bitmap object with custom scaling. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail Bitmap object with custom scaling. |
| [getThumbnail(IRenderingOptions options, Size imageSize)](#getThumbnail-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Returns a Thumbnail Bitmap object with specified size. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Returns a Thumbnail Bitmap object with specified size. |
| [renderToGraphics(IRenderingOptions options, Canvas graphics)](#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-) | Renders certain slide to a Graphics object. |
| [renderToGraphics(IRenderingOptions options, Canvas graphics, float scaleX, float scaleY)](#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-float-float-) | Renders certain slide to a Graphics object with custom scaling. |
| [renderToGraphics(IRenderingOptions options, Canvas graphics, Size renderingSize)](#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-com.aspose.slides.android.Size-) | Renders certain slide to a Graphics object using specified size. |
| [getLayoutSlide()](#getLayoutSlide--) | Returns or sets the layout slide for the current slide. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Returns or sets the layout slide for the current slide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Allow to access notes slide, add and remove it. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Returns all slide comments added by specific author. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Saves content of slide as SVG file. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Saves content of slide as SVG file. |
| [remove()](#remove--) | Removes slide from presentation. |
| [reset()](#reset--) | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```


Returns HeaderFooter manager of the slide. Read-only [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Returns:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```


Returns a number of slide. Index of slide in [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) collection is always equal to SlideNumber - 1. Read/write int.

**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```


Returns a number of slide. Index of slide in [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) collection is always equal to SlideNumber - 1. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```


Determines whether the specified slide is hidden during a slide show. Read/write boolean.

**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```


Determines whether the specified slide is hidden during a slide show. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getThumbnail(float scaleX, float scaleY) {#getThumbnail-float-float-}
```
public abstract Bitmap getThumbnail(float scaleX, float scaleY)
```


Returns a Thumbnail Bitmap object with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
android.graphics.Bitmap - Bitmap object android.graphics.Bitmap
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```


Returns an image object with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getThumbnail() {#getThumbnail--}
```
public abstract Bitmap getThumbnail()
```


Returns a Thumbnail Image object (20% of real size).

**Returns:**
android.graphics.Bitmap - Bitmap object android.graphics.Bitmap
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Returns a Thumbnail Image object (20% of real size).

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getThumbnail(Size imageSize) {#getThumbnail-com.aspose.slides.android.Size-}
```
public abstract Bitmap getThumbnail(Size imageSize)
```


Returns a Thumbnail Bitmap object with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
android.graphics.Bitmap - Bitmap object.
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```


Returns an image object with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getThumbnail(ITiffOptions options) {#getThumbnail-com.aspose.slides.ITiffOptions-}
```
public abstract Bitmap getThumbnail(ITiffOptions options)
```


Returns a Thumbnail tiff bitmap object with specified parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff options. |

**Returns:**
android.graphics.Bitmap - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```


Returns a Thumbnail tiff bitmap object with specified parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff options. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getThumbnail(IRenderingOptions options) {#getThumbnail-com.aspose.slides.IRenderingOptions-}
```
public abstract Bitmap getThumbnail(IRenderingOptions options)
```


Returns a Thumbnail Bitmap object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**Returns:**
android.graphics.Bitmap - Bitmap objects.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```


Returns a Thumbnail Bitmap object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getThumbnail(IRenderingOptions options, float scaleX, float scaleY) {#getThumbnail-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract Bitmap getThumbnail(IRenderingOptions options, float scaleX, float scaleY)
```


Returns a Thumbnail Bitmap object with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
android.graphics.Bitmap - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


Returns a Thumbnail Bitmap object with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getThumbnail(IRenderingOptions options, Size imageSize) {#getThumbnail-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract Bitmap getThumbnail(IRenderingOptions options, Size imageSize)
```


Returns a Thumbnail Bitmap object with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
android.graphics.Bitmap - Bitmap objects.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```


Returns a Thumbnail Bitmap object with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### renderToGraphics(IRenderingOptions options, Canvas graphics) {#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-}
```
public abstract void renderToGraphics(IRenderingOptions options, Canvas graphics)
```


Renders certain slide to a Graphics object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| graphics | android.graphics.Canvas | The object where to render to. |

### renderToGraphics(IRenderingOptions options, Canvas graphics, float scaleX, float scaleY) {#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-float-float-}
```
public abstract void renderToGraphics(IRenderingOptions options, Canvas graphics, float scaleX, float scaleY)
```


Renders certain slide to a Graphics object with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| graphics | android.graphics.Canvas | The object where to render to. |
| scaleX | float | The scale for rendering the slide (1.0 is 100%) in the x-axis direction. |
| scaleY | float | The scale for rendering the slide (1.0 is 100%) in the y-axis direction. |

### renderToGraphics(IRenderingOptions options, Canvas graphics, Size renderingSize) {#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-com.aspose.slides.android.Size-}
```
public abstract void renderToGraphics(IRenderingOptions options, Canvas graphics, Size renderingSize)
```


Renders certain slide to a Graphics object using specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| graphics | android.graphics.Canvas | The object where to render to. |
| renderingSize | [Size](../../com.aspose.slides.android/size) | The maximum dimensions (in pixels) that can be occupied by the rendered slide. |

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```


Returns or sets the layout slide for the current slide. Read/write [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```


Returns or sets the layout slide for the current slide. Read/write [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```


Allow to access notes slide, add and remove it. Read-only [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Returns:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```


Returns all slide comments added by specific author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Author of comments to find or null to return all comments. |

**Returns:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```


Saves content of slide as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Saves content of slide as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### remove() {#remove--}
```
public abstract void remove()
```


Removes slide from presentation.

### reset() {#reset--}
```
public abstract void reset()
```


Resets position, size and formatting of every shape that has a prototype on LayoutSlide.

