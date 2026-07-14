---
title: IWarningInfo
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นอินเทอร์เฟซฐานสำหรับการเตือนทั้งหมด.
type: docs
url: /th/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

เป็นอินเทอร์เฟซฐานสำหรับการเตือนทั้งหมด.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | หาก receiver ไม่เป็น null จะจบการเตือนไปยัง receiver ที่ระบุและโยน AbortRequestedException หาก receiver ตัดสินใจยกเลิกการทำงาน |
| [getWarningType()](#getWarningType--) | คืนค่าชนิดของการเตือน |
| [getDescription()](#getDescription--) | คืนค่าคำอธิบายที่อ่านเป็นภาษามนุษย์ของการเตือนนี้ |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

หาก receiver ไม่เป็น null จะจบการเตือนไปยัง receiver ที่ระบุและโยน AbortRequestedException หาก receiver ตัดสินใจยกเลิกการทำงาน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Receiver อ็อบเจกต์ [IWarningCallback](../../com.aspose.slides/iwarningcallback) |
### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

คืนค่าชนิดของการเตือน. อ่านอย่างเดียว [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**คืนค่า:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

คืนค่าคำอธิบายที่อ่านได้ของการเตือนนี้. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String