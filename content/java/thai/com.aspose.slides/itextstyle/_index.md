---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
description: Text style formatting properties.
type: docs
url: /th/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

คุณสมบัติการจัดรูปแบบสไตล์ข้อความ.
## เมธอด

| Method | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | หากระดับของสไตล์มีอยู่จะคืนค่าระดับนั้น มิฉะนั้นจะคืนค่า null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | คุณสมบัติย่อหน้าตั้งค่าเริ่มต้น. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบสไตล์ข้อความที่มีผลพร้อมการสืบทอดที่นำมาใช้. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

หากระดับของสไตล์มีอยู่จะคืนค่าระดับนั้น มิฉะนั้นจะคืนค่า null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของระดับ. ต้องอยู่ในช่วง 0..8. |

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - การจัดรูปแบบของระดับ [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

คุณสมบัติย่อหน้าตั้งค่าเริ่มต้น. อ่านอย่างเดียว [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบสไตล์ข้อความที่มีผลพร้อมการสืบทอดที่นำมาใช้.

**Returns:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - A [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).