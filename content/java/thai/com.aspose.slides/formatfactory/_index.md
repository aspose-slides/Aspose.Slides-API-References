---
title: FormatFactory
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: อนุญาตให้สร้างรูปแบบผ่านอินเทอร์เฟซ COM.
type: docs
url: /th/com.aspose.slides/formatfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

อนุญาตให้สร้างรูปแบบผ่านอินเทอร์เฟซ COM.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getInstance()](#getInstance--) | Format factory static instance. |
| [createPortionFormat()](#createPortionFormat--) | สร้างใหม่ [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | สร้างใหม่ [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | สร้างใหม่ [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```

### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```

Format factory static instance. อ่านอย่างเดียว [FormatFactory](../../com.aspose.slides/formatfactory).

**คืนค่า:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

สร้างใหม่ [IPortionFormat](../../com.aspose.slides/iportionformat).

**คืนค่า:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - รูปแบบส่วนใหม่.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

สร้างใหม่ [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**คืนค่า:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - รูปแบบย่อหน้ใหม่.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

สร้างใหม่ [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**คืนค่า:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - รูปแบบเฟรมข้อความใหม่.