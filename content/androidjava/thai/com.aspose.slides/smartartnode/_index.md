---
title: SmartArtNode
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของโหนดในอ็อบเจ็กต์ SmartArt
type: docs
url: /th/com.aspose.slides/smartartnode/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

เป็นตัวแทนโหนดของอ็อบเจ็กต์ SmartArt
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | คืนค่าชุดของโหนดลูกทั้งหมดของโหนดปัจจุบัน. |
| [getShapes()](#getShapes--) | คืนค่าชุดของรูปร่างทั้งหมดที่เชื่อมโยงกับโหนด. |
| [getTextFrame()](#getTextFrame--) | คืนค่าเฟรมข้อความของโหนด. |
| [isAssistant()](#isAssistant--) | คืนค่าหรือกำหนดโหนดเป็นผู้ช่วย. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | คืนค่าหรือกำหนดโหนดเป็นผู้ช่วย. |
| [getLevel()](#getLevel--) | คืนค่าระดับการซ้อนของโหนด. |
| [getBulletFillFormat()](#getBulletFillFormat--) | คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับ bullet ของโหนด. |
| [getPosition()](#getPosition--) | คืนค่าหรือกำหนดตำแหน่งโดยเริ่มจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง. |
| [setPosition(int value)](#setPosition-int-) | คืนค่าหรือกำหนดตำแหน่งโดยเริ่มจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง. |
| [isHidden()](#isHidden--) | คืนค่า true หากโหนดนี้เป็นโหนดที่ซ่อนอยู่ในโมเดลข้อมูล. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | คืนค่าหรือกำหนดประเภทการจัดเรียงแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | คืนค่าหรือกำหนดประเภทการจัดเรียงแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน. |
| [remove()](#remove--) | ลบโหนดปัจจุบัน. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```


คืนค่าชุดของโหนดลูกทั้งหมดของโหนดปัจจุบัน. อ่านอย่างเดียว [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**คืนค่า:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```


คืนค่าชุดของรูปร่างทั้งหมดที่เชื่อมโยงกับโหนด. อ่านอย่างเดียว [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**คืนค่า:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


คืนค่าเฟรมข้อความของโหนด. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```


คืนค่าหรือกำหนดโหนดเป็นผู้ช่วย. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```


คืนค่าหรือกำหนดโหนดเป็นผู้ช่วย. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```


คืนค่าระดับการซ้อนของโหนด. อ่านอย่างเดียว int.

**คืนค่า:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```


คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับ bullet ของโหนด. หมายเหตุ: สามารถคืนค่า null สำหรับประเภทบางอย่างของการจัดรูปแบบ SmartArt ที่ไม่มี bullet สำหรับโหนด. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


คืนค่าหรือกำหนดตำแหน่งโดยเริ่มจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง. อ่าน/เขียน int .

**คืนค่า:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


คืนค่าหรือกำหนดตำแหน่งโดยเริ่มจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง. อ่าน/เขียน int .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


คืนค่า true หากโหนดนี้เป็นโหนดที่ซ่อนอยู่ในโมเดลข้อมูล. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```


คืนค่าหรือกำหนดประเภทการจัดเรียงแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน. อ่าน/เขียน [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**คืนค่า:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```


คืนค่าหรือกำหนดประเภทการจัดเรียงแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน. อ่าน/เขียน [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```


ลบโหนดปัจจุบัน.

**คืนค่า:**
boolean - true หากลบสำเร็จ, มิฉะนั้น false