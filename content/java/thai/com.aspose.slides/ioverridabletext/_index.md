---
title: IOverridableText
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนข้อความที่สามารถเขียนทับได้สำหรับแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ioverridabletext/
---
**อินเทอร์เฟซที่ดำเนินการทั้งหมด:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

เป็นตัวแทนข้อความที่สามารถเขียนทับได้สำหรับแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | สามารถมีข้อความที่จัดรูปแบบอย่างหลากหลายได้. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

สามารถมีข้อความที่จัดรูปแบบอย่างหลากหลายได้ หากคุณสมบัตินี้ไม่เป็นค่า null แล้วค่าข้อความที่จัดรูปแบบนี้จะเขียนทับข้อความที่สร้างโดยอัตโนมัติ ข้อความที่สร้างโดยอัตโนมัติเป็นคุณสมบัติโรงImplicit ของป้ายข้อมูล, ป้ายหน่วยการแสดงผลของแกนค่า, ชื่อแกน, ชื่อแผนภูมิ, ป้ายของเส้นแนวโน้ม ข้อความที่สร้างโดยอัตโนมัติถูกจัดรูปแบบด้วยคุณสมบัติ IFormattedTextContainer.TextFormat. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text". หาก TextFrameForOverriding ถูกเริ่มต้นไว้แล้วจะทำการเปลี่ยนข้อความของมันอย่างง่ายดาย.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความสำหรับ TextFrameForOverriding ใหม่. |

**คืนค่า:**
[ITextFrame](../../com.aspose.slides/itextframe) - กรอบข้อความ [ITextFrame](../../com.aspose.slides/itextframe)