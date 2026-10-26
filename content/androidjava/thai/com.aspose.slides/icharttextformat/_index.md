---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: แผนภูมิทำงานกับชุดคุณสมบัติรูปแบบข้อความที่จำกัด.
type: docs
url: /th/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

แผนภูมิทำงานกับชุดคุณสมบัติรูปแบบข้อความที่จำกัด. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat อินเทอร์เฟซอธิบายชุดที่จำกัดนี้.
## เมธอด

| วิธีการ | คำอธิบาย |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | ส่งคืนรูปแบบสำหรับองค์ประกอบข้อความของแผนภูมิ. |
| [getParagraphFormat()](#getParagraphFormat--) | ส่งคืนรูปแบบย่อหน้า. |
| [getPortionFormat()](#getPortionFormat--) | ส่งคืนรูปแบบส่วน. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | คัดลอกรูปแบบข้อความไปยังกรอบข้อความที่ระบุ. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | คัดลอกรูปแบบข้อความจากกรอบข้อความที่ระบุ. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

ส่งคืนรูปแบบสำหรับองค์ประกอบข้อความของแผนภูมิ. อ่านอย่างเดียว [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**ผลลัพธ์:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

ส่งคืนรูปแบบย่อหน้า. อ่านอย่างเดียว [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**ผลลัพธ์:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

ส่งคืนรูปแบบส่วน. อ่านอย่างเดียว [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**ผลลัพธ์:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

คัดลอกรูปแบบข้อความไปยังกรอบข้อความที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | กรอบข้อความที่จะคัดลอกรูปแบบข้อความไปยัง. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

คัดลอกรูปแบบข้อความจากกรอบข้อความที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | กรอบข้อความที่จะคัดลอกรูปแบบข้อความ. |