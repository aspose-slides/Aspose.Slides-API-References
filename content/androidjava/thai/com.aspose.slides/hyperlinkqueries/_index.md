---
title: HyperlinkQueries
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุไว้อย่างง่ายดาย.
type: docs
url: /th/com.aspose.slides/hyperlinkqueries/
---
**การสืบทอด:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุไว้ได้อย่างง่ายดาย.
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | รับทุกออบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkClick ที่ไม่เป็น null. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | รับทุกออบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkMouseOver ที่ไม่เป็น null. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | รับทุกออบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkMouseOver ที่ไม่เป็น null. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | ลบไฮเปอร์ลิงก์ HyperlinkClick และ HyperlinkMouseOver ทั้งหมดที่บรรจุอยู่ (ในทุกออบเจ็กต์ย่อย IHyperlinkContainer). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

รับทุกออบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkClick ที่ไม่เป็น null. ด้วยออบเจ็กต์ IHyperlinkContainer ที่ให้มา คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, ปรับปรุงหรือเอาออก). ดูอินเทอร์เฟซ IHyperlinkContainer.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

รับทุกออบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkMouseOver ที่ไม่เป็น null. ด้วยออบเจ็กต์ IHyperlinkContainer ที่ให้มา คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, ปรับปรุงหรือเอาออก). ดูอินเทอร์เฟซ IHyperlinkContainer.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

รับทุกออบเจ็กต์ย่อย IHyperlinkContainer ที่มี HyperlinkMouseOver ที่ไม่เป็น null. ด้วยออบเจ็กต์ IHyperlinkContainer ที่ให้มา คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, ปรับปรุงหรือเอาออก). ดูอินเทอร์เฟซ IHyperlinkContainer.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```

ลบไฮเปอร์ลิงก์ HyperlinkClick และ HyperlinkMouseOver ทั้งหมดที่บรรจุอยู่ (ในทุกออบเจ็กต์ย่อย IHyperlinkContainer).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ผลลัพธ์:**
com.aspose.slides.IDOMObject