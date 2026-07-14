---
title: BaseSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: เป็นผู้จัดการที่เก็บพฤติกรรมของตัวยึดส่วนท้าย, วันที่-เวลา, และหมายเลขหน้าสำหรับสไลด์ทุกประเภท.
type: docs
url: /th/com.aspose.slides/baseslideheaderfootermanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

เป็นผู้จัดการที่เก็บพฤติกรรมของตัวยึดส่วนท้าย, ตัวยึดวันที่-เวลา, และตัวยึดหมายเลขหน้าสำหรับสไลด์ทุกประเภท.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | รับค่าที่บ่งบอกว่ามีตัวยึดส่วนท้ายอยู่. อ่านเป็น boolean. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | รับค่าที่บ่งบอกว่ามีตัวยึดหมายเลขหน้าอยู่. อ่านเป็น boolean. |
| [isDateTimeVisible()](#isDateTimeVisible--) | รับค่าที่บ่งบอกว่ามีตัวยึดวันที่-เวลาอยู่. อ่านเป็น boolean. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวยึดส่วนท้ายสไลด์. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวยึดหมายเลขหน้าสไลด์. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวยึดวันที่-เวลาในสไลด์. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | กำหนดข้อความให้กับตัวยึดส่วนท้ายสไลด์. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | กำหนดข้อความให้กับตัวยึดวันที่-เวลาในสไลด์. |
### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

รับค่าที่บ่งบอกว่ามีตัวยึดส่วนท้ายอยู่. อ่านเป็น boolean.

**คืนค่า:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

รับค่าที่บ่งบอกว่ามีตัวยึดหมายเลขหน้าอยู่. อ่านเป็น boolean.

**คืนค่า:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

รับค่าที่บ่งบอกว่ามีตัวยึดวันที่-เวลาอยู่. อ่านเป็น boolean.

**คืนค่า:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวยึดส่วนท้ายสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดส่วนท้ายปรากฏ, otherwise - ซ่อนมัน. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวยึดหมายเลขหน้าสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดหมายเลขหน้าปรากฏ, otherwise - ซ่อนมัน. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวยึดวันที่-เวลาในสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดวันที่-เวลาปรากฏ, otherwise - ซ่อนมัน. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

กำหนดข้อความให้กับตัวยึดส่วนท้ายสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

กำหนดข้อความให้กับตัวยึดวันที่-เวลาในสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |