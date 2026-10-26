---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: Represents node of a SmartArt diagram.
type: docs
url: /th/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

แสดงถึงโหนดของแผนภาพ SmartArt.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | ส่งคืนคอลเลกชันของโหนดลูกทั้งหมดของโหนดปัจจุบัน. |
| [getShapes()](#getShapes--) | ส่งคืนคอลเลกชันของรูปร่างทั้งหมดที่เชื่อมโยงกับโหนด. |
| [getTextFrame()](#getTextFrame--) | ส่งคืนหรือกำหนดข้อความของโหนด. |
| [isAssistant()](#isAssistant--) | ส่งคืนหรือกำหนดโหนดเป็นผู้ช่วย. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | ส่งคืนหรือกำหนดโหนดเป็นผู้ช่วย. |
| [getLevel()](#getLevel--) | ส่งคืนระดับการซ้อนของโหนด. |
| [getBulletFillFormat()](#getBulletFillFormat--) | ส่งคืนอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับหัวข้อย่อยของโหนด. |
| [getPosition()](#getPosition--) | ส่งคืนหรือกำหนดตำแหน่งเริ่มจากศูนย์ของโหนดในจำนวนโหนดพี่น้อง. |
| [setPosition(int value)](#setPosition-int-) | ส่งคืนหรือกำหนดตำแหน่งเริ่มจากศูนย์ของโหนดในจำนวนโหนดพี่น้อง. |
| [isHidden()](#isHidden--) | ส่งคืน true หากโหนดนี้เป็นโหนดที่ซ่อนอยู่ในโมเดลข้อมูล. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | ส่งคืนหรือกำหนดประเภทการจัดวางแผนภาพองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | ส่งคืนหรือกำหนดประเภทการจัดวางแผนภาพองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน. |
| [remove()](#remove--) | ลบโหนดปัจจุบัน. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

ส่งคืนคอลเลกชันของโหนดลูกทั้งหมดของโหนดปัจจุบัน. อ่านอย่างเดียว [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**ค่าที่ส่งคืน:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

ส่งคืนคอลเลกชันของรูปร่างทั้งหมดที่เชื่อมโยงกับโหนด. อ่านอย่างเดียว [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**ค่าที่ส่งคืน:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

ส่งคืนหรือกำหนดข้อความของโหนด. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**ค่าที่ส่งคืน:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

ส่งคืนหรือกำหนดโหนดเป็นผู้ช่วย. อ่าน/เขียน boolean.

**ค่าที่ส่งคืน:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

ส่งคืนหรือกำหนดโหนดเป็นผู้ช่วย. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

ส่งคืนระดับการซ้อนของโหนด. อ่านอย่างเดียว int.

**ค่าที่ส่งคืน:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

ส่งคืนอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับหัวข้อย่อยของโหนด. หมายเหตุ: สามารถส่งคืน null สำหรับประเภทของการจัดวาง SmartArt บางประเภทที่ไม่ได้ให้หัวข้อย่อยสำหรับโหนด. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**ค่าที่ส่งคืน:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

ส่งคืนหรือกำหนดตำแหน่งเริ่มจากศูนย์ของโหนดในจำนวนโหนดพี่น้อง. อ่าน/เขียน int.

**ค่าที่ส่งคืน:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

ส่งคืนหรือกำหนดตำแหน่งเริ่มจากศูนย์ของโหนดในจำนวนโหนดพี่น้อง. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

ส่งคืน true หากโหนดนี้เป็นโหนดที่ซ่อนอยู่ในโมเดลข้อมูล. อ่านอย่างเดียว boolean.

**ค่าที่ส่งคืน:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

ส่งคืนหรือกำหนดประเภทการจัดวางแผนภาพองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน. อ่าน/เขียน [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**ค่าที่ส่งคืน:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

ส่งคืนหรือกำหนดประเภทการจัดวางแผนภาพองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน. อ่าน/เขียน [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

ลบโหนดปัจจุบัน.

**ค่าที่ส่งคืน:** boolean - true หากลบสำเร็จ, มิฉะนั้น false.