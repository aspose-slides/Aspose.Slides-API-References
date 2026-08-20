---
title: ITabEffectiveData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ออบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการหยุดแท็บของข้อความที่มีประสิทธิภาพ
type: docs
url: /th/com.aspose.slides/itabeffectivedata/
---
**All Implemented Interfaces:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการหยุดแท็บของข้อความที่มีประสิทธิภาพ

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getPosition()](#getPosition--) | คืนค่าตำแหน่งของแท็บ |
| [getAlignment()](#getAlignment--) | คืนค่าสไตล์การจัดแนวของแท็บ |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


คืนค่าตำแหน่งของแท็บ การกำหนดค่าคุณสมบัตินี้สามารถเปลี่ยนดัชนีของแท็บในคอลเลกชันและทำให้ Enumerator หมดผลการทำงานได้. อ่านอย่างเดียว double.

**Returns:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


คืนค่าสไตล์การจัดแนวของแท็บ. อ่านอย่างเดียว [TabAlignment](../../com.aspose.slides/tabalignment).

**Returns:**
int