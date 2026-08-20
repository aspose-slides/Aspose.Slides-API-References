---
title: HtmlFormatter
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของเทมเพลตไฟล์ HTML.
type: docs
url: /th/com.aspose.slides/htmlformatter/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการ Implemented:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

เป็นตัวแทนของเทมเพลตไฟล์ HTML.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | สร้างและคืนค่า HTML formatter สำหรับมุมมองเอกสารแบบง่ายที่ประกอบด้วยลำดับของสไลด์เรียงต่อกันจากบนลงล่าง. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | สร้างและคืนค่า HTML formatter สำหรับ slide show HTML แบบง่ายที่แสดงสไลด์ต่อกันหนึ่งต่อหนึ่ง. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | สร้างและคืนค่า HTML formatter สำหรับการสร้าง HTML ที่ขับเคลื่อนโดย callback แบบกำหนดเอง. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

สร้างและคืนค่า HTML formatter สำหรับมุมมองเอกสารแบบง่ายที่ประกอบด้วยลำดับของสไลด์เรียงต่อกันจากบนลงล่าง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| css | java.lang.String | ระบุ CSS สำหรับไฟล์นี้. |
| showSlideTitle | boolean | เพิ่มชื่อสไลด์หากมีเหนือภาพสไลด์. |

**ค่าที่คืน:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - วัตถุ [HtmlFormatter](../../com.aspose.slides/htmlformatter)

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

สร้างและคืนค่า HTML formatter สำหรับ slide show HTML แบบง่ายที่แสดงสไลด์ต่อกันหนึ่งต่อหนึ่ง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| css | java.lang.String | ระบุ URL ของไฟล์ CCS ที่ใช้. |
| showSlideTitle | boolean | เพิ่มชื่อสไลด์หากมีเหนือภาพสไลด์. |

**ค่าที่คืน:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - วัตถุ [HtmlFormatter](../../com.aspose.slides/htmlformatter)

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

สร้างและคืนค่า HTML formatter สำหรับการสร้าง HTML ที่ขับเคลื่อนโดย callback แบบกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | ส่วนต่อประสาน callback ที่ควบคุมการสร้างไฟล์ html. |

**ค่าที่คืน:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - วัตถุ [HtmlFormatter](../../com.aspose.slides/htmlformatter)