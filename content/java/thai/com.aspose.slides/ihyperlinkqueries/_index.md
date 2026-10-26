---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Provide easy access to contained hyperlinks.
type: docs
url: /th/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | รับทุกอ็อบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkClick ไม่เป็นค่า null. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | รับทุกอ็อบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkMouseOver ไม่เป็นค่า null. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | รับทุกอ็อบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkMouseOver ไม่เป็นค่า null. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | ลบไฮเปอร์ลิงก์ HyperlinkClick และ HyperlinkMouseOver ที่บรรจุอยู่ทั้งหมด (ในอ็อบเจ็กต์ย่อย IHyperlinkContainer ทั้งหมด). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

รับทุกอ็อบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkClick ไม่เป็นค่า null. ด้วยอ็อบเจ็กต์ IHyperlinkContainer ที่กำหนด คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, อัปเดต หรือ ลบ). โปรดดูอินเทอร์เฟซ IHyperlinkContainer.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - ทุกอ็อบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkClick ไม่เป็นค่า null
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

รับทุกอ็อบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkMouseOver ไม่เป็นค่า null. ด้วยอ็อบเจ็กต์ IHyperlinkContainer ที่กำหนด คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, อัปเดต หรือ ลบ). โปรดดูอินเทอร์เฟซ IHyperlinkContainer.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - ทุกอ็อบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkMouseOver ไม่เป็นค่า null
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

รับทุกอ็อบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkMouseOver ไม่เป็นค่า null. ด้วยอ็อบเจ็กต์ IHyperlinkContainer ที่กำหนด คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, อัปเดต หรือ ลบ). โปรดดูอินเทอร์เฟซ IHyperlinkContainer.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - ทุกอ็อบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkMouseOver ไม่เป็นค่า null
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

ลบไฮเปอร์ลิงก์ HyperlinkClick และ HyperlinkMouseOver ที่บรรจุอยู่ทั้งหมด (ในอ็อบเจ็กต์ย่อย IHyperlinkContainer ทั้งหมด).