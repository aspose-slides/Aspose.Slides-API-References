---
title: FormatFactory
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: อนุญาตให้สร้างรูปแบบผ่านอินเทอร์เฟซ COM.
type: docs
url: /th/com.aspose.slides/formatfactory/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
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
| [getInstance()](#getInstance--) | อินสแตนซ์โรงงานรูปแบบแบบคงที่. |
| [createPortionFormat()](#createPortionFormat--) | สร้าง [IPortionFormat](../../com.aspose.slides/iportionformat) ใหม่. |
| [createParagraphFormat()](#createParagraphFormat--) | สร้าง [IParagraphFormat](../../com.aspose.slides/iparagraphformat) ใหม่. |
| [createTextFrameFormat()](#createTextFrameFormat--) | สร้าง [ITextFrameFormat](../../com.aspose.slides/itextframeformat) ใหม่. |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


อินสแตนซ์โรงงานรูปแบบแบบคงที่. อ่านอย่างเดียว [FormatFactory](../../com.aspose.slides/formatfactory).

**คืนค่า:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


สร้าง [IPortionFormat](../../com.aspose.slides/iportionformat) ใหม่.

**คืนค่า:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - รูปแบบส่วนใหม่.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


สร้าง [IParagraphFormat](../../com.aspose.slides/iparagraphformat) ใหม่.

**คืนค่า:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - รูปแบบย่อหน้ใหม่.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


สร้าง [ITextFrameFormat](../../com.aspose.slides/itextframeformat) ใหม่.

**คืนค่า:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - รูปแบบกรอบข้อความใหม่.