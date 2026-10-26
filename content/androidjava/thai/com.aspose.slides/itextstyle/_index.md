---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Text style formatting properties.
type: docs
url: /th/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

คุณสมบัติการจัดรูปแบบสไตล์ข้อความ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | หากระดับของสไตล์มีอยู่จะคืนค่ามัน, มิฉะนั้นจะคืนค่า null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | คุณสมบัติย่อหน้าดีฟอลต์. |
| [getEffective()](#getEffective--) | ดึงข้อมูลการจัดรูปแบบสไตล์ข้อความที่มีประสิทธิผลพร้อมการสืบทอดที่นำไปใช้. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

หากระดับของสไตล์มีอยู่จะคืนค่ามัน, มิฉะนั้นจะคืนค่า null.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีระดับที่เริ่มจากศูนย์. ต้องอยู่ในช่วง 0..8. |

**ค่าที่ส่งคืน:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - การจัดรูปแบบของระดับ [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

คุณสมบัติย่อหน้าดีฟอลต์. อ่านอย่างเดียว [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**ค่าที่ส่งคืน:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

ดึงข้อมูลการจัดรูปแบบสไตล์ข้อความที่มีประสิทธิผลพร้อมการสืบทอดที่นำไปใช้.

**ค่าที่ส่งคืน:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - A [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).