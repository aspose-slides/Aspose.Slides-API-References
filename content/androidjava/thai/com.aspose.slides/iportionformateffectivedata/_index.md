---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ออบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีผล.
type: docs
url: /th/com.aspose.slides/iportionformateffectivedata/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

ออบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติการจัดรูปแบบส่วนข้อความที่มีผล

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IPortionFormat](../../com.aspose.slides/iportionformat) เพื่อคืนค่าการจัดรูปแบบที่มีผลโดยใช้การสืบทอด

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | คืนค่า identifier ของบุ๊กมาร์ก. |
| [getHyperlinkClick()](#getHyperlinkClick--) | คืนค่า hyperlink ที่กำหนดสำหรับการคลิกเมาส์. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | คืนค่า hyperlink ที่กำหนดสำหรับการวางเมาส์. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

คืนค่า identifier ของบุ๊กมาร์ก. อ่าน-อย่างเดียว String.

**คืนค่า:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```

คืนค่า hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน-อย่างเดียว [IHyperlink](../../com.aspose.slides/ihyperlink).

**คืนค่า:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```java
public abstract IHyperlink getHyperlinkMouseOver()
```

คืนค่า hyperlink ที่กำหนดสำหรับการวางเมาส์. อ่าน-อย่างเดียว [IHyperlink](../../com.aspose.slides/ihyperlink).

**คืนค่า:**
[IHyperlink](../../com.aspose.slides/ihyperlink)