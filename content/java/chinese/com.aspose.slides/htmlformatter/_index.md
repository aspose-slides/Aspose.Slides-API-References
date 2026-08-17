---
title: HtmlFormatter
second_title: Aspose.Slides for Java API 参考
description: 表示 HTML 文件模板。
type: docs
url: /zh/com.aspose.slides/htmlformatter/
---
**继承：**
java.lang.Object

**所有已实现的接口：**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

表示 HTML 文件模板。
## 方法

| 方法 | 描述 |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | 创建并返回用于简单文档视图的 HTML 格式化器，该视图由一个接一个的幻灯片序列组成。 |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | 创建并返回用于简单幻灯片放映的 HTML 格式化器，该放映依次显示幻灯片。 |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | 创建并返回用于自定义回调驱动的 HTML 生成的格式化器。 |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


创建并返回用于简单文档视图的 HTML 格式化器，该视图由一个接一个的幻灯片序列组成。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| css | java.lang.String | 指定此文件的 CSS。 |
| showSlideTitle | boolean | 如果幻灯片图像上方有标题，则添加幻灯片标题。 |

**返回值：**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - 该 [HtmlFormatter](../../com.aspose.slides/htmlformatter) 对象。
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


创建并返回用于简单幻灯片放映的 HTML 格式化器，该放映依次显示幻灯片。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| css | java.lang.String | 指定使用的 CCS 文件的 URL。 |
| showSlideTitle | boolean | 如果幻灯片图像上方有标题，则添加幻灯片标题。 |

**返回值：**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - 该 [HtmlFormatter](../../com.aspose.slides/htmlformatter) 对象。
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


创建并返回用于自定义回调驱动的 HTML 生成的格式化器。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | 控制 HTML 文件生成的回调接口。 |

**返回值：**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - 该 [HtmlFormatter](../../com.aspose.slides/htmlformatter) 对象。