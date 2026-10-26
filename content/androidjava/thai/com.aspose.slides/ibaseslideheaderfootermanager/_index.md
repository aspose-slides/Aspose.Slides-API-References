---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวจัดการที่ถือพฤติกรรมของส่วนแทนส่วนท้าย วันที่-เวลา และหมายเลขหน้า สำหรับสไลด์ทุกประเภท.
type: docs
url: /th/com.aspose.slides/ibaseslideheaderfootermanager/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

เป็นผู้จัดการที่ถือพฤติกรรมของส่วนที่เป็นตัวยึดของส่วนท้าย, วันที่-เวลา, ตัวเลขหน้าสำหรับสไลด์ทุกประเภท.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | รับค่าที่บ่งชี้ว่ามีส่วนที่เป็นตัวยึดของส่วนท้าย. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | รับค่าที่บ่งชี้ว่ามีส่วนที่เป็นตัวยึดของตัวเลขหน้า. |
| [isDateTimeVisible()](#isDateTimeVisible--) | รับค่าที่บ่งชี้ว่ามีส่วนที่เป็นตัวยึดของวันที่-เวลา. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | เปลี่ยนความมองเห็นของส่วนที่เป็นตัวยึดของส่วนท้ายสไลด์. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | เปลี่ยนความมองเห็นของส่วนที่เป็นตัวยึดของตัวเลขหน้าสไลด์. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | เปลี่ยนความมองเห็นของส่วนที่เป็นตัวยึดของวันที่-เวลาในสไลด์. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | ตั้งค่าข้อความให้กับส่วนที่เป็นตัวยึดของส่วนท้ายสไลด์. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | ตั้งค่าข้อความให้กับส่วนที่เป็นตัวยึดของวันที่-เวลาในสไลด์. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


รับค่าที่บ่งชี้ว่ามีส่วนที่เป็นตัวยึดของส่วนท้าย. อ่านเป็นบูลีน.

**คืนค่า:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


รับค่าที่บ่งชี้ว่ามีส่วนที่เป็นตัวยึดของตัวเลขหน้า. อ่านเป็นบูลีน.

**คืนค่า:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


รับค่าที่บ่งชี้ว่ามีส่วนที่เป็นตัวยึดของวันที่-เวลา. อ่านเป็นบูลีน.

**คืนค่า:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```


เปลี่ยนความมองเห็นของส่วนที่เป็นตัวยึดของส่วนท้ายสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ส่วนที่เป็นตัวยึดของส่วนท้ายแสดง, มิฉะนั้น - ซ่อนมัน. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```


เปลี่ยนความมองเห็นของส่วนที่เป็นตัวยึดของตัวเลขหน้าสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ส่วนที่เป็นตัวยึดของตัวเลขหน้าแสดง, มิฉะนั้น - ซ่อนมัน. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```


เปลี่ยนความมองเห็นของส่วนที่เป็นตัวยึดของวันที่-เวลาในสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ส่วนที่เป็นตัวยึดของวันที่-เวลาแสดง, มิฉะนั้น - ซ่อนมัน. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```


ตั้งค่าข้อความให้กับส่วนที่เป็นตัวยึดของส่วนท้ายสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```


ตั้งค่าข้อความให้กับส่วนที่เป็นตัวยึดของวันที่-เวลาในสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |