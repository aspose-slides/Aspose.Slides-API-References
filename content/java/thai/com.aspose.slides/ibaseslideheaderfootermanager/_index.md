---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงผู้จัดการที่บรรจุพฤติกรรมของตัวยึดส่วนท้าย วันที่-เวลา หมายเลขหน้า สำหรับสไลด์ทุกประเภท.
type: docs
url: /th/com.aspose.slides/ibaseslideheaderfootermanager/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

แสดงผู้จัดการที่บรรจุพฤติกรรมของตัวยึดส่วนท้าย, วันที่-เวลา, และหมายเลขหน้า สำหรับสไลด์ทุกประเภท.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | รับค่าที่บ่งชี้ว่าตัวยึดส่วนท้ายปรากฏอยู่ |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | รับค่าที่บ่งชี้ว่าตัวยึดหมายเลขหน้าปรากฏอยู่ |
| [isDateTimeVisible()](#isDateTimeVisible--) | รับค่าที่บ่งชี้ว่าตัวยึดวันที่-เวลา ปรากฏอยู่ |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวยึดส่วนท้ายของสไลด์ |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวยึดหมายเลขหน้าของสไลด์ |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวยึดวันที่-เวลาของสไลด์ |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | ตั้งค่าข้อความให้กับตัวยึดส่วนท้ายของสไลด์ |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | ตั้งค่าข้อความให้กับตัวยึดวันที่-เวลของสไลด์ |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


รับค่าที่บ่งชี้ว่าตัวยึดส่วนท้ายปรากฏอยู่ อ่านค่า boolean.

**คืนค่า:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


รับค่าที่บ่งชี้ว่าตัวยึดหมายเลขหน้าปรากฏอยู่ อ่านค่า boolean.

**คืนค่า:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


รับค่าที่บ่งชี้ว่าตัวยึดวันที่-เวลา ปรากฏอยู่ อ่านค่า boolean.

**คืนค่า:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```


เปลี่ยนการมองเห็นของตัวยึดส่วนท้ายของสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดส่วนท้ายมองเห็นได้, มิฉะนั้น - ซ่อนตัวยึดส่วนท้าย. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```


เปลี่ยนการมองเห็นของตัวยึดหมายเลขหน้าของสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดหมายเลขหน้ามองเห็นได้, มิฉะนั้น - ซ่อนตัวยึดหมายเลขหน้า. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```


เปลี่ยนการมองเห็นของตัวยึดวันที่-เวลาของสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดวันที่-เวลา มองเห็นได้, มิฉะนั้น - ซ่อนตัวยึดวันที่-เวลา. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```


ตั้งค่าข้อความให้กับตัวยึดส่วนท้ายของสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```


ตั้งค่าข้อความให้กับตัวยึดวันที่-เวลาของสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |