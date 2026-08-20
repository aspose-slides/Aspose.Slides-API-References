---
title: BaseSlideHeaderFooterManager
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวจัดการที่ควบคุมพฤติกรรมของตัวยึดส่วนท้าย วันที่-เวลา หมายเลขหน้า สำหรับทุกประเภทของสไลด์
type: docs
url: /th/com.aspose.slides/baseslideheaderfootermanager/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

เป็นผู้จัดการที่ทำหน้าที่ควบคุมการทำงานของตัวยึดส่วนท้าย, วันที่-เวลา, และหมายเลขหน้า สำหรับทุกประเภทของสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | รับค่าที่บ่งชี้ว่ามีตัวยึดส่วนท้ายอยู่ |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | รับค่าที่บ่งชี้ว่ามีตัวยึดหมายเลขหน้ามีอยู่ |
| [isDateTimeVisible()](#isDateTimeVisible--) | รับค่าที่บ่งชี้ว่ามีตัวยึดวันที่-เวลาอยู่ |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | เปลี่ยนการแสดงผลของตัวยึดส่วนท้ายของสไลด์ |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | เปลี่ยนการแสดงผลของตัวยึดหมายเลขหน้าของสไลด์ |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | เปลี่ยนการแสดงผลของตัวยึดวันที่-เวลาของสไลด์ |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | ตั้งค่าข้อความให้กับตัวยึดส่วนท้ายของสไลด์ |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | ตั้งค่าข้อความให้กับตัวยึดวันที่-เวลาของสไลด์ |
### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```


รับค่าที่บ่งชี้ว่ามีตัวยึดส่วนท้ายอยู่. อ่าน boolean.

**คืนค่า:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```


รับค่าที่บ่งชี้ว่ามีตัวยึดหมายเลขหน้ามีอยู่. อ่าน boolean.

**คืนค่า:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```


รับค่าที่บ่งชี้ว่ามีตัวยึดวันที่-เวลาอยู่. อ่าน boolean.

**คืนค่า:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```


เปลี่ยนการแสดงผลของตัวยึดส่วนท้ายของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดส่วนท้ายแสดง, มิฉะนั้น - ซ่อนมัน. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```


เปลี่ยนการแสดงผลของตัวยึดหมายเลขหน้าของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดหมายเลขหน้าแสดง, มิฉะนั้น - ซ่อนมัน. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```


เปลี่ยนการแสดงผลของตัวยึดวันที่-เวลาของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดวันที่-เวลาแสดง, มิฉะนั้น - ซ่อนมัน. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```


ตั้งค่าข้อความให้กับตัวยึดส่วนท้ายของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```


ตั้งค่าข้อความให้กับตัวยึดวันที่-เวลาของสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |