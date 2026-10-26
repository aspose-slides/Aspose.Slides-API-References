---
title: SmartArtNode
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงโหนดของอ็อบเจ็กต์ SmartArt
type: docs
url: /th/com.aspose.slides/smartartnode/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)  
```
public final class SmartArtNode implements ISmartArtNode
```

แสดงโหนดของอ็อบเจ็กต์ SmartArt

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | คืนคอลเลกชันของโหนดลูกทั้งหมดของโหนดปัจจุบัน |
| [getShapes()](#getShapes--) | คืนคอลเลกชันของรูปร่างทั้งหมดที่เชื่อมโยงกับโหนด |
| [getTextFrame()](#getTextFrame--) | คืนเฟรมข้อความของโหนด |
| [isAssistant()](#isAssistant--) | คืนค่า หรือ ตั้งค่าโหนดเป็นผู้ช่วย |
| [setAssistant(boolean value)](#setAssistant-boolean-) | คืนค่า หรือ ตั้งค่าโหนดเป็นผู้ช่วย |
| [getLevel()](#getLevel--) | คืนระดับการซ้อนของโหนด |
| [getBulletFillFormat()](#getBulletFillFormat--) | คืนอ็อบเจ็กต์ FillFormat ที่มีคุณลักษณะการจัดรูปแบบการเติมสำหรับหัวข้อย่อยของโหนด |
| [getPosition()](#getPosition--) | คืนค่า หรือ ตั้งค่าตำแหน่งเริ่มต้นจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง |
| [setPosition(int value)](#setPosition-int-) | คืนค่า หรือ ตั้งค่าตำแหน่งเริ่มต้นจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง |
| [isHidden()](#isHidden--) | คืนค่า true หากโหนดนี้เป็นโหนดที่ซ่อนอยู่ในโมเดลข้อมูล |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | คืนค่า หรือ ตั้งค่าชนิดการจัดวางแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | คืนค่า หรือ ตั้งค่าชนิดการจัดวางแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน |
| [remove()](#remove--) | ลบโหนดปัจจุบัน |

### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

คืนคอลเลกชันของโหนดลูกทั้งหมดของโหนดปัจจุบัน. อ่านอย่างเดียว [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**คืนค่า:**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

คืนคอลเลกชันของรูปร่างทั้งหมดที่เชื่อมโยงกับโหนด. อ่านอย่างเดียว [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**คืนค่า:**  
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

คืนเฟรมข้อความของโหนด. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**คืนค่า:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

คืนค่า หรือ ตั้งค่าโหนดเป็นผู้ช่วย. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

คืนค่า หรือ ตั้งค่าโหนดเป็นผู้ช่วย. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public final int getLevel()
```

คืนระดับการซ้อนของโหนด. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

คืนอ็อบเจ็กต์ FillFormat ที่มีคุณลักษณะการจัดรูปแบบการเติมสำหรับหัวข้อย่อยของโหนด. หมายเหตุ: สามารถคืนค่า null สำหรับประเภทของการจัดวาง SmartArt บางประเภทที่ไม่ให้หัวข้อย่อยสำหรับโหนด. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

คืนค่า หรือ ตั้งค่าตำแหน่งเริ่มต้นจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง. อ่าน/เขียน int.

**คืนค่า:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

คืนค่า หรือ ตั้งค่าตำแหน่งเริ่มต้นจากศูนย์ของโหนดในบรรดาโหนดพี่น้อง. อ่าน/เขียน int.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
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

คืนค่า หรือ ตั้งค่าชนิดการจัดวางแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน. อ่าน/เขียน [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**คืนค่า:**  
int

### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

คืนค่า หรือ ตั้งค่าชนิดการจัดวางแผนภูมิองค์กรที่เชื่อมโยงกับโหนดปัจจุบัน. อ่าน/เขียน [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public final boolean remove()
```

ลบโหนดปัจจุบัน.

**คืนค่า:**  
boolean - true หากลบสำเร็จ, มิฉะนั้น false