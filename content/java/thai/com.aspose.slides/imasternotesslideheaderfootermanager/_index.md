---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงผู้จัดการที่ถือพฤติกรรมของ placeholder ส่วนท้ายสไลด์บันทึกหลัก, placeholder ตัวจับเวลาสถานที่, placeholder ตัวเลขหน้า และ placeholder ลูกทั้งหมด.
type: docs
url: /th/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

แสดงถึงผู้จัดการที่ถือพฤติกรรมของส่วนท้ายสไลด์บันทึกหลัก, ตัวจับเวลาสถานที่, ตัวเลขหน้า placeholder และ placeholder ลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่อยู่บนสไลด์บันทึกที่ขึ้นกับมัน. สไลด์บันทึกที่ขึ้นกับนั้นใช้และพึ่งพาสไลด์บันทึกหลัก.
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | เปลี่ยนการมองเห็นของ placeholder ส่วนหัวสไลด์บันทึกหลักและ placeholder ส่วนหัวลูกทั้งหมด. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | กำหนดข้อความให้กับ placeholder ส่วนหัวสไลด์บันทึกหลักและ placeholder ส่วนหัวลูกทั้งหมด. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | เปลี่ยนการมองเห็นของ placeholder ส่วนท้ายสไลด์บันทึกหลักและ placeholder ส่วนท้ายลูกทั้งหมด. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | เปลี่ยนการมองเห็นของ placeholder ตัวเลขหน้าสไลด์บันทึกหลักและ placeholder ตัวเลขหน้าลูกทั้งหมด. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | เปลี่ยนการมองเห็นของ placeholder ตัวจับเวลาสถานที่สไลด์บันทึกหลักและ placeholder ตัวจับเวลาลูกทั้งหมด. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | กำหนดข้อความให้กับ placeholder ส่วนท้ายสไลด์บันทึกหลักและ placeholder ส่วนท้ายลูกทั้งหมด. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | กำหนดข้อความให้กับ placeholder ตัวจับเวลาสถานที่สไลด์บันทึกหลักและ placeholder ตัวจับเวลาลูกทั้งหมด. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของ placeholder ส่วนหัวสไลด์บันทึกหลักและ placeholder ส่วนหัวลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่อยู่บนสไลด์บันทึกที่ขึ้นกับมัน. สไลด์บันทึกที่ขึ้นกับนั้นใช้และพึ่งพาสไลด์บันทึกหลัก.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ placeholder ส่วนหัวแสดงผล, false - ซ่อนไว้. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

กำหนดข้อความให้กับ placeholder ส่วนหัวสไลด์บันทึกหลักและ placeholder ส่วนหัวลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่อยู่บนสไลด์บันทึกที่ขึ้นกับมัน. สไลด์บันทึกที่ขึ้นกับนั้นใช้และพึ่งพาสไลด์บันทึกหลัก.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของ placeholder ส่วนท้ายสไลด์บันทึกหลักและ placeholder ส่วนท้ายลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่อยู่บนสไลด์บันทึกที่ขึ้นกับมัน. สไลด์บันทึกที่ขึ้นกับนั้นใช้และพึ่งพาสไลด์บันทึกหลัก.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ placeholder ส่วนท้ายแสดงผล, false - ซ่อนไว้. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของ placeholder ตัวเลขหน้าสไลด์บันทึกหลักและ placeholder ตัวเลขหน้าลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่อยู่บนสไลด์บันทึกที่ขึ้นกับมัน. สไลด์บันทึกที่ขึ้นกับนั้นใช้และพึ่งพาสไลด์บันทึกหลัก.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ placeholder ตัวเลขหน้าแสดงผล, false - ซ่อนไว้. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของ placeholder ตัวจับเวลาสถานที่สไลด์บันทึกหลักและ placeholder ตัวจับเวลาลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่อยู่บนสไลด์บันทึกที่ขึ้นกับมัน. สไลด์บันทึกที่ขึ้นกับนั้นใช้และพึ่งพาสไลด์บันทึกหลัก.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ placeholder ตัวจับเวลาสถานที่แสดงผล, false - ซ่อนไว้. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

กำหนดข้อความให้กับ placeholder ส่วนท้ายสไลด์บันทึกหลักและ placeholder ส่วนท้ายลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่อยู่บนสไลด์บันทึกที่ขึ้นกับมัน. สไลด์บันทึกที่ขึ้นกับนั้นใช้และพึ่งพาสไลด์บันทึกหลัก.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

กำหนดข้อความให้กับ placeholder ตัวจับเวลาสถานที่สไลด์บันทึกหลักและ placeholder ตัวจับเวลาลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่อยู่บนสไลด์บันทึกที่ขึ้นกับมัน. สไลด์บันทึกที่ขึ้นกับนั้นใช้และพึ่งพาสไลด์บันทึกหลัก.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |