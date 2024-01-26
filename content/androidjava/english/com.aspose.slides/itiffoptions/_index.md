---
title: ITiffOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Provides options that control how a presentation is saved in TIFF format.
type: docs
url: /com.aspose.slides/itiffoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Provides options that control how a presentation is saved in TIFF format.
## Methods

| Method | Description |
| --- | --- |
| [getImageSize()](#getImageSize--) | Specifies size of a generated TIFF image. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Specifies size of a generated TIFF image. |
| [getDpiX()](#getDpiX--) | Specifies the horizontal resolution in dots per inch. |
| [setDpiX(long value)](#setDpiX-long-) | Specifies the horizontal resolution in dots per inch. |
| [getDpiY()](#getDpiY--) | Specifies the vertical resolution in dots per inch. |
| [setDpiY(long value)](#setDpiY-long-) | Specifies the vertical resolution in dots per inch. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getCompressionType()](#getCompressionType--) | Specifies the compression type. |
| [setCompressionType(int value)](#setCompressionType-int-) | Specifies the compression type. |
| [getPixelFormat()](#getPixelFormat--) | Specifies the pixel format for the generated images. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Specifies the pixel format for the generated images. |
| [getNotesCommentsLayouting()](#getNotesCommentsLayouting--) | Provides options that control how notes and comments is placed in exported document. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Specifies the algorithm for converting a color image into a black and white image. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Specifies the algorithm for converting a color image into a black and white image. |
| [getInkOptions()](#getInkOptions--) | Provides options that control the look of Ink objects in exported document. |
### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```


Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write [Size](../../com.aspose.slides.android/size).

**Returns:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```


Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write [Size](../../com.aspose.slides.android/size).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```


Specifies the horizontal resolution in dots per inch. Read/write long.

**Returns:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```


Specifies the horizontal resolution in dots per inch. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```


Specifies the vertical resolution in dots per inch. Read/write long.

**Returns:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```


Specifies the vertical resolution in dots per inch. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```


Specifies the compression type. Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```


Specifies the compression type. Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```


Specifies the pixel format for the generated images. Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```


Specifies the pixel format for the generated images. Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNotesCommentsLayouting() {#getNotesCommentsLayouting--}
```
public abstract INotesCommentsLayoutingOptions getNotesCommentsLayouting()
```


Provides options that control how notes and comments is placed in exported document.

**Returns:**
[INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions)
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```


Specifies the algorithm for converting a color image into a black and white image. This option will applied only if  CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) is set to [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) or [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Read/write [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Default is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```


Specifies the algorithm for converting a color image into a black and white image. This option will applied only if  CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) is set to [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) or [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Read/write [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Default is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


Provides options that control the look of Ink objects in exported document. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returns:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
