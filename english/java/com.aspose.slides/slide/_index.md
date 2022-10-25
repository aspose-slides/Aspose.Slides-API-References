---
title: Slide
second_title: Aspose.Slides for Java API Reference
description: Represents a slide in a presentation.
type: docs
weight: 499
url: /java/com.aspose.slides/slide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Represents a slide in a presentation.
## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns HeaderFooter manager of the slide. |
| [getThemeManager()](#getThemeManager--) | Returns the overriding theme manager. |
| [getSlideNumber()](#getSlideNumber--) | Returns a number of slide. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Returns a number of slide. |
| [getHidden()](#getHidden--) | Determines whether the specified slide is hidden during a slide show. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determines whether the specified slide is hidden during a slide show. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifies if shapes on the master slide should be shown on slides or not. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifies if shapes on the master slide should be shown on slides or not. |
| [getThumbnail(float scaleX, float scaleY)](#getThumbnail-float-float-) | Returns a Thumbnail Bitmap object with custom scaling. |
| [getThumbnail()](#getThumbnail--) | Returns a Thumbnail Image object (20% of real size). |
| [getThumbnail(Dimension imageSize)](#getThumbnail-java.awt.Dimension-) | Returns a Thumbnail Bitmap object with specified size. |
| [getThumbnail(ITiffOptions options)](#getThumbnail-com.aspose.slides.ITiffOptions-) | Returns a Thumbnail tiff BufferedImage object with specified parameters. |
| [getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting)](#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-) | Returns a Thumbnail BufferedImage object. |
| [getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY)](#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-float-float-) | Returns a Thumbnail BufferedImage object with custom scaling. |
| [getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, Dimension imageSize)](#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Dimension-) | Returns a Thumbnail BufferedImage object with specified size. |
| [getThumbnail(IRenderingOptions options)](#getThumbnail-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail BufferedImage object. |
| [getThumbnail(IRenderingOptions options, float scaleX, float scaleY)](#getThumbnail-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail BufferedImage object with custom scaling. |
| [getThumbnail(IRenderingOptions options, Dimension imageSize)](#getThumbnail-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Returns a Thumbnail BufferedImage object with specified size. |
| [renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics, int width, int height)](#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Graphics2D-int-int-) | Renders certain slide to a Graphics object using specified size. |
| [renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics, float scale)](#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Graphics2D-float-) | Renders certain slide to a Graphics object using specified scale. |
| [renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics)](#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Graphics2D-) | Renders certain slide to a Graphics object. |
| [renderToGraphics(IRenderingOptions options, Graphics2D graphics)](#renderToGraphics-com.aspose.slides.IRenderingOptions-java.awt.Graphics2D-) | Renders certain slide to a Graphics object. |
| [renderToGraphics(IRenderingOptions options, Graphics2D graphics, float scaleX, float scaleY)](#renderToGraphics-com.aspose.slides.IRenderingOptions-java.awt.Graphics2D-float-float-) | Renders certain slide to a Graphics object with custom scaling. |
| [renderToGraphics(IRenderingOptions options, Graphics2D graphics, Dimension renderingSize)](#renderToGraphics-com.aspose.slides.IRenderingOptions-java.awt.Graphics2D-java.awt.Dimension-) | Renders certain slide to a Graphics object using specified size. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Saves content of slide as SVG file. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Saves content of slide as SVG file. |
| [remove()](#remove--) | Removes slide from presentation. |
| [getLayoutSlide()](#getLayoutSlide--) | Returns or sets the layout slide for the current slide. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Returns or sets the layout slide for the current slide. |
| [reset()](#reset--) | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Allow to access notes slide, add and remove it. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Returns all slide comments added by specific author. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```


Returns HeaderFooter manager of the slide. Read-only [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Returns:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Returns the overriding theme manager. Read-only [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Returns:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Returns a number of slide. Index of slide in ([Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides)) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int.

**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Returns a number of slide. Index of slide in ([Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides)) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


Determines whether the specified slide is hidden during a slide show. Read/write boolean.

**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


Determines whether the specified slide is hidden during a slide show. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean.

**Returns:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getThumbnail(float scaleX, float scaleY) {#getThumbnail-float-float-}
```
public final BufferedImage getThumbnail(float scaleX, float scaleY)
```


Returns a Thumbnail Bitmap object with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
java.awt.image.BufferedImage - Bitmap object.
### getThumbnail() {#getThumbnail--}
```
public final BufferedImage getThumbnail()
```


Returns a Thumbnail Image object (20% of real size).

**Returns:**
java.awt.image.BufferedImage
### getThumbnail(Dimension imageSize) {#getThumbnail-java.awt.Dimension-}
```
public final BufferedImage getThumbnail(Dimension imageSize)
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
public final BufferedImage getThumbnail(ITiffOptions options)
```


Returns a Thumbnail tiff BufferedImage object with specified parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff options. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage object.
### getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting) {#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-}
```
public final BufferedImage getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting)
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
public final BufferedImage getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY)
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
### getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, Dimension imageSize) {#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Dimension-}
```
public final BufferedImage getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, Dimension imageSize)
```


Returns a Thumbnail BufferedImage object with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage objects.
### getThumbnail(IRenderingOptions options) {#getThumbnail-com.aspose.slides.IRenderingOptions-}
```
public final BufferedImage getThumbnail(IRenderingOptions options)
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
public final BufferedImage getThumbnail(IRenderingOptions options, float scaleX, float scaleY)
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
public final BufferedImage getThumbnail(IRenderingOptions options, Dimension imageSize)
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
public final void renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics, int width, int height)
```


Renders certain slide to a Graphics object using specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | java.awt.Graphics2D | The object where to render to. |
| width | int | The maximum width (in pixels) that can be occupied by the rendered slide. |
| height | int | The maximum height (in pixels) that can be occupied by the rendered slide. |

### renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics, float scale) {#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Graphics2D-float-}
```
public final void renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics, float scale)
```


Renders certain slide to a Graphics object using specified scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | java.awt.Graphics2D | The object where to render to. |
| scale | float | The scale for rendering the slide (1.0 is 100%). |

### renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics) {#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Graphics2D-}
```
public final void renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Graphics2D graphics)
```


Renders certain slide to a Graphics object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | java.awt.Graphics2D | The object where to render to. |

### renderToGraphics(IRenderingOptions options, Graphics2D graphics) {#renderToGraphics-com.aspose.slides.IRenderingOptions-java.awt.Graphics2D-}
```
public final void renderToGraphics(IRenderingOptions options, Graphics2D graphics)
```


Renders certain slide to a Graphics object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| graphics | java.awt.Graphics2D | The object where to render to. |

### renderToGraphics(IRenderingOptions options, Graphics2D graphics, float scaleX, float scaleY) {#renderToGraphics-com.aspose.slides.IRenderingOptions-java.awt.Graphics2D-float-float-}
```
public final void renderToGraphics(IRenderingOptions options, Graphics2D graphics, float scaleX, float scaleY)
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
public final void renderToGraphics(IRenderingOptions options, Graphics2D graphics, Dimension renderingSize)
```


Renders certain slide to a Graphics object using specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| graphics | java.awt.Graphics2D | The object where to render to. |
| renderingSize | java.awt.Dimension | The maximum dimensions (in pixels) that can be occupied by the rendered slide. |

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```


Saves content of slide as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Saves content of slide as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### remove() {#remove--}
```
public final void remove()
```


Removes slide from presentation.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```


Returns or sets the layout slide for the current slide. Read/write [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```


Returns or sets the layout slide for the current slide. Read/write [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```


Resets position, size and formatting of every shape that has a prototype on LayoutSlide.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```


Allow to access notes slide, add and remove it. Read-only [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Returns:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```


Returns all slide comments added by specific author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Author of comments to find or null to return all comments. |

**Returns:**
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


Joins runs with same formatting in all paragraphs in all acceptable shapes.

