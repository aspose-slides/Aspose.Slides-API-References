---
title: SaveOptions
second_title: Aspose.Slides for Java API 参考
description: 抽象类，提供控制演示文稿保存方式的选项。
type: docs
url: /zh/com.aspose.slides/saveoptions/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

抽象类，提供控制演示文稿保存方式的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | 返回或设置一个对象，该对象接收警告并决定加载过程是继续还是中止。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 返回或设置一个对象，该对象接收警告并决定加载过程是继续还是中止。 |
| [getProgressCallback()](#getProgressCallback--) | 表示用于保存进度百分比更新的回调对象。 |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | 表示用于保存进度百分比更新的回调对象。 |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 返回或设置在未找到源字体时使用的字体。 |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 返回或设置在未找到源字体时使用的字体。 |
| [getGradientStyle()](#getGradientStyle--) | 返回或设置渐变的视觉样式。 |
| [setGradientStyle(int value)](#setGradientStyle-int-) | 返回或设置渐变的视觉样式。 |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。 |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。 |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


返回或设置一个对象，该对象接收警告并决定加载过程是继续还是中止。读/写 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**返回:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


返回或设置一个对象，该对象接收警告并决定加载过程是继续还是中止。读/写 [IWarningCallback](../../com.aspose.slides/iwarningcallback)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


表示用于保存进度百分比更新的回调对象。参见 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**返回:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


表示用于保存进度百分比更新的回调对象。参见 [IProgressCallback](../../com.aspose.slides/iprogresscallback)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
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


**返回:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


返回或设置渐变的视觉样式。读/写 [GradientStyle](../../com.aspose.slides/gradientstyle)。

**返回:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


返回或设置渐变的视觉样式。读/写 [GradientStyle](../../com.aspose.slides/gradientstyle)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
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

当此属性设置为 true 时，带有 JavaScript 调用的超链接将在保存时被忽略。

当此属性设置为 false 时，所有超链接均会被保存。

**返回:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
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

当此属性设置为 true 时，带有 JavaScript 调用的超链接将在保存时被忽略。

当此属性设置为 false 时，所有超链接均会被保存。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |