---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: 控制演示文稿保存方式的选项。
type: docs
url: /zh/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

控制演示文稿保存方式的选项。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。 |
| [getProgressCallback()](#getProgressCallback--) | 表示用于保存进度更新（以百分比表示）的回调对象。 |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | 表示用于保存进度更新（以百分比表示）的回调对象。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 返回或设置在未找到源字体时使用的字体。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 返回或设置在未找到源字体时使用的字体。 |
| [getGradientStyle()](#getGradientStyle--) | 返回或设置渐变的视觉样式。 |
| [setGradientStyle(int value)](#setGradientStyle-int-) | 返回或设置渐变的视觉样式。 |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。 |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。 |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

返回或设置一个接收警告并决定加载过程是继续还是中止的对象。读/写 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**返回：**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

返回或设置一个接收警告并决定加载过程是继续还是中止的对象。读/写 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

表示用于保存进度更新（以百分比表示）的回调对象。参见 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**返回：**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)

### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

表示用于保存进度更新（以百分比表示）的回调对象。参见 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

返回或设置在未找到源字体时使用的字体。读写 String。

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Returns or sets font used in case source font is not found. Read-write String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```

Returns or sets the visual style of the gradient. Read/write [GradientStyle](../../com.aspose.slides/gradientstyle).

**Returns:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

Returns or sets the visual style of the gradient. Read/write [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Read/write boolean. The default value is false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

When this property is set to true, hyperlinks with JavaScript calls will be ignored while saving.

When this property is set to false, all hyperlinks will be saved.

**Returns:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)

指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读/写 boolean。默认值为 false。

--------------------

> ```
> 示例：
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

当此属性设为 true 时，保存时会忽略带有 JavaScript 调用的超链接。

当此属性设为 false 时，所有超链接都会被保存。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |