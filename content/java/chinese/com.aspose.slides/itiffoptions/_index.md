---
title: ITiffOptions
second_title: Aspose.Slides for Java API 参考
description: 提供控制演示文稿以 TIFF 格式保存的选项。
type: docs
url: /zh/com.aspose.slides/itiffoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

提供控制演示文稿以 TIFF 格式保存方式的选项。
## 方法

| Method | Description |
| --- | --- |
| [getImageSize()](#getImageSize--) | 指定生成的 TIFF 图像的大小。 |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | 指定生成的 TIFF 图像的大小。 |
| [getDpiX()](#getDpiX--) | 指定水平分辨率（每英寸点数）。 |
| [setDpiX(long value)](#setDpiX-long-) | 指定水平分辨率（每英寸点数）。 |
| [getDpiY()](#getDpiY--) | 指定垂直分辨率（每英寸点数）。 |
| [setDpiY(long value)](#setDpiY-long-) | 指定垂直分辨率（每英寸点数）。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包括隐藏幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包括隐藏幻灯片。 |
| [getCompressionType()](#getCompressionType--) | 指定压缩类型。 |
| [setCompressionType(int value)](#setCompressionType-int-) | 指定压缩类型。 |
| [getPixelFormat()](#getPixelFormat--) | 指定生成图像的像素格式。 |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 指定生成图像的像素格式。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getBwConversionMode()](#getBwConversionMode--) | 指定将彩色图像转换为黑白图像的算法。 |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | 指定将彩色图像转换为黑白图像的算法。 |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中 Ink 对象外观的选项。 |
### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```


指定生成的 TIFF 图像的大小。默认值为 0x0，表示生成的图像大小将根据演示文稿幻灯片尺寸计算。读/写 java.awt.Dimension。

**Returns:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```


指定生成的 TIFF 图像的大小。默认值为 0x0，表示生成的图像大小将根据演示文稿幻灯片尺寸计算。读/写 java.awt.Dimension。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```


指定水平分辨率（每英寸点数）。读/写 long。

**Returns:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```


指定水平分辨率（每英寸点数）。读/写 long。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```


指定垂直分辨率（每英寸点数）。读/写 long。

**Returns:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```


指定垂直分辨率（每英寸点数）。读/写 long。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


指定生成的文档是否应包括隐藏幻灯片。默认值为 false。

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


指定生成的文档是否应包括隐藏幻灯片。默认值为 false。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```


指定压缩类型。读/写 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```


指定压缩类型。读/写 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```


指定生成图像的像素格式。读/写 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```


指定生成图像的像素格式。读/写 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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


获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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


指定将彩色图像转换为黑白图像的算法。仅当 CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) 设置为 [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) 或 [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) 时此选项才会生效。读/写 [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)。默认值为 [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)。

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


指定将彩色图像转换为黑白图像的算法。仅当 CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) 设置为 [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) 或 [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) 时此选项才会生效。读/写 [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)。默认值为 [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)。

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


提供控制导出文档中 Ink 对象外观的选项。只读 [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returns:**
[IInkOptions](../../com.aspose.slides/iinkoptions)