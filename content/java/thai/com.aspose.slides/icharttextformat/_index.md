---
title: IChartTextFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แผนภูมิทำงานด้วยชุดคุณสมบัติรูปแบบข้อความที่จำกัด.
type: docs
url: /th/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

แผนภูมิทำงานด้วยชุดคุณสมบัติรูปแบบข้อความที่จำกัด. อินเทอร์เฟซ IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat อธิบายชุดที่จำกัดนี้.
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | ส่งคืนรูปแบบสำหรับองค์ประกอบข้อความของแผนภูมิ. |
| [getParagraphFormat()](#getParagraphFormat--) | ส่งคืนรูปแบบย่อหน้า. |
| [getPortionFormat()](#getPortionFormat--) | ส่งคืนรูปแบบส่วน. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | คัดลอกรูปแบบข้อความไปยังข้อความเฟรมที่ระบุ. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | คัดลอกรูปแบบข้อความจากข้อความเฟรมที่ระบุ. |

### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

ส่งคืนรูปแบบสำหรับองค์ประกอบข้อความของแผนภูมิ. อ่านอย่างเดียว [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**คืนค่า:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)

### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

ส่งคืนรูปแบบย่อหน้า. อ่านอย่างเดียว [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**คืนค่า:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)

### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

ส่งคืนรูปแบบส่วน. อ่านอย่างเดียว [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**คืนค่า:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)

### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

คัดลอกรูปแบบข้อความไปยังข้อความเฟรมที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | ข้อความเฟรมที่ใช้คัดลอกรูปแบบข้อความไปยัง. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

คัดลอกรูปแบบข้อความจากข้อความเฟรมที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | ข้อความเฟรมที่ใช้คัดลอกรูปแบบข้อความ. |