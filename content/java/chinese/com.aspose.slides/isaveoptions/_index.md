---
title: ISaveOptions
second_title: Aspose.Slides for Java API Reference
description: Options that control how a presentation is saved.
type: docs
url: /zh/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

控制演示文稿保存方式的选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. |
| [getProgressCallback()](#getProgressCallback--) | Represents a callback object for saving progress updates in percentage. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Represents a callback object for saving progress updates in percentage. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Returns or sets font used in case source font is not found. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Returns or sets font used in case source font is not found. |
| [getGradientStyle()](#getGradientStyle--) | Returns or sets the visual style of the gradient. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Returns or sets the visual style of the gradient. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. |
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

表示一个用于保存进度更新（百分比）的回调对象。参见 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**返回：**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

表示一个用于保存进度更新（百分比）的回调对象。参见 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

返回或设置在未找到源字体时使用的字体。读/写 String。

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

**返回：**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

返回或设置在未找到源字体时使用的字体。读/写 String。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```

返回或设置渐变的视觉样式。读/写 [GradientStyle](../../com.aspose.slides/gradientstyle)。

**返回：**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

返回或设置渐变的视觉样式。读/写 [GradientStyle](../../com.aspose.slides/gradientstyle)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读/写 boolean。默认值为 false。

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

当此属性设置为 true 时，保存时将忽略带有 JavaScript 调用的超链接。

当此属性设置为 false 时，所有超链接将被保存。

**返回：**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读/写 boolean。默认值为 false。

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

当此属性设置为 true 时，保存时将忽略带有 JavaScript 调用的超链接。

当此属性设置为 false 时，所有超链接将被保存。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |