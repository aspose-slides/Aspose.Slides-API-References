---
title: IHyperlinkQueries
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย.
type: docs
url: /th/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | ดึง IHyperlinkContainer subobjects ทั้งหมดที่มี HyperlinkClick ไม่เป็น null. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | ดึง IHyperlinkContainer subobjects ทั้งหมดที่มี HyperlinkMouseOver ไม่เป็น null. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | ดึง IHyperlinkContainer subobjects ทั้งหมดที่มี HyperlinkMouseOver ไม่เป็น null. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | ลบไฮเปอร์ลิงก์ HyperlinkClick และ HyperlinkMouseOver ทั้งหมดที่บรรจุอยู่ (ใน IHyperlinkContainer subobjects ทั้งหมด). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

ดึง IHyperlinkContainer subobjects ทั้งหมดที่มี HyperlinkClick ไม่เป็น null. ด้วยอ็อบเจ็กต์ IHyperlinkContainer ที่กำหนด คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, อัปเดต หรือ ลบ). ดูอินเทอร์เฟซ IHyperlinkContainer.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

ดึง IHyperlinkContainer subobjects ทั้งหมดที่มี HyperlinkMouseOver ไม่เป็น null. ด้วยอ็อบเจ็กต์ IHyperlinkContainer ที่กำหนด คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, อัปเดต หรือ ลบ). ดูอินเทอร์เฟซ IHyperlinkContainer.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

ดึง IHyperlinkContainer subobjects ทั้งหมดที่มี HyperlinkMouseOver ไม่เป็น null. ด้วยอ็อบเจ็กต์ IHyperlinkContainer ที่กำหนด คุณสามารถจัดการไฮเปอร์ลิงก์ของมัน (อ่าน, อัปเดต หรือ ลบ). ดูอินเทอร์เฟซ IHyperlinkContainer.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

ลบไฮเปอร์ลิงก์ HyperlinkClick และ HyperlinkMouseOver ทั้งหมดที่บรรจุอยู่ (ใน IHyperlinkContainer subobjects ทั้งหมด).