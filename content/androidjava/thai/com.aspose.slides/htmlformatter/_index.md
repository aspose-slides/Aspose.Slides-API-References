---
title: HtmlFormatter
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นเทมเพลตไฟล์ HTML.
type: docs
url: /th/com.aspose.slides/htmlformatter/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

เป็นเทมเพลตไฟล์ HTML.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple document view which consists of sequences of slides one below another. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple slide show html which shows slides one after another. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Creates and returns HTML formatter for custom callback-driven html generation. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


Creates and returns HTML formatter for a simple document view which consists of sequences of slides one below another.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| css | java.lang.String | ระบุ CSS สำหรับไฟล์นี้. |
| showSlideTitle | boolean | เพิ่มชื่อสไลด์หากมีอยู่เหนือภาพสไลด์. |

**ค่าที่ส่งกลับ:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


Creates and returns HTML formatter for a simple slide show html which shows slides one after another.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| css | java.lang.String | ระบุ URL ของไฟล์ CCS ที่ใช้. |
| showSlideTitle | boolean | เพิ่มชื่อสไลด์หากมีอยู่เหนือภาพสไลด์. |

**ค่าที่ส่งกลับ:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


Creates and returns HTML formatter for custom callback-driven html generation.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | อินเทอร์เฟซ callback ที่ควบคุมการสร้างไฟล์ html. |

**ค่าที่ส่งกลับ:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.