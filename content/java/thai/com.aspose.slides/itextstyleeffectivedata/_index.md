---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective text style properties.
type: docs
url: /th/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

ออบเจ็กต์ที่ไม่สามารถเปลี่ยนแปลงได้ซึ่งบรรจุคุณสมบัติสไตล์ข้อความที่มีผล

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [ITextStyle](../../com.aspose.slides/itextstyle) เพื่อคืนค่าการจัดรูปแบบที่มีผลโดยใช้การสืบทอด

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | คืนระดับของสไตล์ที่มีผล |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | คืนคุณสมบัติย่อหน้าเริ่มต้นที่มีผล |

### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

คืนระดับของสไตล์ที่มีผล

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีระดับที่เริ่มจากศูนย์ ต้องอยู่ในช่วง 0..8 |

**คืนค่า:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - การจัดรูปแบบที่มีผลของระดับ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

คืนคุณสมบัติย่อหน้าเริ่มต้นที่มีผล อ่านอย่างเดียว [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**คืนค่า:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)