---
title: Html5Options
second_title: Aspose.Slides for Java API 参考
description: 表示 HTML5 导出选项。
type: docs
url: /zh/com.aspose.slides/html5options/
---
**继承:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有实现的接口:**  
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)  
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

表示 HTML5 导出选项。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Html5Options()](#Html5Options--) | 默认构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | 返回或设置过渡动画选项。 |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | 返回或设置过渡动画选项。 |
| [getAnimateShapes()](#getAnimateShapes--) | 返回或设置形状动画选项。 |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | 返回或设置形状动画选项。 |
| [getEmbedImages()](#getEmbedImages--) | 返回或设置图像嵌入选项。 |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | 返回或设置图像嵌入选项。 |
| [getOutputPath()](#getOutputPath--) | 确定外部资源的存储位置。 |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | 确定外部资源的存储位置。 |
| [getPicturesCompression()](#getPicturesCompression--) | 表示图片压缩级别 |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | 表示图片压缩级别 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 获取或设置一个值，指示文本在渲染时是否不使用连字。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 获取或设置一个值，指示文本在渲染时是否不使用连字。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |

### Html5Options() {#Html5Options--}
> ```
public Html5Options()
```

默认构造函数。

### getAnimateTransitions() {#getAnimateTransitions--}
> ```
public final boolean getAnimateTransitions()
```

返回或设置过渡动画选项。可读写 boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**  
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
> ```
public final void setAnimateTransitions(boolean value)
```

返回或设置过渡动画选项。可读写 boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
> ```
public final boolean getAnimateShapes()
```

返回或设置形状动画选项。可读写 boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**  
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
> ```
public final void setAnimateShapes(boolean value)
```

返回或设置形状动画选项。可读写 boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
> ```
public final boolean getEmbedImages()
```

返回或设置图像嵌入选项。可读写 boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**  
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
> ```
public final void setEmbedImages(boolean value)
```

返回或设置图像嵌入选项。可读写 boolean。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
> ```
public final String getOutputPath()
```

确定外部资源的存储位置。可读写 String。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**  
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
> ```
public final void setOutputPath(String value)
```

确定外部资源的存储位置。可读写 String。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
> ```
public final int getPicturesCompression()
```

表示图片压缩级别

**返回:**  
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
> ```
public final void setPicturesCompression(int value)
```

表示图片压缩级别

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
> ```
public final boolean getDisableFontLigatures()
```

获取或设置一个值，指示文本在渲染时是否不使用连字。当设置为 true 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 false。

--------------------

> ``` 
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // 在文本渲染中禁用连字
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**  
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
> ```
public final void setDisableFontLigatures(boolean value)
```

获取或设置一个值，指示文本在渲染时是否不使用连字。当设置为 true 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 false。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // 在文本渲染中禁用连字
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
> ```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
> ```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

获取或设置在导出演示文稿时幻灯片在页面上的放置模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |