---
title: Slide
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slide/
---

## Slide class

  Represents a slide in a presentation.
 

## Functions

| Name | Description |
| --- | --- |
| [getHeaderFooterManager]() | Returns HeaderFooter manager of the slide. Read-only ISlideHeaderFooterManager. |

### Result
[SlideHeaderFooterManager](../../slideheaderfootermanager)


---


| [getHidden]() | Determines whether the specified slide is hidden during a slide show. Read/write boolean. |

### Result
boolean


---


| [getLayoutSlide]() | Returns or sets the layout slide for the current slide. Read/write ILayoutSlide. |

### Result
[LayoutSlide](../../layoutslide)


---


| [getNotesSlideManager]() | Allow to access notes slide, add and remove it. Read-only INotesSlideManager. |

### Result
[NotesSlideManager](../../notesslidemanager)


---


| [getShowMasterShapes]() | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |

### Result
boolean


---


| [getSlideComments]([CommentAuthor](../commentauthor)) | Returns all slide comments added by specific author. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| author | [CommentAuthor](../../commentauthor) | Author of comments to find or null to return all comments. |

### Result
[Comment](../../comment), [ModernComment](../../moderncomment)


---


| [getSlideNumber]() | Returns a number of slide. Index of slide in ( Presentation#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int. |

### Result
int


---


| [getThemeManager]() | Returns the overriding theme manager. Read-only IOverrideThemeManager. |

### Result
[NotesSlideThemeManager](../../notesslidethememanager), [ChartThemeManager](../../chartthememanager), [BaseOverrideThemeManager](../../baseoverridethememanager), [LayoutSlideThemeManager](../../layoutslidethememanager), [SlideThemeManager](../../slidethememanager)


---


| [getThumbnail](float, float) | Returns a Thumbnail Bitmap object with custom scaling. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

### Result
BufferedImage


---


| [getThumbnail]() | Returns a Thumbnail Image object (20% of real size). |

### Result
BufferedImage


---


| [getThumbnail](Dimension) | Returns a Thumbnail Bitmap object with specified size. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| imageSize | Dimension | Size of the image to create. |

### Result
BufferedImage


---


| [getThumbnail]([TiffOptions](../tiffoptions)) | Returns a Thumbnail tiff BufferedImage object with specified parameters. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../../tiffoptions) | Tiff options. |

### Result
BufferedImage

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull. |


---


| [getThumbnail]([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Returns a Thumbnail BufferedImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../../notescommentslayoutingoptions) | Options for notes and comments layouting. |

### Result
BufferedImage

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [getThumbnail]([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), float, float) | Returns a Thumbnail BufferedImage object with custom scaling. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

### Result
BufferedImage

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [getThumbnail]([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), Dimension) | Returns a Thumbnail BufferedImage object with specified size. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| imageSize | Dimension | Size of the image to create. |

### Result
BufferedImage

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [getThumbnail]([RenderingOptions](../renderingoptions)) | Returns a Thumbnail BufferedImage object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../../renderingoptions) | Rendering options. |

### Result
BufferedImage

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [getThumbnail]([RenderingOptions](../renderingoptions), float, float) | Returns a Thumbnail BufferedImage object with custom scaling. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

### Result
BufferedImage

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [getThumbnail]([RenderingOptions](../renderingoptions), Dimension) | Returns a Thumbnail BufferedImage object with specified size. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| imageSize | Dimension | Size of the image to create. |

### Result
BufferedImage

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [joinPortionsWithSameFormatting]() | Joins runs with same formatting in all paragraphs in all acceptable shapes. |


---


| [remove]() | Removes slide from presentation. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if slide is already removed from presentation. |


---


| [renderToGraphics]([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), Graphics2D, int, int) | Renders certain slide to a Graphics object using specified size. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | Graphics2D | The object where to render to. |
| width | int | The maximum width (in pixels) that can be occupied by the rendered slide. |
| height | int | The maximum height (in pixels) that can be occupied by the rendered slide. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [renderToGraphics]([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), Graphics2D, float) | Renders certain slide to a Graphics object using specified scale. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | Graphics2D | The object where to render to. |
| scale | float | The scale for rendering the slide (1.0 is 100%). |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [renderToGraphics]([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), Graphics2D) | Renders certain slide to a Graphics object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | Graphics2D | The object where to render to. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [renderToGraphics]([RenderingOptions](../renderingoptions), Graphics2D) | Renders certain slide to a Graphics object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| graphics | Graphics2D | The object where to render to. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [renderToGraphics]([RenderingOptions](../renderingoptions), Graphics2D, float, float) | Renders certain slide to a Graphics object with custom scaling. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| graphics | Graphics2D | The object where to render to. |
| scaleX | float | The scale for rendering the slide (1.0 is 100%) in the x-axis direction. |
| scaleY | float | The scale for rendering the slide (1.0 is 100%) in the y-axis direction. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [renderToGraphics]([RenderingOptions](../renderingoptions), Graphics2D, Dimension) | Renders certain slide to a Graphics object using specified size. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| graphics | Graphics2D | The object where to render to. |
| renderingSize | Dimension | The maximum dimensions (in pixels) that can be occupied by the rendered slide. |

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


| [reset]() | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |


---


| [setHidden](boolean) | Determines whether the specified slide is hidden during a slide show. Read/write boolean. |


---


| [setLayoutSlide]([LayoutSlide](../layoutslide)) | Returns or sets the layout slide for the current slide. Read/write ILayoutSlide. |


---


| [setShowMasterShapes](boolean) | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |


---


| [setSlideNumber](int) | Returns a number of slide. Index of slide in ( Presentation#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int. |


---


| [writeAsSvgToStream ](Slide, WriteStream) | Saves content of slide as SVG file. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slide | Slide  | link to self |
| stream | WriteStream | Target stream |


---


| [writeAsSvgToStream ](Slide, WriteStream, [SVGOptions](../svgoptions)) | Saves content of slide as SVG file. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slide | Slide  | link to self |
| stream | WriteStream | Target stream |
| svgOptions | [SVGOptions](../../svgoptions) | SVG generation options |


---


