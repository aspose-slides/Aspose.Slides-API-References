---
title: HyperlinkQueries
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย.
type: docs
url: /th/com.aspose.slides/hyperlinkqueries/
---
**สืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | รับอ็อบเจกต์ย่อย IHyperlinkContainer ทั้งหมดซึ่งมี HyperlinkClick ไม่เป็นค่า null. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | รับอ็อบเจกต์ย่อย IHyperlinkContainer ทั้งหมดซึ่งมี HyperlinkMouseOver ไม่เป็นค่า null. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | รับอ็อบเจกต์ย่อย IHyperlinkContainer ทั้งหมดซึ่งมี HyperlinkMouseOver ไม่เป็นค่า null. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | ลบไฮเปอร์ลิงก์ HyperlinkClick และ HyperlinkMouseOver ทั้งหมดที่บรรจุอยู่ (ในอ็อบเจกต์ย่อย IHyperlinkContainer ทั้งหมด). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


รับอ็อบเจกต์ย่อย IHyperlinkContainer ทั้งหมดที่มี HyperlinkClick ไม่เป็นค่า null. ด้วยอ็อบเจกต์ IHyperlinkContainer ที่ให้มา คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, ปรับปรุงหรือถอนออก) ดูอินเทอร์เฟซ IHyperlinkContainer.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


รับอ็อบเจกต์ย่อย IHyperlinkContainer ทั้งหมดซึ่งมี HyperlinkMouseOver ไม่เป็นค่า null. ด้วยอ็อบเจกต์ IHyperlinkContainer ที่ให้มา คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, ปรับปรุงหรือถอนออก) ดูอินเทอร์เฟซ IHyperlinkContainer.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


รับอ็อบเจกต์ย่อย IHyperlinkContainer ทั้งหมดซึ่งมี HyperlinkMouseOver ไม่เป็นค่า null. ด้วยอ็อบเจกต์ IHyperlinkContainer ที่ให้มา คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, ปรับปรุงหรือถอนออก) ดูอินเทอร์เฟซ IHyperlinkContainer.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```


ลบไฮเปอร์ลิงก์ HyperlinkClick และ HyperlinkMouseOver ทั้งหมดที่บรรจุอยู่ (ในอ็อบเจกต์ย่อย IHyperlinkContainer ทั้งหมด).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject