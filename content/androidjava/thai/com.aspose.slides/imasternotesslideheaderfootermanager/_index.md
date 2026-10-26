---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นผู้จัดการที่ถือพฤติกรรมของส่วนท้ายสไลด์บันทึกหลัก วันที่-เวลา ตัวเลขหน้า ที่วางโครงร่างและที่วางโครงร่างย่อยทั้งหมด
type: docs
url: /th/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

เป็นผู้จัดการที่ถือพฤติกรรมของส่วนท้ายสไลด์บันทึกหลัก, วันที่-เวลา, ตัวเลขหน้าและส่วนย่อยทั้งหมด ส่วนย่อยหมายถึงที่วางโครงร่างที่อยู่บนสไลด์บันทึกที่อิง สไลด์บันทึกที่อิงใช้และพึ่งพาสไลด์บันทึกหลัก.
## Methods

| Method | Description |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | เปลี่ยนการมองเห็นของส่วนหัวสไลด์บันทึกหลักและส่วนหัวย่อยทั้งหมด |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | กำหนดข้อความให้กับส่วนหัวสไลด์บันทึกหลักและส่วนหัวย่อยทั้งหมด |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | เปลี่ยนการมองเห็นของส่วนท้ายสไลด์บันทึกหลักและส่วนท้ายย่อยทั้งหมด |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวเลขหน้าสไลด์บันทึกหลักและตัวเลขหน้าย่อยทั้งหมด |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | เปลี่ยนการมองเห็นของที่วางโครงร่างวันที่-เวลาในสไลด์บันทึกหลักและที่วางโครงร่างวันที่-เวลาในย่อยทั้งหมด |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | กำหนดข้อความให้กับส่วนท้ายสไลด์บันทึกหลักและส่วนท้ายย่อยทั้งหมด |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | กำหนดข้อความให้กับที่วางโครงร่างวันที่-เวลาในสไลด์บันทึกหลักและที่วางโครงร่างวันที่-เวลาในย่อยทั้งหมด |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของส่วนหัวสไลด์บันทึกหลักและส่วนหัวย่อยทั้งหมด ส่วนย่อยหมายถึงที่วางโครงร่างที่อยู่บนสไลด์บันทึกที่อิง สไลด์บันทึกที่อิงใช้และพึ่งพาสไลด์บันทึกหลัก.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ส่วนหัวของที่วางโครงร่างแสดงผล, มิฉะนั้น - ซ่อนมัน. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

กำหนดข้อความให้กับส่วนหัวสไลด์บันทึกหลักและส่วนหัวย่อยทั้งหมด ส่วนย่อยหมายถึงที่วางโครงร่างที่อยู่บนสไลด์บันทึกที่อิง สไลด์บันทึกที่อิงใช้และพึ่งพาสไลด์บันทึกหลัก.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ตั้งค่า. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของส่วนท้ายสไลด์บันทึกหลักและส่วนท้ายย่อยทั้งหมด ส่วนย่อยหมายถึงที่วางโครงร่างที่อยู่บนสไลด์บันทึกที่อิง สไลด์บันทึกที่อิงใช้และพึ่งพาสไลด์บันทึกหลัก.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ส่วนท้ายของที่วางโครงร่างแสดงผล, มิฉะนั้น - ซ่อนมัน. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวเลขหน้าสไลด์บันทึกหลักและตัวเลขหน้าย่อยทั้งหมด ส่วนย่อยหมายถึงที่วางโครงร่างที่อยู่บนสไลด์บันทึกที่อิง สไลด์บันทึกที่อิงใช้และพึ่งพาสไลด์บันทึกหลัก.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวเลขหน้าของที่วางโครงร่างแสดงผล, มิฉะนั้น - ซ่อนมัน. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของที่วางโครงร่างวันที่-เวลาในสไลด์บันทึกหลักและที่วางโครงร่างวันที่-เวลาในย่อยทั้งหมด ส่วนย่อยหมายถึงที่วางโครงร่างที่อยู่บนสไลด์บันทึกที่อิง สไลด์บันทึกที่อิงใช้และพึ่งพาสไลด์บันทึกหลัก.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้วันที่-เวลาในที่วางโครงร่างแสดงผล, มิฉะนั้น - ซ่อนมัน. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

กำหนดข้อความให้กับส่วนท้ายสไลด์บันทึกหลักและส่วนท้ายย่อยทั้งหมด ส่วนย่อยหมายถึงที่วางโครงร่างที่อยู่บนสไลด์บันทึกที่อิง สไลด์บันทึกที่อิงใช้และพึ่งพาสไลด์บันทึกหลัก.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ตั้งค่า. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

กำหนดข้อความให้กับที่วางโครงร่างวันที่-เวลาในสไลด์บันทึกหลักและที่วางโครงร่างวันที่-เวลาในย่อยทั้งหมด ส่วนย่อยหมายถึงที่วางโครงร่างที่อยู่บนสไลด์บันทึกที่อิง สไลด์บันทึกที่อิงใช้และพึ่งพาสไลด์บันทึกหลัก.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ตั้งค่า. |