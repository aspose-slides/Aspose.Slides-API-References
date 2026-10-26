---
title: HtmlOptions
second_title: Aspose.Slides Java API 参考
description: 表示 HTML 导出选项。
type: docs
url: /zh/com.aspose.slides/htmloptions/
---
**继承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有实现的接口:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

表示 HTML 导出选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | 创建一个新的 HtmlOptions 对象，指定回调。 |
| [HtmlOptions()](#HtmlOptions--) | 创建一个新的 HtmlOptions 对象，用于保存为单个 HTML 文件。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中 Ink 对象外观的选项。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [getHtmlFormatter()](#getHtmlFormatter--) | 获取或设置 HTML 模板。 |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | 获取或设置 HTML 模板。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 获取或设置一个值，指示文本是否在渲染时不使用连字。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 获取或设置一个值，指示文本是否在渲染时不使用连字。 |
| [getSlideImageFormat()](#getSlideImageFormat--) | 获取或设置幻灯片图像格式选项。 |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | 获取或设置幻灯片图像格式选项。 |
| [getJpegQuality()](#getJpegQuality--) | 获取或设置决定 PDF 文档内 JPEG 图像质量的值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 获取或设置决定 PDF 文档内 JPEG 图像质量的值。 |
| [getPicturesCompression()](#getPicturesCompression--) | 表示图片压缩级别 |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 表示图片压缩级别 |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 布尔标志指示裁剪部分是否保留在文档中。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 布尔标志指示裁剪部分是否保留在文档中。 |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | 设置为 true 可从 svg 容器中排除 width 和 height 属性——这将使布局具有响应性。 |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | 设置为 true 可从 svg 容器中排除 width 和 height 属性——这将使布局具有响应性。 |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

创建一个新的 HtmlOptions 对象，指定回调。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | 控制保存项目的回调对象。 |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

创建一个新的 HtmlOptions 对象，用于保存为单个 HTML 文件。

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
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**
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
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

提供控制导出文档中 Ink 对象外观的选项。只读 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**返回:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

获取或设置 HTML 模板。读/写 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**返回:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

获取或设置 HTML 模板。读/写 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

获取或设置一个值，指示文本是否在渲染时不使用连字。 当设置为 true 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 false。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

获取或设置一个值，指示文本是否在渲染时不使用连字。 当设置为 true 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 false。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

获取或设置幻灯片图像格式选项。读/写 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**返回:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

获取或设置幻灯片图像格式选项。读/写 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

获取或设置决定 PDF 文档内 JPEG 图像质量的值。读/写 byte。

--------------------

仅在文档包含 JPEG 图像时生效。

使用此属性获取或设置在 PDF 格式保存时文档内图像的质量。该值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

默认值为 **95**。

**返回:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

获取或设置决定 PDF 文档内 JPEG 图像质量的值。读/写 byte。

--------------------

仅在文档包含 JPEG 图像时生效。

使用此属性获取或设置在 PDF 格式保存时文档内图像的质量。该值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。

默认值为 **95**。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

表示图片压缩级别

**返回:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

表示图片压缩级别

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

布尔标志指示裁剪部分是否保留在文档中。如果为 true，则裁剪部分将被移除；如果为 false，则它们将序列化到文档中（这可能导致文件更大）。

**返回:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

布尔标志指示裁剪部分是否保留在文档中。如果为 true，则裁剪部分将被移除；如果为 false，则它们将序列化到文档中（这可能导致文件更大）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

设置为 true 可从 svg 容器中排除 width 和 height 属性——这将使布局具有响应性。设置为 false 则相反。读/写 boolean。

**返回:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

设置为 true 可从 svg 容器中排除 width 和 height 属性——这将使布局具有响应性。设置为 false 则相反。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |