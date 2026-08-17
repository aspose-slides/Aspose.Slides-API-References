---
title: IHtmlOptions
second_title: Aspose.Slides for Java API 参考
description: 表示 HTML 导出选项。
type: docs
url: /zh/com.aspose.slides/ihtmloptions/
---
**所有已实现的接口：**
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
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包含隐藏的幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包含隐藏的幻灯片。 |
| [getJpegQuality()](#getJpegQuality--) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。 |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。 |
| [getPicturesCompression()](#getPicturesCompression--) | 表示图片压缩级别 读/写 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 表示图片压缩级别 读/写 [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | 布尔标志指示裁剪的部分是否仍是文档的一部分。 |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | 布尔标志指示裁剪的部分是否仍是文档的一部分。 |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True 表示从 SVG 容器中排除宽度和高度属性——这将使布局响应式。 |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True 表示从 SVG 容器中排除宽度和高度属性——这将使布局响应式。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 获取或设置一个值，指示文本是否在不使用连字的情况下渲染。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 获取或设置一个值，指示文本是否在不使用连字的情况下渲染。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中 Ink 对象外观的选项。 |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

返回或设置 HTML 模板。读/写 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**返回：**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

返回或设置 HTML 模板。读/写 [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

返回或设置幻灯片图像格式选项。读/写 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**返回：**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

返回或设置幻灯片图像格式选项。读/写 [ISlideImageFormat](../../com.aspose.slides/islideimageformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定生成的文档是否应包含隐藏的幻灯片。默认值为 false。

**返回：**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定生成的文档是否应包含隐藏的幻灯片。默认值为 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

返回或设置决定 PDF 文档中 JPEG 图像质量的值。读/写 byte。

--------------------

仅在文档包含 JPEG 图像时有效。

使用此属性在以 PDF 格式保存文档时获取或设置图像质量。值范围为 0 到 100，0 表示质量最差但压缩最高，100 表示质量最佳但压缩最低。

默认值为 **95**。

**返回：**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

返回或设置决定 PDF 文档中 JPEG 图像质量的值。读/写 byte。

--------------------

仅在文档包含 JPEG 图像时有效。

使用此属性在以 PDF 格式保存文档时获取或设置图像质量。值范围为 0 到 100，0 表示质量最差但压缩最高，100 表示质量最佳但压缩最低。

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

布尔标志指示裁剪的部分是否仍是文档的一部分。如果为 true，则裁剪的部分将被删除；如果为 false，则它们将序列化到文档中（可能导致文件更大）。读/写 boolean。

**返回：**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

布尔标志指示裁剪的部分是否仍是文档的一部分。如果为 true，则裁剪的部分将被删除；如果为 false，则它们将序列化到文档中（可能导致文件更大）。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

True 表示从 SVG 容器中排除宽度和高度属性——这将使布局响应式。False 表示相反。读/写 boolean。

**返回：**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

True 表示从 SVG 容器中排除宽度和高度属性——这将使布局响应式。False 表示相反。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

获取或设置一个值，指示文本是否在不使用连字的情况下渲染。当设置为 true 时，渲染输出中将禁用连字。默认情况下，此属性为 false。

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


**返回：**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

获取或设置一个值，指示文本是否在不使用连字的情况下渲染。当设置为 true 时，渲染输出中将禁用连字。默认情况下，此属性为 false。

--------------------

> ```
> 示例：
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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> 示例：
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


**返回：**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> 示例：
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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

提供控制导出文档中 Ink 对象外观的选项。只读 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回：**
[IInkOptions](../../com.aspose.slides/iinkoptions)