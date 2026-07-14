---
title: IOverridableText
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงข้อความที่สามารถเขียนทับได้สำหรับแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ioverridabletext/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

แสดงข้อความที่สามารถเขียนทับได้สำหรับแผนภูมิ.
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | สามารถมีข้อความที่จัดรูปแบบอย่างอุดมการณ์ได้ |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text" |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


สามารถมีข้อความที่จัดรูปแบบอย่างอุดมการณ์ได้ หากคุณสมบัตินี้ไม่เป็น null แล้วค่าข้อความที่จัดรูปแบบนี้จะทับข้อความที่สร้างโดยอัตโนมัติ ข้อความที่สร้างโดยอัตโนมัติเป็นคุณสมบัติแฝงของป้ายข้อมูล, ป้ายหน่วยแสดงของแกนค่า, ชื่อแกน, ชื่อแผนภูมิ, ป้ายของเส้นแนวโน้ม ข้อความที่สร้างโดยอัตโนมัติจะถูกจัดรูปแบบด้วยคุณสมบัติ IFormattedTextContainer.TextFormat อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text" หาก TextFrameForOverriding ได้รับการเริ่มต้นแล้วก็จะเปลี่ยนข้อความของมันโดยตรง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความสำหรับ TextFrameForOverriding ใหม่ |

**คืนค่า:**
[ITextFrame](../../com.aspose.slides/itextframe) - กรอบข้อความ [ITextFrame](../../com.aspose.slides/itextframe)