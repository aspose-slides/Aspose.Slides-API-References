---
title: getThumbnail
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/slide/getthumbnail/
---

## getThumbnail(float scaleX, float scaleY)  method

 Returns a Thumbnail Bitmap object with custom scaling.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

### Returns
BufferedImage


---


## getThumbnail()  method

 Returns a Thumbnail Image object (20% of real size).
 

### Returns
BufferedImage


---


## getThumbnail(Dimension imageSize)  method

 Returns a Thumbnail Bitmap object with specified size.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| imageSize | Dimension | Size of the image to create. |

### Returns
BufferedImage


---


## getThumbnail([TiffOptions](../../tiffoptions) options)  method

 Returns a Thumbnail tiff BufferedImage object with specified parameters.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../../tiffoptions) | Tiff options. |

### Returns
BufferedImage

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull. |


---


## getThumbnail([NotesCommentsLayoutingOptions](../../notescommentslayoutingoptions) notesCommentsLayouting)  method

 Returns a Thumbnail BufferedImage object.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../../notescommentslayoutingoptions) | Options for notes and comments layouting. |

### Returns
BufferedImage

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


## getThumbnail([NotesCommentsLayoutingOptions](../../notescommentslayoutingoptions) notesCommentsLayouting, float scaleX, float scaleY)  method

 Returns a Thumbnail BufferedImage object with custom scaling.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

### Returns
BufferedImage

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


## getThumbnail([NotesCommentsLayoutingOptions](../../notescommentslayoutingoptions) notesCommentsLayouting, Dimension imageSize)  method

 Returns a Thumbnail BufferedImage object with specified size.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| imageSize | Dimension | Size of the image to create. |

### Returns
BufferedImage

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


## getThumbnail([RenderingOptions](../../renderingoptions) options)  method

 Returns a Thumbnail BufferedImage object.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../../renderingoptions) | Rendering options. |

### Returns
BufferedImage

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


## getThumbnail([RenderingOptions](../../renderingoptions) options, float scaleX, float scaleY)  method

 Returns a Thumbnail BufferedImage object with custom scaling.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

### Returns
BufferedImage

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


## getThumbnail([RenderingOptions](../../renderingoptions) options, Dimension imageSize)  method

 Returns a Thumbnail BufferedImage object with specified size.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| imageSize | Dimension | Size of the image to create. |

### Returns
BufferedImage

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


