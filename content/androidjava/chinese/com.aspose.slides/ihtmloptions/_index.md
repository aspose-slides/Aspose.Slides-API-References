---
title: IHtmlOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 HTML 导出选项。
type: docs
url: /zh/com.aspose.slides/ihtmloptions/
---
**所有已实现的接口:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

表示 HTML 导出选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | 返回或设置 HTML 模板。 |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | 返回或设置 HTML 模板。 |
| [getSlideImageFormat()](#getSlideImageFormat--) | 返回或设置幻灯片图像格式选项。 |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | 返回或设置幻灯片图像格式选项。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [getJpegQuality()](#getJpegQuality--) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。 |
| [getPicturesCompression()](#getPicturesCompression--) | 表示图片压缩级别 读/写 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))。 |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 表示图片压缩级别 读/写 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))。 |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 布尔标志，指示裁剪的部分是否保留在文档中。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 布尔标志，指示裁剪的部分是否保留在文档中。 |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | 设置为 True 可从 SVG 容器中排除宽度和高度属性——这将使布局响应式。 |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | 设置为 True 可从 SVG 容器中排除宽度和高度属性——这将使布局响应式。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 获取或设置指示文本是否在不使用连字的情况下渲染的值。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 获取或设置指示文本是否在不使用连字的情况下渲染的值。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置导出演示文稿时幻灯片在页面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置导出演示文稿时幻灯片在页面上的排列模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中墨水对象外观的选项。 |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

返回或设置 HTML 模板。 读/写 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**返回：**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

返回或设置 HTML 模板。 读/写 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

返回或设置幻灯片图像格式选项。 读/写 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**返回：**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

返回或设置幻灯片图像格式选项。 读/写 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

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

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

返回或设置决定 PDF 文档中 JPEG 图像质量的值。 读/写 byte。

--------------------

仅在文档包含 JPEG 图像时生效。

使用此属性在以 PDF 格式保存时获取或设置文档中图像的质量。值范围为 0 到 100，其中 0 表示最差质量但最高压缩，100 表示最佳质量但最低压缩。

默认值为 **95**。

**返回：**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

返回或设置决定 PDF 文档中 JPEG 图像质量的值。 读/写 byte。

--------------------

仅在文档包含 JPEG 图像时生效。

使用此属性在以 PDF 格式保存时获取或设置文档中图像的质量。值范围为 0 到 100，其中 0 表示最差质量但最高压缩，100 表示最佳质量但最低压缩。

默认值为 **95**。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

表示图片压缩级别 读/写 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))。

**返回：**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

表示图片压缩级别 读/写 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int))。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

布尔标志，指示裁剪的部分是否保留在文档中。若为 true，则裁剪部分将被移除；若为 false，则它们会序列化到文档中（可能导致文件更大）。 读/写 boolean。

**返回：**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

布尔标志，指示裁剪的部分是否保留在文档中。若为 true，则裁剪部分将被移除；若为 false，则它们会序列化到文档中（可能导致文件更大）。 读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

设置为 True 可从 SVG 容器中排除宽度和高度属性——这将使布局响应式。否则为 False。 读/写 boolean。

**返回：**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

设置为 True 可从 SVG 容器中排除宽度和高度属性——这将使布局响应式。否则为 False。 读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

获取或设置指示文本是否在不使用连字的情况下渲染的值。设置为 true 时，渲染输出将禁用连字。默认情况下，此属性为 false。

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

**Returns:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```


Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()

提供控制导出文档中墨水对象外观的选项。 只读 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回：**
[IInkOptions](../../com.aspose.slides/iinkoptions)