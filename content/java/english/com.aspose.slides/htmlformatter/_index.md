---
title: HtmlFormatter
second_title: Aspose.Slides for Java API Reference
description: Represents HTML file template.
type: docs
weight: 240
url: /com.aspose.slides/htmlformatter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Represents HTML file template.
## Methods

| Method | Description |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple document view which consists of sequences of slides one below another. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple slide show html which shows slides one after another. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Creates and returns HTML formatter for custom callback-driven html generation. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


Creates and returns HTML formatter for a simple document view which consists of sequences of slides one below another.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| css | java.lang.String | Specifies CSS for this file. |
| showSlideTitle | boolean | Add slide title if there is one above slide image. |

**Returns:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


Creates and returns HTML formatter for a simple slide show html which shows slides one after another.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| css | java.lang.String | Specifies URL of CCS file used. |
| showSlideTitle | boolean | Add slide title if there is one above slide image. |

**Returns:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


Creates and returns HTML formatter for custom callback-driven html generation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Callback interface which controls html file generation. |

**Returns:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
