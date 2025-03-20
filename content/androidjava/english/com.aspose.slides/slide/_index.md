---
title: Slide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a slide in a presentation.
type: docs
url: /com.aspose.slides/slide/
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
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Returns a Thumbnail Image object with custom scaling. |
| [getThumbnail()](#getThumbnail--) | Returns a Thumbnail Image object (20% of real size). |
| [getImage()](#getImage--) | Returns a Thumbnail Image object (20% of real size). |
| [getThumbnail(IRenderingOptions options)](#getThumbnail-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail Bitmap object. |
| [getThumbnail(Size imageSize)](#getThumbnail-com.aspose.slides.android.Size-) | Returns a Thumbnail Image object with specified size. |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Returns a Thumbnail Image object with specified size. |
| [getThumbnail(ITiffOptions options)](#getThumbnail-com.aspose.slides.ITiffOptions-) | Returns a Thumbnail tiff image object with specified parameters. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Returns a Thumbnail tiff image object with specified parameters. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail Image object. |
| [getThumbnail(IRenderingOptions options, float scaleX, float scaleY)](#getThumbnail-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail Image object with custom scaling. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail Image object with custom scaling. |
| [getThumbnail(IRenderingOptions options, Size imageSize)](#getThumbnail-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Returns a Thumbnail android.graphics.Bitmap object with specified size. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Returns a Thumbnail Image object with specified size. |
| [renderToGraphics(IRenderingOptions options, Canvas graphics)](#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-) | Renders certain slide to a Graphics object. |
| [renderToGraphics(IRenderingOptions options, Canvas graphics, float scaleX, float scaleY)](#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-float-float-) | Renders certain slide to a Graphics object with custom scaling. |
| [renderToGraphics(IRenderingOptions options, Canvas graphics, Size renderingSize)](#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-com.aspose.slides.android.Size-) | Renders certain slide to a Graphics object using specified size. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Saves the slide content as an SVG file. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Saves the slide content as an SVG file. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Saves the slide content as an EMF file. |
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


Returns a number of slide. Index of slide in [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int.

**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Returns a number of slide. Index of slide in [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int.

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
public final Bitmap getThumbnail(float scaleX, float scaleY)
```


Returns a Thumbnail Bitmap object with custom scaling.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  // Instantiate a Presentation class that represents the presentation file
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Access the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Create a full scale image
>      android.graphics.Bitmap bmp = sld.getThumbnail(1f, 1f);
>      // Save the image to disk in PNG format
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("Thumbnail_out.png");
>          bmp.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try
>  {
>      for (ISlide slide : pres.getSlides())
>      {
>          // Converts the slide in the presentation to a Bitmap object
>          android.graphics.Bitmap bmp = slide.getThumbnail();
>          // Saves the image in the PNG format
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream("Thumbnail_out_" + slide.getSlideNumber() + ".png");
>              bmp.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try
>  {
>      for (ISlide slide : pres.getSlides())
>      {
>          // Converts the slide in the presentation to a Bitmap object
>          android.graphics.Bitmap bmp = slide.getThumbnail();
>          // Saves the image in the JPG format
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream("Thumbnail_out" + slide.getSlideNumber() + ".jpg");
>              bmp.compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, fos);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try
>  {
>      // Define dimensions
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Get scaled values of X and Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide slide : pres.getSlides())
>      {
>          // Converts the first slide in the presentation to a Bitmap object
>          android.graphics.Bitmap bmp = slide.getThumbnail(ScaleX, ScaleY);
>          // Saves the image in the JPG format
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream("Slide_" + slide.getSlideNumber() + ".jpg");
>              bmp.compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, fos);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
android.graphics.Bitmap - Bitmap object.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```


Returns a Thumbnail Image object with custom scaling.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Access the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Create a full scale image
>      IImage bmp = sld.getImage(1f, 1f);
>      // Save the image to disk in JPEG format
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converts the first slide in the presentation to a Bitmap object
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Saves the image in the PNG format
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // Create a full scale image
>          IImage bmp = sld.getImage(1f, 1f);
>          // Save the image to disk in JPEG format
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // Define dimensions
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Get scaled values of X and Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Create a full scale image
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Save the image to disk in JPEG format
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - IImage object.
### getThumbnail() {#getThumbnail--}
```
public final Bitmap getThumbnail()
```


Returns a Thumbnail Image object (20% of real size).

**Returns:**
android.graphics.Bitmap
### getImage() {#getImage--}
```
public final IImage getImage()
```


Returns a Thumbnail Image object (20% of real size).

**Returns:**
[IImage](../../com.aspose.slides/iimage)
### getThumbnail(IRenderingOptions options) {#getThumbnail-com.aspose.slides.IRenderingOptions-}
```
public final Bitmap getThumbnail(IRenderingOptions options)
```


Returns a Thumbnail Bitmap object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**Returns:**
android.graphics.Bitmap - Bitmap objects.
### getThumbnail(Size imageSize) {#getThumbnail-com.aspose.slides.android.Size-}
```
public final Bitmap getThumbnail(Size imageSize)
```


Returns a Thumbnail Image object with specified size.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using Java.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converts the first slide in the presentation to a Bitmap with the specified size
>      IImage image = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Saves the image in the JPEG format
>      image.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
android.graphics.Bitmap - Bitmap object.
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```


Returns a Thumbnail Image object with specified size.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converts the first slide in the presentation to a Bitmap with the specified size
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Saves the image in the JPEG format
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getThumbnail(ITiffOptions options) {#getThumbnail-com.aspose.slides.ITiffOptions-}
```
public final Bitmap getThumbnail(ITiffOptions options)
```


Returns a Thumbnail tiff image object with specified parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff options. |

**Returns:**
android.graphics.Bitmap - android.graphics.Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```


Returns a Thumbnail tiff image object with specified parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff options. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```


Returns a Thumbnail Image object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getThumbnail(IRenderingOptions options, float scaleX, float scaleY) {#getThumbnail-com.aspose.slides.IRenderingOptions-float-float-}
```
public final Bitmap getThumbnail(IRenderingOptions options, float scaleX, float scaleY)
```


Returns a Thumbnail Image object with custom scaling.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images using Java.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Create the rendering options
>      IRenderingOptions options = new RenderingOptions();
>      // Create notes and comments layouting options
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Sets the position of the notes on the page
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Sets the position of the comments on the page
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Sets the width of the comment output area
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Sets the color for the comments area
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Set layout options for rendering
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Converts the first slide of the presentation to a android.graphics.Bitmap object
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Saves the image in the GIF format
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
android.graphics.Bitmap - android.graphics.Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


Returns a Thumbnail Image object with custom scaling.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images using C#.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Create the rendering options
>      IRenderingOptions options = new RenderingOptions();
>      // Create notes and comments layouting options
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Sets the position of the notes on the page
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Sets the position of the comments on the page
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Sets the width of the comment output area
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Sets the color for the comments area
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Set layout options for rendering
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Converts the first slide of the presentation to a IImage object
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Saves the image in the GIF format
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

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
public final Bitmap getThumbnail(IRenderingOptions options, Size imageSize)
```


Returns a Thumbnail android.graphics.Bitmap object with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
android.graphics.Bitmap - android.graphics.Bitmap objects.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```


Returns a Thumbnail Image object with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### renderToGraphics(IRenderingOptions options, Canvas graphics) {#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-}
```
public final void renderToGraphics(IRenderingOptions options, Canvas graphics)
```


Renders certain slide to a Graphics object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| graphics | android.graphics.Canvas | The object where to render to. |

### renderToGraphics(IRenderingOptions options, Canvas graphics, float scaleX, float scaleY) {#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-float-float-}
```
public final void renderToGraphics(IRenderingOptions options, Canvas graphics, float scaleX, float scaleY)
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
public final void renderToGraphics(IRenderingOptions options, Canvas graphics, Size renderingSize)
```


Renders certain slide to a Graphics object using specified size.

--------------------

> ```
> The following example shows how to convert the first slide to the framed image with the RenderToGraphics method.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Gets the presentation slide size
>      com.aspose.slides.android.Size slideSize = new com.aspose.slides.android.Size(1820, 1040);
>      // Creates a Bitmap with the slide size
>      android.graphics.Bitmap image = android.graphics.Bitmap.createBitmap((int)slideSize.getWidth() + 50, (int)slideSize.getHeight() + 50, Bitmap.Config.ARGB_8888);
>      Canvas graphics = new Canvas(image);
>      Paint paint = new Paint();
>      paint.setStyle(Paint.Style.FILL);
>      paint.setColor(Color.RED);
>      graphics.drawRect(0, 0, (int)pres.getSlideSize().getSize().getWidth(), (int)pres.getSlideSize().getSize().getHeight(), paint);
>      graphics.translate(25, 25);
>      pres.getSlides().get_Item(0).renderToGraphics(new RenderingOptions(), graphics);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("Slide_0.png");
>          image.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to conversion process for a slide with notes using the RenderToGraphics.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Gets the presentation slide size
>      com.aspose.slides.android.Size notesSize = new com.aspose.slides.android.Size((int)pres.getNotesSize().getSize().getWidth(), (int)pres.getNotesSize().getSize().getHeight());
>      IRenderingOptions options = new RenderingOptions();
>      // Sets the position of the notes
>      options.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomTruncated);
>      // Creates a Bitmap with the slide size
>      android.graphics.Bitmap image = android.graphics.Bitmap.createBitmap((int)notesSize.getWidth(), (int)notesSize.getHeight(), Bitmap.Config.ARGB_8888);
>      Canvas graphics = new Canvas(image);
>      Paint paint = new Paint();
>      paint.setStyle(Paint.Style.FILL);
>      paint.setColor(Color.RED);
>      graphics.drawRect(0, 0, (int)pres.getSlideSize().getSize().getWidth(), (int)pres.getSlideSize().getSize().getHeight(), paint);
>      graphics.translate(25, 25);
>      pres.getSlides().get_Item(0).renderToGraphics(options, graphics, notesSize);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("Slide_0.png");
>          image.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| graphics | android.graphics.Canvas | The object where to render to. |
| renderingSize | [Size](../../com.aspose.slides.android/size) | The maximum dimensions (in pixels) that can be occupied by the rendered slide. |

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```


Saves the slide content as an SVG file.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Saves the first slide as an SVG file
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Saves the slide content as an SVG file.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Saves the first slide as an SVG file
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```


Saves the slide content as an EMF file.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Saves the first slide as a metafille
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

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

