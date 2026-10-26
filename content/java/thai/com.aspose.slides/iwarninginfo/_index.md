---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /th/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

เป็นอินเทอร์เฟซพื้นฐานสำหรับคำเตือนทั้งหมด.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | หาก receiver ไม่เป็นค่า null จะส่งคำเตือนไปยัง receiver ที่ระบุและจะทำการโยน AbortRequestedException หาก receiver ตัดสินใจยกเลิกการดำเนินการ. |
| [getWarningType()](#getWarningType--) | คืนชนิดของคำเตือน. |
| [getDescription()](#getDescription--) | คืนคำอธิบายที่อ่านได้ของคำเตือนนี้. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

หาก receiver ไม่เป็นค่า null จะส่งคำเตือนไปยัง receiver ที่ระบุและจะทำการโยน AbortRequestedException หาก receiver ตัดสินใจยกเลิกการดำเนินการ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Receiver object [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

คืนชนิดของคำเตือน. อ่านอย่างเดียว [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**ค่าที่ส่งกลับ:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

คืนคำอธิบายที่อ่านได้ของคำเตือนนี้. อ่านอย่างเดียว String.

**ค่าที่ส่งกลับ:**
java.lang.String