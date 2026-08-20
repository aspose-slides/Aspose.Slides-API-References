---
title: IPortionFormat
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนของข้อความ.
type: docs
url: /th/com.aspose.slides/iportionformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนของข้อความ. ไม่เหมือน [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

--------------------

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนของข้อความที่กำหนดสำหรับส่วนเฉพาะ. ซึ่งหมายความว่าไม่มีการสืบทอดเมื่อดึงค่าจึงในกรณีส่วนใหญ่คุณจะได้รับค่าที่หมายถึง "undefined".

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด, คุณต้องใช้เมธอด [getEffective](../../com.aspose.slides/iportionformat\#getEffective) ซึ่งส่งคืนอินสแตนซ์ [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) instance.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | ส่งคืนหรือกำหนดตัวระบุ bookmark. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | ส่งคืนหรือกำหนดตัวระบุ bookmark. |
| [getSmartTagClean()](#getSmartTagClean--) | กำหนดว่า smart tag ควรทำความสะอาดหรือไม่. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | กำหนดว่า smart tag ควรทำความสะอาดหรือไม่. |
| [getEffective()](#getEffective--) | ดึงข้อมูลการจัดรูปแบบส่วนที่มีผลโดยมีการสืบทอด. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

ส่งคืนหรือกำหนดตัวระบุ bookmark. อ่าน/เขียน String.

**ส่งคืน:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

ส่งคืนหรือกำหนดตัวระบุ bookmark. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

กำหนดว่า smart tag ควรทำความสะอาดหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

กำหนดว่า smart tag ควรทำความสะอาดหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

ดึงข้อมูลการจัดรูปแบบส่วนที่มีผลโดยมีการสืบทอด.

**ส่งคืน:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).