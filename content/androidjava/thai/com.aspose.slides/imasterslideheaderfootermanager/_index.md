---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวจัดการที่ควบคุมพฤติกรรมของ placeholder ส่วนท้ายสไลด์หลัก, วันที่และเวลา, หมายเลขหน้า และ placeholder ลูกทั้งหมด.
type: docs
url: /th/com.aspose.slides/imasterslideheaderfootermanager/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

เป็นตัวจัดการที่ควบคุมพฤติกรรมของ placeholder ส่วนท้ายสไลด์หลัก, date-time, page number และ placeholder ลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่ถูกบรรจุอยู่บนสไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | เปลี่ยนการมองเห็นของ placeholder ส่วนท้ายสไลด์หลักและ placeholder ส่วนท้ายลูกทั้งหมด. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | เปลี่ยนการมองเห็นของ placeholder หมายเลขหน้าสไลด์หลักและ placeholder หมายเลขหน้าลูกทั้งหมด. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | เปลี่ยนการมองเห็นของ placeholder วันที่และเวลาของสไลด์หลักและ placeholder วันที่และเวลาลูกทั้งหมด. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | ตั้งค่าข้อความให้กับ placeholder ส่วนท้ายสไลด์หลักและ placeholder ส่วนท้ายลูกทั้งหมด. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | ตั้งค่าข้อความให้กับ placeholder วันที่และเวลาของสไลด์หลักและ placeholder วันที่และเวลาลูกทั้งหมด. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของ placeholder ส่วนท้ายสไลด์หลักและ placeholder ส่วนท้ายลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่ถูกบรรจุอยู่บนสไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ placeholder ส่วนท้ายแสดง, มิฉะนั้น - ซ่อนมัน. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของ placeholder หมายเลขหน้าสไลด์หลักและ placeholder หมายเลขหน้าลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่ถูกบรรจุอยู่บนสไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ placeholder หมายเลขหน้าตัวแสดง, มิฉะนั้น - ซ่อนมัน. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของ placeholder วันที่และเวลาของสไลด์หลักและ placeholder วันที่และเวลาลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่ถูกบรรจุอยู่บนสไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ placeholder วันที่และเวลาแสดง, มิฉะนั้น - ซ่อนมัน. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

ตั้งค่าข้อความให้กับ placeholder ส่วนท้ายสไลด์หลักและ placeholder ส่วนท้ายลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่ถูกบรรจุอยู่บนสไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

ตั้งค่าข้อความให้กับ placeholder วันที่และเวลาของสไลด์หลักและ placeholder วันที่และเวลาลูกทั้งหมด. placeholder ลูกหมายถึง placeholder ที่ถูกบรรจุอยู่บนสไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เลย์เอาต์ที่ขึ้นกับและสไลด์เหล่านั้นใช้และพึ่งพาสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |