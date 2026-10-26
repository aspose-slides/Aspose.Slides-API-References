---
title: TiffOptions
second_title: Aspose.Slides for Java API 参考
description: 提供控制演示文稿以 TIFF 格式保存方式的选项。
type: docs
url: /zh/com.aspose.slides/tiffoptions/
---
**继承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有已实现的接口：**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

提供控制演示文稿以 TIFF 格式保存方式的选项。

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // 实例化一个表示演示文稿文件的 Presentation 对象
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // 将演示文稿保存为 TIFF 文档
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // 实例化一个表示演示文稿文件的 Presentation 对象
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // 实例化 TiffOptions 类
>      TiffOptions opts = new TiffOptions();
>      // 设置压缩类型
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // 压缩类型
>      // Default - 指定默认的压缩方案（LZW）。
>      // None - 指定不进行压缩。
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // 深度取决于压缩类型，不能手动设置。
>      // 分辨率单位始终等于 2（每英寸点数）
>      // 设置图像 DPI
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // 设置图像大小
>      opts.setImageSize(new Dimension(1728, 1078));
>      // 将演示文稿保存为指定图像大小的 TIFF
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // 实例化一个表示演示文稿文件的 Presentation 对象
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat 包含以下值（如文档所示）：
>      //Format1bppIndexed; // 每像素1位，已索引。
>      //Format4bppIndexed; // 每像素4位，已索引。
>      //Format8bppIndexed; // 每像素8位，已索引。
>      //Format24bppRgb; // 每像素24位，RGB。
>      //Format32bppArgb; // 每像素32位，ARGB。
> 
>      // 将演示文稿保存为指定图像像素格式的 TIFF
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | 默认构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中 Ink 对象外观的选项。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [getImageSize()](#getImageSize--) | 指定生成的 TIFF 图像的大小。 |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | 指定生成的 TIFF 图像的大小。 |
| [getDpiX()](#getDpiX--) | 指定水平分辨率（每英寸点数）。 |
| [setDpiX(long value)](#setDpiX-long-) | 指定水平分辨率（每英寸点数）。 |
| [getDpiY()](#getDpiY--) | 指定垂直分辨率（每英寸点数）。 |
| [setDpiY(long value)](#setDpiY-long-) | 指定垂直分辨率（每英寸点数）。 |
| [getCompressionType()](#getCompressionType--) | 指定压缩类型。 |
| [setCompressionType(int value)](#setCompressionType-int-) | 指定压缩类型。 |
| [getPixelFormat()](#getPixelFormat--) | 指定生成图像的像素格式。 |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 指定生成图像的像素格式。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getBwConversionMode()](#getBwConversionMode--) | 指定将彩色图像转换为黑白图像的算法。 |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | 指定将彩色图像转换为黑白图像的算法。 |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

默认构造函数。

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

提供控制导出文档中 Ink 对象外观的选项。只读 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回：**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**返回：**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```

指定生成的 TIFF 图像的大小。默认值为 0x0，表示将根据演示文稿幻灯片大小计算生成图像的尺寸。读/写 java.awt.Dimension。

**返回：**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```

指定生成的 TIFF 图像的大小。默认值为 0x0，表示将根据演示文稿幻灯片大小计算生成图像的尺寸。读/写 java.awt.Dimension。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

指定水平分辨率（每英寸点数）。读/写 long。

**返回：**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

指定水平分辨率（每英寸点数）。读/写 long。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

指定垂直分辨率（每英寸点数）。读/写 long。

**返回：**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

指定垂直分辨率（每英寸点数）。读/写 long。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

指定压缩类型。读/写 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**返回：**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

指定压缩类型。读/写 [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

指定生成图像的像素格式。读/写 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**返回：**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

指定生成图像的像素格式。读/写 [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
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

**返回：**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
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

**返回：**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |