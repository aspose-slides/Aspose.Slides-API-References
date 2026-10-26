---
title: ITabEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการหยุดแท็บของข้อความที่มีผล.
type: docs
url: /th/com.aspose.slides/itabeffectivedata/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการหยุดแท็บของข้อความที่มีผล.

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPosition()](#getPosition--) | ส่งคืนตำแหน่งของแท็บ. |
| [getAlignment()](#getAlignment--) | ส่งคืนสไตล์การจัดแนวของแท็บ. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


ส่งคืนตำแหน่งของแท็บ. การกำหนดค่าคุณสมบัตินี้สามารถเปลี่ยนดัชนีของแท็บในคอลเลกชันและทำให้ Enumerator ไม่ถูกต้อง. อ่านอย่างเดียว double.

**คืนค่า:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


ส่งคืนสไตล์การจัดแนวของแท็บ. อ่านอย่างเดียว [TabAlignment](../../com.aspose.slides/tabalignment).

**คืนค่า:**
int