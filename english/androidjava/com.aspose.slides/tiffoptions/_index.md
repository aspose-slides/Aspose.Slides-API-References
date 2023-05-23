---
title: TiffOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Provides options that control how a presentation is saved in TIFF format.
type: docs
weight: 578
url: /androidjava/com.aspose.slides/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Provides options that control how a presentation is saved in TIFF format.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Saving the presentation to TIFF document
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Instantiate a Presentation object that represents a Presentation file
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Instantiate the TiffOptions class
>      TiffOptions opts = new TiffOptions();
>      // Setting compression type
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      INotesCommentsLayoutingOptions notesOptions = opts.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Compression Types
>      // Default - Specifies the default compression scheme (LZW).
>      // None - Specifies no compression.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Depth depends on the compression type and cannot be set manually.
>      // Resolution unit  is always equal to â\u20ac\u01532â\u20ac? (dots per inch)
>      // Setting image DPI
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Set Image Size
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // Save the presentation to TIFF with specified image size
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Instantiate a Presentation object that represents a Presentation file
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat contains the following values (as could be seen from documentation):
>      //Format1bppIndexed; // 1 bits per pixel, indexed.
>      //Format4bppIndexed; // 4 bits per pixel, indexed.
>      //Format8bppIndexed; // 8 bits per pixel, indexed.
>      //Format24bppRgb; // 24 bits per pixel, RGB.
>      //Format32bppArgb; // 32 bits per pixel, ARGB.
> 
>      // Save the presentation to TIFF with specified image size
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getNotesCommentsLayouting()](#getNotesCommentsLayouting--) | Provides options that control how notes and comments is placed in exported document. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getImageSize()](#getImageSize--) | Specifies size of a generated TIFF image. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Specifies size of a generated TIFF image. |
| [getDpiX()](#getDpiX--) | Specifies the horizontal resolution in dots per inch. |
| [setDpiX(long value)](#setDpiX-long-) | Specifies the horizontal resolution in dots per inch. |
| [getDpiY()](#getDpiY--) | Specifies the vertical resolution in dots per inch. |
| [setDpiY(long value)](#setDpiY-long-) | Specifies the vertical resolution in dots per inch. |
| [getCompressionType()](#getCompressionType--) | Specifies the compression type. |
| [setCompressionType(int value)](#setCompressionType-int-) | Specifies the compression type. |
| [getPixelFormat()](#getPixelFormat--) | Specifies the pixel format for the generated images. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Specifies the pixel format for the generated images. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


Default constructor.

### getNotesCommentsLayouting() {#getNotesCommentsLayouting--}
```
public final INotesCommentsLayoutingOptions getNotesCommentsLayouting()
```


Provides options that control how notes and comments is placed in exported document.

**Returns:**
[INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```


Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write [Size](../../com.aspose.slides.android/size).

**Returns:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```


Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write [Size](../../com.aspose.slides.android/size).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


Specifies the horizontal resolution in dots per inch. Read/write long.

**Returns:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


Specifies the horizontal resolution in dots per inch. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


Specifies the vertical resolution in dots per inch. Read/write long.

**Returns:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


Specifies the vertical resolution in dots per inch. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


Specifies the compression type. Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


Specifies the compression type. Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


Specifies the pixel format for the generated images. Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


Specifies the pixel format for the generated images. Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

