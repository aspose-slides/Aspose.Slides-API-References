---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides สำหรับ Java API Reference
description: อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีผล
type: docs
url: /th/com.aspose.slides/iportionformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีผล

--------------------

ส่วนต่อประสานนี้ใช้ร่วมกับส่วนต่อประสาน [IPortionFormat](../../com.aspose.slides/iportionformat) เพื่อคืนค่าการจัดรูปแบบที่มีผลพร้อมกับการสืบทอดที่ใช้

## เมธอด

| Method | Description |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | คืนค่าตัวระบุของที่คั่นหน้า |
| [getHyperlinkClick()](#getHyperlinkClick--) | คืนค่าลิงก์ที่กำหนดสำหรับการคลิกเมาส์ |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | คืนค่าลิงก์ที่กำหนดสำหรับการวางเมาส์ |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


คืนค่าตัวระบุของที่คั่นหน้า. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


คืนค่าลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่านอย่างเดียว [IHyperlink](../../com.aspose.slides/ihyperlink).

**คืนค่า:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


คืนค่าลิงก์ที่กำหนดสำหรับการวางเมาส์. อ่านอย่างเดียว [IHyperlink](../../com.aspose.slides/ihyperlink).

**คืนค่า:**
[IHyperlink](../../com.aspose.slides/ihyperlink)