---
title: ISlide
second_title: Aspose.Slides for Java API Reference
description:  Represents a slide in a presentation.
type: docs
weight: 1024
url: /java/com.aspose.slides/islide/
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
| [getThumbnail()](#getThumbnail--) | Returns a Thumbnail Image object (20% of real size). |
| [getThumbnail(Dimension imageSize)](#getThumbnail-java.awt.Dimension-) | Returns a Thumbnail Bitmap object with specified size. |
| [getThumbnail(ITiffOptions options)](#getThumbnail-com.aspose.slides.ITiffOptions-) | Returns a Thumbnail tiff bitmap object with specified parameters. |
| [getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting)](#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-) | Returns a Thumbnail BufferedImage object. |
| [getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY)](#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-float-float-) | Returns a Thumbnail BufferedImage object with custom scaling. |
| [getThumbnail(INotesCommentsLayoutingOptions options, Dimension imageSize)](#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Dimension-) | Returns a Thumbnail BufferedImage object with specified size. |
| [getThumbnail(IRenderingOptions options)](#getThumbnail-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail BufferedImage object. |
| [getThumbnail(IRenderingOptions options, float scaleX, float scaleY)](#getThumbnail-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail BufferedImage object with custom scaling. |
| [getThumbnail(IRenderingOptions options, Dimension imageSize)](#getThumbnail-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Returns a Thumbnail BufferedImage object with specified size. |
| [renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics, int width, int height)](#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Graphics2D-int-int-) | Renders certain slide to a Graphics object. |
| [renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics, float scale)](#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Graphics2D-float-) | Renders certain slide to a Graphics object. |
| [renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics)](#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Graphics2D-) | Renders certain slide to a Graphics object. |
| [renderToGraphics(IRenderingOptions options, Graphics2D graphics)](#renderToGraphics-com.aspose.slides.IRenderingOptions-java.awt.Graphics2D-) | Renders certain slide to a Graphics object. |
| [renderToGraphics(IRenderingOptions options, Graphics2D graphics, float scaleX, float scaleY)](#renderToGraphics-com.aspose.slides.IRenderingOptions-java.awt.Graphics2D-float-float-) | Renders certain slide to a Graphics object with custom scaling. |
| [renderToGraphics(IRenderingOptions options, Graphics2D graphics, Dimension renderingSize)](#renderToGraphics-com.aspose.slides.IRenderingOptions-java.awt.Graphics2D-java.awt.Dimension-) | Renders certain slide to a Graphics object using specified size. |
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


Returns a number of slide. Index of slide in ([IPresentation\#getSlides](../../com.aspose.slides/ipresentation\#getSlides)) collection is always equal to SlideNumber - 1. Read/write int.

**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```


Returns a number of slide. Index of slide in ([IPresentation\#getSlides](../../com.aspose.slides/ipresentation\#getSlides)) collection is always equal to SlideNumber - 1. Read/write int.

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
public abstract BufferedImage getThumbnail(float scaleX, float scaleY)
```


Returns a Thumbnail Bitmap object with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
java.awt.image.BufferedImage - Bitmap object java.awt.image.BufferedImage
### getThumbnail() {#getThumbnail--}
```
public abstract BufferedImage getThumbnail()
```


Returns a Thumbnail Image object (20% of real size).

**Returns:**
java.awt.image.BufferedImage - Bitmap object java.awt.image.BufferedImage
### getThumbnail(Dimension imageSize) {#getThumbnail-java.awt.Dimension-}
```
public abstract BufferedImage getThumbnail(Dimension imageSize)
```


Returns a Thumbnail Bitmap object with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
java.awt.image.BufferedImage - Bitmap object.
### getThumbnail(ITiffOptions options) {#getThumbnail-com.aspose.slides.ITiffOptions-}
```
public abstract BufferedImage getThumbnail(ITiffOptions options)
```


Returns a Thumbnail tiff bitmap object with specified parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff options. |

**Returns:**
java.awt.image.BufferedImage - Bitmap object.
### getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting) {#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-}
```
public abstract BufferedImage getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting)
```


Returns a Thumbnail BufferedImage object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage objects.
### getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY) {#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-float-float-}
```
public abstract BufferedImage getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY)
```


Returns a Thumbnail BufferedImage object with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage objects.
### getThumbnail(INotesCommentsLayoutingOptions options, Dimension imageSize) {#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Dimension-}
```
public abstract BufferedImage getThumbnail(INotesCommentsLayoutingOptions options, Dimension imageSize)
```


Returns a Thumbnail BufferedImage object with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage objects.
### getThumbnail(IRenderingOptions options) {#getThumbnail-com.aspose.slides.IRenderingOptions-}
```
public abstract BufferedImage getThumbnail(IRenderingOptions options)
```


Returns a Thumbnail BufferedImage object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage objects.
### getThumbnail(IRenderingOptions options, float scaleX, float scaleY) {#getThumbnail-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract BufferedImage getThumbnail(IRenderingOptions options, float scaleX, float scaleY)
```


Returns a Thumbnail BufferedImage object with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage objects.
### getThumbnail(IRenderingOptions options, Dimension imageSize) {#getThumbnail-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract BufferedImage getThumbnail(IRenderingOptions options, Dimension imageSize)
```


Returns a Thumbnail BufferedImage object with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage objects.
### renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics, int width, int height) {#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Graphics2D-int-int-}
```
public abstract void renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics, int width, int height)
```


Renders certain slide to a Graphics object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | java.awt.Graphics2D | The object where to render to. |
| width | int | The maximum width (in pixels) that can be occupied by the rendered slide. |
| height | int | The maximum height (in pixels) that can be occupied by the rendered slide. |

### renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics, float scale) {#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Graphics2D-float-}
```
public abstract void renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics, float scale)
```


Renders certain slide to a Graphics object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | java.awt.Graphics2D | The object where to render to. |
| scale | float | The scale for rendering the slide (1.0 is 100%). |

### renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics) {#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Graphics2D-}
```
public abstract void renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics)
```


Renders certain slide to a Graphics object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | java.awt.Graphics2D | The object where to render to. |

### renderToGraphics(IRenderingOptions options, Graphics2D graphics) {#renderToGraphics-com.aspose.slides.IRenderingOptions-java.awt.Graphics2D-}
```
public abstract void renderToGraphics(IRenderingOptions options, Graphics2D graphics)
```


Renders certain slide to a Graphics object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| graphics | java.awt.Graphics2D | The object where to render to. |

### renderToGraphics(IRenderingOptions options, Graphics2D graphics, float scaleX, float scaleY) {#renderToGraphics-com.aspose.slides.IRenderingOptions-java.awt.Graphics2D-float-float-}
```
public abstract void renderToGraphics(IRenderingOptions options, Graphics2D graphics, float scaleX, float scaleY)
```


Renders certain slide to a Graphics object with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| graphics | java.awt.Graphics2D | The object where to render to. |
| scaleX | float | The scale for rendering the slide (1.0 is 100%) in the x-axis direction. |
| scaleY | float | The scale for rendering the slide (1.0 is 100%) in the y-axis direction. |

### renderToGraphics(IRenderingOptions options, Graphics2D graphics, Dimension renderingSize) {#renderToGraphics-com.aspose.slides.IRenderingOptions-java.awt.Graphics2D-java.awt.Dimension-}
```
public abstract void renderToGraphics(IRenderingOptions options, Graphics2D graphics, Dimension renderingSize)
```


Renders certain slide to a Graphics object using specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| graphics | java.awt.Graphics2D | The object where to render to. |
| renderingSize | java.awt.Dimension | The maximum dimensions (in pixels) that can be occupied by the rendered slide. |

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
com.aspose.slides.IComment[] - Array of [IComment](../com.aspose.slides/icomment).
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

