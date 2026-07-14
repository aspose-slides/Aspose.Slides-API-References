---
title: ChartTextFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุการจัดรูปแบบข้อความเริ่มต้นสำหรับองค์ประกอบข้อความของแผนภูมิ.
type: docs
url: /th/com.aspose.slides/charttextformat/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่ Implement ทั้งหมด:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

ระบุการจัดรูปแบบข้อความเริ่มต้นสำหรับองค์ประกอบข้อความของแผนภูมิ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | คัดลอกการจัดรูปแบบข้อความไปยังเฟรมข้อความที่ระบุ. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | คัดลอกการจัดรูปแบบข้อความจากเฟรมข้อความที่ระบุ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```

TextBlockFormat. อ่านอย่างเดียว [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**คืนค่า:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```

ParagraphFormat. อ่านอย่างเดียว [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**คืนค่า:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```

PortionFormat. อ่านอย่างเดียว [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**คืนค่า:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```

คัดลอกการจัดรูปแบบข้อความไปยังเฟรมข้อความที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | เฟรมข้อความที่จะคัดลอกการจัดรูปแบบข้อความไปยัง. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```

คัดลอกการจัดรูปแบบข้อความจากเฟรมข้อความที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | เฟรมข้อความที่จะคัดลอกการจัดรูปแบบข้อความ. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject