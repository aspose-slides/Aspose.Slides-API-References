---
title: Slide
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/slide/
---

## Slide class

  Represents a slide in a presentation.
 
### getHeaderFooterManager {#getHeaderFooterManager}

| Name | Description |
| --- | --- |
| getHeaderFooterManager() | Returns HeaderFooter manager of the slide. Read-only ISlideHeaderFooterManager. |

 **Returns:**
[SlideHeaderFooterManager](../slideheaderfootermanager)


---


### getHidden {#getHidden}

| Name | Description |
| --- | --- |
| getHidden() | Determines whether the specified slide is hidden during a slide show. Read/write boolean. |

 **Returns:**
boolean


---


### getImage {#getImage}

| Name | Description |
| --- | --- |
| getImage(float, float) | Returns a Thumbnail Image object with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

 **Returns:**
SlidesImage


---


### getImage {#getImage}

| Name | Description |
| --- | --- |
| getImage() | Returns a Thumbnail Image object (20% of real size). |

 **Returns:**
SlidesImage


---


### getImage {#getImage}

| Name | Description |
| --- | --- |
| getImage(Dimension) | Returns a Thumbnail Image object with specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| imageSize | Dimension | Size of the image to create. |

 **Returns:**
SlidesImage


---


### getImage {#getImage}

| Name | Description |
| --- | --- |
| getImage([TiffOptions](../tiffoptions)) | Returns a Thumbnail tiff image object with specified parameters. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../tiffoptions) | Tiff options. |

 **Returns:**
SlidesImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull. |


---


### getImage {#getImage}

| Name | Description |
| --- | --- |
| getImage([RenderingOptions](../renderingoptions)) | Returns a Thumbnail Image object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |

 **Returns:**
SlidesImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### getImage {#getImage}

| Name | Description |
| --- | --- |
| getImage([RenderingOptions](../renderingoptions), float, float) | Returns a Thumbnail Image object with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

 **Returns:**
SlidesImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### getImage {#getImage}

| Name | Description |
| --- | --- |
| getImage([RenderingOptions](../renderingoptions), Dimension) | Returns a Thumbnail Image object with specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| imageSize | Dimension | Size of the image to create. |

 **Returns:**
SlidesImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### getLayoutSlide {#getLayoutSlide}

| Name | Description |
| --- | --- |
| getLayoutSlide() | Returns or sets the layout slide for the current slide. Read/write ILayoutSlide. |

 **Returns:**
[LayoutSlide](../layoutslide)


---


### getNotesSlideManager {#getNotesSlideManager}

| Name | Description |
| --- | --- |
| getNotesSlideManager() | Allow to access notes slide, add and remove it. Read-only INotesSlideManager. |

 **Returns:**
[NotesSlideManager](../notesslidemanager)


---


### getShowMasterShapes {#getShowMasterShapes}

| Name | Description |
| --- | --- |
| getShowMasterShapes() | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |

 **Returns:**
boolean


---


### getSlideComments {#getSlideComments}

| Name | Description |
| --- | --- |
| getSlideComments([CommentAuthor](../commentauthor)) | Returns all slide comments added by specific author. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| author | [CommentAuthor](../commentauthor) | Author of comments to find or null to return all comments. |

 **Returns:**
[ModernComment](../moderncomment), [Comment](../comment)


---


### getSlideNumber {#getSlideNumber}

| Name | Description |
| --- | --- |
| getSlideNumber() | Returns a number of slide. Index of slide in ( Presentation#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int. |

 **Returns:**
int


---


### getThemeManager {#getThemeManager}

| Name | Description |
| --- | --- |
| getThemeManager() | Returns the overriding theme manager. Read-only IOverrideThemeManager. |

 **Returns:**
[NotesSlideThemeManager](../notesslidethememanager), [LayoutSlideThemeManager](../layoutslidethememanager), [ChartThemeManager](../chartthememanager), [SlideThemeManager](../slidethememanager), [BaseOverrideThemeManager](../baseoverridethememanager)


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail(float, float) | Returns a Thumbnail Bitmap object with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

 **Returns:**
BufferedImage


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail() | Returns a Thumbnail Image object (20% of real size). |

 **Returns:**
BufferedImage


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail([RenderingOptions](../renderingoptions)) | Returns a Thumbnail Bitmap object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |

 **Returns:**
BufferedImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail(Dimension) | Returns a Thumbnail Bitmap object with specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| imageSize | Dimension | Size of the image to create. |

 **Returns:**
BufferedImage


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail([TiffOptions](../tiffoptions)) | Returns a Thumbnail tiff image object with specified parameters. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../tiffoptions) | Tiff options. |

 **Returns:**
BufferedImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull. |


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail([RenderingOptions](../renderingoptions), float, float) | Returns a Thumbnail BufferedImage object with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

 **Returns:**
BufferedImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail([RenderingOptions](../renderingoptions), Dimension) | Returns a Thumbnail BufferedImage object with specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| imageSize | Dimension | Size of the image to create. |

 **Returns:**
BufferedImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting() | Joins runs with same formatting in all paragraphs in all acceptable shapes. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove() | Removes slide from presentation. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if slide is already removed from presentation. |


---


### renderToGraphics {#renderToGraphics}

| Name | Description |
| --- | --- |
| renderToGraphics([RenderingOptions](../renderingoptions), Graphics2D) | Renders certain slide to a Graphics object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| graphics | Graphics2D | The object where to render to. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### renderToGraphics {#renderToGraphics}

| Name | Description |
| --- | --- |
| renderToGraphics([RenderingOptions](../renderingoptions), Graphics2D, float, float) | Renders certain slide to a Graphics object with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| graphics | Graphics2D | The object where to render to. |
| scaleX | float | The scale for rendering the slide (1.0 is 100%) in the x-axis direction. |
| scaleY | float | The scale for rendering the slide (1.0 is 100%) in the y-axis direction. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### renderToGraphics {#renderToGraphics}

| Name | Description |
| --- | --- |
| renderToGraphics([RenderingOptions](../renderingoptions), Graphics2D, Dimension) | Renders certain slide to a Graphics object using specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| graphics | Graphics2D | The object where to render to. |
| renderingSize | Dimension | The maximum dimensions (in pixels) that can be occupied by the rendered slide. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### reset {#reset}

| Name | Description |
| --- | --- |
| reset() | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |


---


### setHidden {#setHidden}

| Name | Description |
| --- | --- |
| setHidden(boolean) | Determines whether the specified slide is hidden during a slide show. Read/write boolean. |


---


### setLayoutSlide {#setLayoutSlide}

| Name | Description |
| --- | --- |
| setLayoutSlide([LayoutSlide](../layoutslide)) | Returns or sets the layout slide for the current slide. Read/write ILayoutSlide. |


---


### setShowMasterShapes {#setShowMasterShapes}

| Name | Description |
| --- | --- |
| setShowMasterShapes(boolean) | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |


---


### setSlideNumber {#setSlideNumber}

| Name | Description |
| --- | --- |
| setSlideNumber(int) | Returns a number of slide. Index of slide in ( Presentation#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int. |


---


### writeAsSvgToBytes  {#writeAsSvgToBytes }

| Name | Description |
| --- | --- |
| writeAsSvgToBytes () | Saves content of slide as SVG file. |

 **Returns:**
Bytes[]


---


### writeAsSvgToBytes  {#writeAsSvgToBytes }

| Name | Description |
| --- | --- |
| writeAsSvgToBytes ([SVGOptions](../svgoptions)) | Saves content of slide as SVG file. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| svgOptions | [SVGOptions](../svgoptions) | SVG generation options |

 **Returns:**
Bytes[]


---


