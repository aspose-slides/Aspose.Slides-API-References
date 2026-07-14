---
title: ITextStyleEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงได้ซึ่งมีคุณสมบัติสไตล์ข้อความที่มีประสิทธิภาพ
type: docs
url: /th/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงได้ซึ่งมีคุณสมบัติสไตล์ข้อความที่มีประสิทธิภาพ

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [ITextStyle](../../com.aspose.slides/itextstyle) เพื่อคืนค่าการจัดรูปแบบที่มีประสิทธิภาพพร้อมการสืบทอดที่ใช้
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | คืนค่าระดับของสไตล์ที่มีประสิทธิภาพ |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | คืนค่าคุณสมบัติย่อหน้ามาตรฐานที่มีประสิทธิภาพ |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

คืนค่าระดับของสไตล์ที่มีประสิทธิภาพ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีระดับที่เริ่มนับจากศูนย์ ต้องอยู่ในช่วง 0..8 |

**คืนค่า:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - การจัดรูปแบบที่มีประสิทธิภาพของระดับ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

คืนค่าคุณสมบัติย่อหน้ามาตรฐานที่มีประสิทธิภาพ อ่านอย่างเดียว [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)

**คืนค่า:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)