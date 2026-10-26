---
title: ITiffOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 提供用于控制演示文稿以 TIFF 格式保存的选项。
type: docs
url: /zh/com.aspose.slides/itiffoptions/
---
**所有已实现的接口：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

提供用于控制演示文稿以 TIFF 格式保存的选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getImageSize()](#getImageSize--) | 指定生成的 TIFF 图像的大小。 |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | 指定生成的 TIFF 图像的大小。 |
| [getDpiX()](#getDpiX--) | 指定水平分辨率（每英寸点数）。 |
| [setDpiX(long value)](#setDpiX-long-) | 指定水平分辨率（每英寸点数）。 |
| [getDpiY()](#getDpiY--) | 指定垂直分辨率（每英寸点数）。 |
| [setDpiY(long value)](#setDpiY-long-) | 指定垂直分辨率（每英寸点数）。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [getCompressionType()](#getCompressionType--) | 指定压缩类型。 |
| [setCompressionType(int value)](#setCompressionType-int-) | 指定压缩类型。 |
| [getPixelFormat()](#getPixelFormat--) | 指定生成图像的像素格式。 |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 指定生成图像的像素格式。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置在导出演示文稿时幻灯片在页面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置在导出演示文稿时幻灯片在页面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getBwConversionMode()](#getBwConversionMode--) | 指定将彩色图像转换为黑白图像的算法。 |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | 指定将彩色图像转换为黑白图像的算法。 |
| [getInkOptions()](#getInkOptions--) | 提供用于控制导出文档中 Ink 对象外观的选项。 |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

指定生成的 TIFF 图像的大小。默认值为 0x0，表示生成的图像大小将根据演示文稿幻灯片的尺寸值计算。可读写 [Size](../../com.aspose.slides.android/size)。

**返回：**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

指定生成的 TIFF 图像的大小。默认值为 0x0，表示生成的图像大小将根据演示文稿幻灯片的尺寸值计算。可读写 [Size](../../com.aspose.slides.android/size)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

指定水平分辨率（每英寸点数）。可读写 long。

**返回：**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

指定水平分辨率（每英寸点数）。可读写 long。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

指定垂直分辨率（每英寸点数）。可读写 long。

**返回：**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

指定垂直分辨率（每英寸点数）。可读写 long。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**返回：**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

指定压缩类型。可读写 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**返回：**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

指定压缩类型。可读写 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

指定生成图像的像素格式。可读写 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**返回：**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

指定生成图像的像素格式。可读写 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

获取或设置在导出演示文稿时幻灯片在页面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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

Specifies the algorithm for converting a color image into a black and white image. This option will applied only if  CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) is set to [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes#CCITT4) or [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes#CCITT3) Read/write [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Default is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode#Default).

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

Specifies the algorithm for converting a color image into a black and white image. This option will applied only if  CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) is set to [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes#CCITT4) or [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes#CCITT3) Read/write [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Default is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode#Default).

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

提供用于控制导出文档中 Ink 对象外观的选项。只读 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回：**
[IInkOptions](../../com.aspose.slides/iinkoptions)