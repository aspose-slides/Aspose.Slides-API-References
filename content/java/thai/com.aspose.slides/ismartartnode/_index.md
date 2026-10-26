---
title: ISmartArtNode
second_title: Aspose.Slides for Java API Reference
description: แทนโหนดของแผนภาพ SmartArt.
type: docs
url: /th/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

แทนโหนดของแผนภาพ SmartArt.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | ส่งกลับคอลเลกชันของโหนดลูกทั้งหมดของโหนดปัจจุบัน |
| [getShapes()](#getShapes--) | ส่งกลับคอลเลกชันของรูปทั้งหมดที่เชื่อมโยงกับโหนด |
| [getTextFrame()](#getTextFrame--) | ส่งกลับหรือกำหนดข้อความของโหนด |
| [isAssistant()](#isAssistant--) | ส่งกลับหรือกำหนดโหนดเป็นผู้ช่วย |
| [setAssistant(boolean value)](#setAssistant-boolean-) | ส่งกลับหรือกำหนดโหนดเป็นผู้ช่วย |
| [getLevel()](#getLevel--) | ส่งกลับระดับการซ้อนของโหนด |
| [getBulletFillFormat()](#getBulletFillFormat--) | ส่งกลับอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับจุดหัวกระสุนของโหนด |
| [getPosition()](#getPosition--) | ส่งกลับหรือกำหนดตำแหน่งเริ่มจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง |
| [setPosition(int value)](#setPosition-int-) | ส่งกลับหรือกำหนดตำแหน่งเริ่มจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง |
| [isHidden()](#isHidden--) | ส่งกลับ true หากโหนดนี้เป็นโหนดที่ซ่อนในโมเดลข้อมูล |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | ส่งกลับหรือกำหนดประเภทการจัดวางแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | ส่งกลับหรือกำหนดประเภทการจัดวางแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน |
| [remove()](#remove--) | ลบโหนดปัจจุบัน |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

ส่งกลับคอลเลกชันของโหนดลูกทั้งหมดของโหนดปัจจุบัน อ่านอย่างเดียว [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**คืนค่า:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

ส่งกลับคอลเลกชันของรูปทั้งหมดที่เชื่อมโยงกับโหนด อ่านอย่างเดียว [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**คืนค่า:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

ส่งกลับหรือกำหนดข้อความของโหนด อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

ส่งกลับหรือกำหนดโหนดเป็นผู้ช่วย อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

ส่งกลับหรือกำหนดโหนดเป็นผู้ช่วย อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

ส่งกลับระดับการซ้อนของโหนด อ่านอย่างเดียว int.

**คืนค่า:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

ส่งกลับอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับจุดหัวกระสุนของโหนด  หมายเหตุ: สามารถคืนค่า null สำหรับประเภทของ SmartArt layout ที่บางประเภทไม่มีจุดหัวกระสุนสำหรับโหนด อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

ส่งกลับหรือกำหนดตำแหน่งเริ่มจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง อ่าน/เขียน int.

**คืนค่า:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

ส่งกลับหรือกำหนดตำแหน่งเริ่มจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

ส่งกลับ true หากโหนดนี้เป็นโหนดที่ซ่อนในโมเดลข้อมูล อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

ส่งกลับหรือกำหนดประเภทการจัดวางแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน อ่าน/เขียน [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**คืนค่า:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

ส่งกลับหรือกำหนดประเภทการจัดวางแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน อ่าน/เขียน [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

ลบโหนดปัจจุบัน.

**คืนค่า:**
boolean - true หากลบสำเร็จ มิฉะนั้น false.