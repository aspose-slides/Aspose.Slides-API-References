---
title: getThumbnail
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 90
url: /php-java/slide/getthumbnail/
---

## getThumbnail(float scaleX, float scaleY)  method

 Returns a Thumbnail Bitmap object with custom scaling.
 

 The following example shows how to generate thumbnails from PowerPoint Presentation.
 
```php
  // Instantiate a Presentation class that represents the presentation file
  $pres = new Presentation("ThumbnailFromSlide.pptx");
  try {
    // Access the first slide
    $sld = $pres->getSlides()->get_Item(0);
    // Create a full scale image
    $bmp = $sld->getThumbnail(1.0, 1.0);
    // Save the image to disk in PNG format
    ImageIO->write($bmp, "PNG", new File("Thumbnail_out.png"));
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

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
 

 The following example shows how to converting slides to images with custom sizes using Java.
 
```php
  $pres = new Presentation("Presentation.pptx");
  try {
    // Converts the first slide in the presentation to a Bitmap with the specified size
    $bmp = $pres->getSlides()->get_Item(0)->getThumbnail(new Dimension(1820, 1040));
    // Saves the image in the JPEG format
    ImageIO->write($bmp, "JPG", new File("Slide_0.jpg"));
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

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
 

 The following example shows how to converting slides With notes and comments to Images using C#.
 
```php
  $pres = new Presentation("PresentationNotesComments.pptx");
  try {
    // Creates the rendering options
    $options = new RenderingOptions();
    // Sets the position of the notes on the page
    $options->getNotesCommentsLayouting()->setNotesPosition(NotesPositions.BottomTruncated);
    // Sets the position of the comments on the page
    $options->getNotesCommentsLayouting()->setCommentsPosition(CommentsPositions.Right);
    // Sets the width of the comment output area
    $options->getNotesCommentsLayouting()->setCommentsAreaWidth(500);
    // Sets the color for the comments area
    $options->getNotesCommentsLayouting()->setCommentsAreaColor(Color::WHITE);
    // Converts the first slide of the presentation to a Bitmap object
    $bmp = $pres->getSlides()->get_Item(0)->getThumbnail($options, 2.0, 2.0);
    // Saves the image in the GIF format
    ImageIO->write($bmp, "GIF", new File("Slide_Notes_Comments_0.gif"));
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

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


