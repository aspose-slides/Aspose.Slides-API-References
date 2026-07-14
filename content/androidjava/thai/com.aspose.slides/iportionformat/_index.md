---
title: IPortionFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: คลาสนี้ประกอบด้วยคุณสมบัติกำหนดรูปแบบส่วนข้อความ.
type: docs
url: /th/com.aspose.slides/iportionformat/
---
**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

คลาสนี้ประกอบด้วยคุณสมบัติกำหนดรูปแบบส่วนข้อความ. แตกต่างจาก [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), คุณสมบัติต่าง ๆ ของคลาสนี้สามารถเขียนได้.

--------------------

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติกำหนดรูปแบบส่วนข้อความที่กำหนดไว้สำหรับส่วนที่เฉพาะเจาะจง. ซึ่งหมายความว่าไม่มีการสืบทอดใช้เมื่อดึงค่า ดังนั้นในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง "undefined".

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอดคุณจำเป็นต้องใช้เมธอด [getEffective](../../com.aspose.slides/iportionformat\#getEffective) ซึ่งจะคืนค่าเป็นอินสแตนซ์ของ [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | คืนค่า หรือ ตั้งค่าตัวระบุ bookmark. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | คืนค่า หรือ ตั้งค่าตัวระบุ bookmark. |
| [getSmartTagClean()](#getSmartTagClean--) | กำหนดว่าควรทำความสะอาด smart tag หรือไม่. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | กำหนดว่าควรทำความสะอาด smart tag หรือไม่. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบส่วนข้อความที่มีการสืบทอดใช้. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

คืนค่า หรือ ตั้งค่าตัวระบุ bookmark. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

คืนค่า หรือ ตั้งค่าตัวระบุ bookmark. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

กำหนดว่าควรทำความสะอาด smart tag หรือไม่. ไม่มีการสืบทอดใช้. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

กำหนดว่าควรทำความสะอาด smart tag หรือไม่. ไม่มีการสืบทอดใช้. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบส่วนข้อความที่มีการสืบทอดใช้.

**คืนค่า:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - เป็น [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).