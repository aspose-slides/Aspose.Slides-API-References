---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: แสดงถึงผู้จัดการที่ควบคุมพฤติกรรมของส่วนท้ายของ master notes slide ตัวอธิบายวัน-เวลา หมายเลขหน้า และพื้นที่เก็บส่วนย่อยทั้งหมด.
type: docs
url: /th/com.aspose.slides/masternotesslideheaderfootermanager/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

แสดงถึงผู้จัดการที่ควบคุมพฤติกรรมของส่วนท้ายของสไลด์ master notes, ตัวอธิบายเวลา-วันที่, หมายเลขหน้าและพื้นที่เก็บส่วนย่อยทั้งหมด ส่วนเก็บส่วนย่อยหมายถึงพื้นที่เก็บที่อยู่บนสไลด์บันทึกที่ขึ้นอยู่ สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพา master notes slide.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | เปลี่ยนการมองเห็นของพื้นที่เก็บส่วนหัวของ master notes slide และพื้นที่เก็บส่วนหัวของลูกทั้งหมด |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | ตั้งค่าข้อความให้กับพื้นที่เก็บส่วนหัวของ master notes slide และพื้นที่เก็บส่วนหัวของลูกทั้งหมด |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | เปลี่ยนการมองเห็นของพื้นที่เก็บส่วนท้ายของ master slide และพื้นที่เก็บส่วนท้ายของลูกทั้งหมด |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | เปลี่ยนการมองเห็นของพื้นที่เก็บหมายเลขหน้าของ master slide และพื้นที่เก็บหมายเลขหน้าของลูกทั้งหมด |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | เปลี่ยนการมองเห็นของพื้นที่เก็บตัวอธิบายเวลา-วันที่ของ master slide และพื้นที่เก็บตัวอธิบายเวลา-วันที่ของลูกทั้งหมด |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | ตั้งค่าข้อความให้กับพื้นที่เก็บส่วนท้ายของ master slide และพื้นที่เก็บส่วนท้ายของลูกทั้งหมด |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | ตั้งค่าข้อความให้กับพื้นที่เก็บตัวอธิบายเวลา-วันที่ของ master slide และพื้นที่เก็บตัวอธิบายเวลา-วันที่ของลูกทั้งหมด |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```


เปลี่ยนการมองเห็นของพื้นที่เก็บส่วนหัวของ master notes slide และพื้นที่เก็บส่วนหัวของลูกทั้งหมด พื้นที่เก็บส่วนหัวของลูกหมายถึงพื้นที่เก็บที่อยู่บนสไลด์บันทึกที่ขึ้นอยู่ สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพา master notes slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้พื้นที่เก็บส่วนหัวแสดงผล, มิฉะนั้น - ซ่อนลง |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```


ตั้งค่าข้อความให้กับพื้นที่เก็บส่วนหัวของ master notes slide และพื้นที่เก็บส่วนหัวของลูกทั้งหมด พื้นที่เก็บส่วนหัวของลูกหมายถึงพื้นที่เก็บที่อยู่บนสไลด์บันทึกที่ขึ้นอยู่ สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพา master notes slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```


เปลี่ยนการมองเห็นของพื้นที่เก็บส่วนท้ายของ master slide และพื้นที่เก็บส่วนท้ายของลูกทั้งหมด พื้นที่เก็บส่วนท้ายของลูกหมายถึงพื้นที่เก็บที่อยู่บนสไลด์บันทึกที่ขึ้นอยู่ สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพา master notes slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้พื้นที่เก็บส่วนท้ายแสดงผล, มิฉะนั้น - ซ่อนลง |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


เปลี่ยนการมองเห็นของพื้นที่เก็บหมายเลขหน้าของ master slide และพื้นที่เก็บหมายเลขหน้าของลูกทั้งหมด พื้นที่เก็บหมายเลขหน้าของลูกหมายถึงพื้นที่เก็บที่อยู่บนสไลด์บันทึกที่ขึ้นอยู่ สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพา master notes slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้พื้นที่เก็บหมายเลขหน้าแสดงผล, มิฉะนั้น - ซ่อนลง |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


เปลี่ยนการมองเห็นของพื้นที่เก็บตัวอธิบายเวลา-วันที่ของ master slide และพื้นที่เก็บตัวอธิบายเวลา-วันที่ของลูกทั้งหมด พื้นที่เก็บตัวอธิบายเวลา-วันที่ของลูกหมายถึงพื้นที่เก็บที่อยู่บนสไลด์บันทึกที่ขึ้นอยู่ สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพา master notes slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้พื้นที่เก็บตัวอธิบายเวลา-วันที่แสดงผล, มิฉะนั้น - ซ่อนลง |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```


ตั้งค่าข้อความให้กับพื้นที่เก็บส่วนท้ายของ master slide และพื้นที่เก็บส่วนท้ายของลูกทั้งหมด พื้นที่เก็บส่วนท้ายของลูกหมายถึงพื้นที่เก็บที่อยู่บนสไลด์บันทึกที่ขึ้นอยู่ สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพา master notes slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```


ตั้งค่าข้อความให้กับพื้นที่เก็บตัวอธิบายเวลา-วันที่ของ master slide และพื้นที่เก็บตัวอธิบายเวลา-วันที่ของลูกทั้งหมด พื้นที่เก็บตัวอธิบายเวลา-วันที่ของลูกหมายถึงพื้นที่เก็บที่อยู่บนสไลด์บันทึกที่ขึ้นอยู่ สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพา master notes slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า |