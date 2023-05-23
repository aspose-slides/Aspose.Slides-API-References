---
title: Slide
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a slide in a presentation.
type: docs
weight: 503
url: /androidjava/com.aspose.slides/slide/
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
| [getThumbnail(Size imageSize)](#getThumbnail-com.aspose.slides.android.Size-) | Returns a Thumbnail Bitmap object with specified size. |
| [getThumbnail(ITiffOptions options)](#getThumbnail-com.aspose.slides.ITiffOptions-) | Returns a Thumbnail tiff android.graphics.Bitmap object with specified parameters. |
| [getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting)](#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-) | Returns a Thumbnail android.graphics.Bitmap object. |
| [getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY)](#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-float-float-) | Returns a Thumbnail android.graphics.Bitmap object with custom scaling. |
| [getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, Size imageSize)](#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-com.aspose.slides.android.Size-) | Returns a Thumbnail android.graphics.Bitmap object with specified size. |
| [getThumbnail(IRenderingOptions options)](#getThumbnail-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail android.graphics.Bitmap object. |
| [getThumbnail(IRenderingOptions options, float scaleX, float scaleY)](#getThumbnail-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail android.graphics.Bitmap object with custom scaling. |
| [getThumbnail(IRenderingOptions options, Size imageSize)](#getThumbnail-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Returns a Thumbnail android.graphics.Bitmap object with specified size. |
| [renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Canvas graphics, int width, int height)](#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-android.graphics.Canvas-int-int-) | Renders certain slide to a Graphics object using specified size. |
| [renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Canvas graphics, float scale)](#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-android.graphics.Canvas-float-) | Renders certain slide to a Graphics object using specified scale. |
| [renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Canvas graphics)](#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-android.graphics.Canvas-) | Renders certain slide to a Graphics object. |
| [renderToGraphics(IRenderingOptions options, Canvas graphics)](#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-) | Renders certain slide to a Graphics object. |
| [renderToGraphics(IRenderingOptions options, Canvas graphics, float scaleX, float scaleY)](#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-float-float-) | Renders certain slide to a Graphics object with custom scaling. |
| [renderToGraphics(IRenderingOptions options, Canvas graphics, Size renderingSize)](#renderToGraphics-com.aspose.slides.IRenderingOptions-android.graphics.Canvas-com.aspose.slides.android.Size-) | Renders certain slide to a Graphics object using specified size. |
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
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
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
>          } catch (IOException e) {
>              throw new RuntimeException(e);
>          } finally {
>              if (fos != null) {
>                  try {
>                      fos.close();
>                  } catch (IOException e) {
>                      e.printStackTrace();
>                  }
>              }
>          }
>      }
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
>          } catch (IOException e) {
>              throw new RuntimeException(e);
>          } finally {
>              if (fos != null) {
>                  try {
>                      fos.close();
>                  } catch (IOException e) {
>                      e.printStackTrace();
>                  }
>              }
>          }
>      }
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
>          } catch (IOException e) {
>              throw new RuntimeException(e);
>          } finally {
>              if (fos != null) {
>                  try {
>                      fos.close();
>                  } catch (IOException e) {
>                      e.printStackTrace();
>                  }
>              }
>          }
>      }
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
### getThumbnail() {#getThumbnail--}
```
public final Bitmap getThumbnail()
```


Returns a Thumbnail Image object (20% of real size).

**Returns:**
android.graphics.Bitmap
### getThumbnail(Size imageSize) {#getThumbnail-com.aspose.slides.android.Size-}
```
public final Bitmap getThumbnail(Size imageSize)
```


Returns a Thumbnail Bitmap object with specified size.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using Java.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converts the first slide in the presentation to a Bitmap with the specified size
>      android.graphics.Bitmap bmp = pres.getSlides().get_Item(0).getThumbnail(new com.aspose.slides.android.Size(1820, 1040));
>      // Saves the image in the JPEG format
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("Slide_0.jpg");
>          bmp.compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
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
### getThumbnail(ITiffOptions options) {#getThumbnail-com.aspose.slides.ITiffOptions-}
```
public final Bitmap getThumbnail(ITiffOptions options)
```


Returns a Thumbnail tiff android.graphics.Bitmap object with specified parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff options. |

**Returns:**
android.graphics.Bitmap - android.graphics.Bitmap object.
### getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting) {#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-}
```
public final Bitmap getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting)
```


Returns a Thumbnail android.graphics.Bitmap object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |

**Returns:**
android.graphics.Bitmap - android.graphics.Bitmap objects.
### getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY) {#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-float-float-}
```
public final Bitmap getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY)
```


Returns a Thumbnail android.graphics.Bitmap object with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
android.graphics.Bitmap - android.graphics.Bitmap objects.
### getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, Size imageSize) {#getThumbnail-com.aspose.slides.INotesCommentsLayoutingOptions-com.aspose.slides.android.Size-}
```
public final Bitmap getThumbnail(INotesCommentsLayoutingOptions notesCommentsLayouting, Size imageSize)
```


Returns a Thumbnail android.graphics.Bitmap object with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
android.graphics.Bitmap - android.graphics.Bitmap objects.
### getThumbnail(IRenderingOptions options) {#getThumbnail-com.aspose.slides.IRenderingOptions-}
```
public final Bitmap getThumbnail(IRenderingOptions options)
```


Returns a Thumbnail android.graphics.Bitmap object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**Returns:**
android.graphics.Bitmap - android.graphics.Bitmap objects.
### getThumbnail(IRenderingOptions options, float scaleX, float scaleY) {#getThumbnail-com.aspose.slides.IRenderingOptions-float-float-}
```
public final Bitmap getThumbnail(IRenderingOptions options, float scaleX, float scaleY)
```


Returns a Thumbnail android.graphics.Bitmap object with custom scaling.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images using Java.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Creates the rendering options
>      IRenderingOptions options = new RenderingOptions();
>      // Sets the position of the notes on the page
>      options.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomTruncated);
>      // Sets the position of the comments on the page
>      options.getNotesCommentsLayouting().setCommentsPosition(CommentsPositions.Right);
>      // Sets the width of the comment output area
>      options.getNotesCommentsLayouting().setCommentsAreaWidth(500);
>      // Sets the color for the comments area
>      options.getNotesCommentsLayouting().setCommentsAreaColor(Color.WHITE);
>      // Converts the first slide of the presentation to a Bitmap object
>      android.graphics.Bitmap bmp = pres.getSlides().get_Item(0).getThumbnail(options, 2f, 2f);
>      // Saves the image in the PNG format
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("Slide_Notes_Comments_0.png");
>          bmp.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
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
### renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Canvas graphics, int width, int height) {#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-android.graphics.Canvas-int-int-}
```
public final void renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Canvas graphics, int width, int height)
```


Renders certain slide to a Graphics object using specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | android.graphics.Canvas | The object where to render to. |
| width | int | The maximum width (in pixels) that can be occupied by the rendered slide. |
| height | int | The maximum height (in pixels) that can be occupied by the rendered slide. |

### renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Canvas graphics, float scale) {#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-android.graphics.Canvas-float-}
```
public final void renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Canvas graphics, float scale)
```


Renders certain slide to a Graphics object using specified scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | android.graphics.Canvas | The object where to render to. |
| scale | float | The scale for rendering the slide (1.0 is 100%). |

### renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Canvas graphics) {#renderToGraphics-com.aspose.slides.INotesCommentsLayoutingOptions-android.graphics.Canvas-}
```
public final void renderToGraphics(INotesCommentsLayoutingOptions notesCommentsLayouting, Canvas graphics)
```


Renders certain slide to a Graphics object.

--------------------

> ```
> The following example shows how to convert the first slide of a PowerPoint presentation to a bitmap object using the RenderToGraphics method.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Gets the presentation slide size
>      SizeF slideSize = pres.getSlideSize().getSize();
>      // Creates a Bitmap with the slide size
>      android.graphics.Bitmap image = android.graphics.Bitmap.createBitmap((int)slideSize.getWidth(), (int)slideSize.getHeight(), Bitmap.Config.ARGB_8888);
>      Canvas graphics = new Canvas(image);
>      pres.getSlides().get_Item(0).renderToGraphics(new RenderingOptions(), graphics);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("Slide_0.png");
>          image.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | android.graphics.Canvas | The object where to render to. |

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
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
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
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
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


Saves content of slide as SVG file.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  // Presentation object can load PowerPoint formats like PPT, PPTX, ODP etc.
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++)
>      {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream fileStream = new FileOutputStream("slide-" + index + ".svg");
>          try {
>              slide.writeAsSvg(fileStream);
>          } finally {
>              if (fileStream != null) fileStream.close();
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
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Saves content of slide as SVG file.

--------------------

> ```
> The following example code shows how to generate SVG image with Custom Shape IDS from PowerPoint Presentation.
>  
>  // Instantiate a Presentation class that represents the presentation file
>  Presentation pres = new Presentation("CreateSlidesSVGImage.pptx");
>  try {
>      // Access the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Create a memory stream object
>      ByteArrayOutputStream svgStream = new ByteArrayOutputStream();
>      // Generate SVG image of slide and save in memory stream
>      sld.writeAsSvg(svgStream);
>      // Save memory stream to file
>      FileOutputStream fileStream = new FileOutputStream("Aspose_out.svg");
>      try {
>          svgStream.writeTo(fileStream);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>      svgStream.close();
>  } catch(IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

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

