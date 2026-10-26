---
title: TiffOptions
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/tiffoptions/
---
## TiffOptions 类

 提供控制演示文稿以 TIFF 格式保存方式的选项。

### TiffOptions {#TiffOptions}

| 名称 | 描述 |
| --- | --- |
| TiffOptions() | 默认函数。 |

**返回：**
TiffOptions


---


### getBwConversionMode {#getBwConversionMode}

| 名称 | 描述 |
| --- | --- |
| getBwConversionMode () | 指定将彩色图像转换为黑白图像的算法。仅在 CompressionType(#getCompressionType/ #setCompressionType(int)) 设置为 TiffCompressionTypes#CCITT4 或 TiffCompressionTypes#CCITT3 时才会应用此选项。Read/write BlackWhiteConversionMode。默认是 BlackWhiteConversionMode#Default。 |

**返回：**
int


---


### getCompressionType {#getCompressionType}

| 名称 | 描述 |
| --- | --- |
| getCompressionType () | 指定压缩类型。Read/write TiffCompressionTypes。 |

**返回：**
int


---


### getDpiX {#getDpiX}

| 名称 | 描述 |
| --- | --- |
| getDpiX () | 指定水平分辨率（每英寸点数）。Read/write long。 |

**返回：**
long


---


### getDpiY {#getDpiY}

| 名称 | 描述 |
| --- | --- |
| getDpiY () | 指定垂直分辨率（每英寸点数）。Read/write long。 |

**返回：**
long


---


### getImageSize {#getImageSize}

| 名称 | 描述 |
| --- | --- |
| getImageSize () | 指定生成的 TIFF 图像的尺寸。默认值为 0x0，表示生成的图像尺寸将根据演示文稿幻灯片大小计算。Read/write java.awt.Dimension。 |

**返回：**
Dimension


---


### getInkOptions {#getInkOptions}

| 名称 | 描述 |
| --- | --- |
| getInkOptions () | 提供控制导出文档中 Ink 对象外观的选项。Read-only IInkOptions |

**返回：**
[InkOptions](../inkoptions)


---


### getPixelFormat {#getPixelFormat}

| 名称 | 描述 |
| --- | --- |
| getPixelFormat () | 指定生成图像的像素格式。Read/write ImagePixelFormat。 |

**返回：**
int


---


### getShowHiddenSlides {#getShowHiddenSlides}

| 名称 | 描述 |
| --- | --- |
| getShowHiddenSlides () | 指定生成的文档是否应包含隐藏幻灯片。默认值为 false。 |

**返回：**
boolean


---


### getSlidesLayoutOptions {#getSlidesLayoutOptions}

| 名称 | 描述 |
| --- | --- |
| getSlidesLayoutOptions () | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 ISlidesLayoutOptions。 |

**返回：**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), [HandoutLayoutingOptions](../handoutlayoutingoptions)


---


### setBwConversionMode {#setBwConversionMode}

| 名称 | 描述 |
| --- | --- |
| setBwConversionMode (int) | 指定将彩色图像转换为黑白图像的算法。仅在 CompressionType(#getCompressionType/ #setCompressionType(int)) 设置为 TiffCompressionTypes#CCITT4 或 TiffCompressionTypes#CCITT3 时才会应用此选项。Read/write BlackWhiteConversionMode。默认是 BlackWhiteConversionMode#Default。 |

**返回：**
void


---


### setCompressionType {#setCompressionType}

| 名称 | 描述 |
| --- | --- |
| setCompressionType (int) | 指定压缩类型。Read/write TiffCompressionTypes。 |

**返回：**
void


---


### setDpiX {#setDpiX}

| 名称 | 描述 |
| --- | --- |
| setDpiX (long) | 指定水平分辨率（每英寸点数）。Read/write long。 |

**返回：**
void


---


### setDpiY {#setDpiY}

| 名称 | 描述 |
| --- | --- |
| setDpiY (long) | 指定垂直分辨率（每英寸点数）。Read/write long。 |

**返回：**
void


---


### setImageSize {#setImageSize}

| 名称 | 描述 |
| --- | --- |
| setImageSize (Dimension) | 指定生成的 TIFF 图像的尺寸。默认值为 0x0，表示生成的图像尺寸将根据演示文稿幻灯片大小计算。Read/write java.awt.Dimension。 |

**返回：**
void


---


### setPixelFormat {#setPixelFormat}

| 名称 | 描述 |
| --- | --- |
| setPixelFormat (int) | 指定生成图像的像素格式。Read/write ImagePixelFormat。 |

**返回：**
void


---


### setShowHiddenSlides {#setShowHiddenSlides}

| 名称 | 描述 |
| --- | --- |
| setShowHiddenSlides (boolean) | 指定生成的文档是否应包含隐藏幻灯片。默认值为 false。 |

**返回：**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| 名称 | 描述 |
| --- | --- |
| setSlidesLayoutOptions ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 ISlidesLayoutOptions。 |

**返回：**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| 名称 | 描述 |
| --- | --- |
| setSlidesLayoutOptions ([HandoutLayoutingOptions](../handoutlayoutingoptions)) | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 ISlidesLayoutOptions。 |

**返回：**
void


---