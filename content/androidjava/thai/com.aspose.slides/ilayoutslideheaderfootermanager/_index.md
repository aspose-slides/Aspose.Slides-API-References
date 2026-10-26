---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวจัดการที่ถือพฤติกรรมของ layout slide footer, date-time, page number placeholders และ child placeholders ทั้งหมด.
type: docs
url: /th/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Interfaces ที่ Implement ทั้งหมด:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

เป็นตัวจัดการที่ถือพฤติกรรมของ layout slide footer, date-time, page number placeholders และ child placeholders ทั้งหมด. Child placeholders หมายถึง placeholder ที่อยู่บนสไลด์ที่อ้างอิง. สไลด์ที่อ้างอิงใช้และพึ่งพา layout slide.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | เปลี่ยนการมองเห็น layout slide footer placeholder และ child footer placeholders ทั้งหมด. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | เปลี่ยนการมองเห็น layout slide page number placeholder และ child page number placeholders ทั้งหมด. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | เปลี่ยนการมองเห็น layout slide date-time placeholder และ child date-time placeholders ทั้งหมด. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | ตั้งค่า text ให้กับ layout slide footer placeholder และ child footer placeholders ทั้งหมด. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | ตั้งค่า text ให้กับ layout slide date-time placeholder และ child date-time placeholders ทั้งหมด. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็น layout slide footer placeholder และ child footer placeholders ทั้งหมด. Child placeholders หมายถึง placeholder ที่อยู่บนสไลด์ที่อ้างอิง. สไลด์ที่อ้างอิงใช้และพึ่งพา master slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ footer placeholders ปรากฏ, อย่างอื่น - ซ่อนมัน. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็น layout slide page number placeholder และ child page number placeholders ทั้งหมด. Child placeholders หมายถึง placeholder ที่อยู่บนสไลด์ที่อ้างอิง. สไลด์ที่อ้างอิงใช้และพึ่งพา layout slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ page number placeholders ปรากฏ, อย่างอื่น - ซ่อนมัน. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็น layout slide date-time placeholder และ child date-time placeholders ทั้งหมด. Child placeholders หมายถึง placeholder ที่อยู่บนสไลด์ที่อ้างอิง. สไลด์ที่อ้างอิงใช้และพึ่งพา layout slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ date-time placeholders ปรากฏ, อย่างอื่น - ซ่อนมัน. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

ตั้งค่า text ให้กับ layout slide footer placeholder และ child footer placeholders ทั้งหมด. Child placeholders หมายถึง placeholder ที่อยู่บนสไลด์ที่อ้างอิง. สไลด์ที่อ้างอิงใช้และพึ่งพา layout slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ตั้งค่า. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

ตั้งค่า text ให้กับ layout slide date-time placeholder และ child date-time placeholders ทั้งหมด. Child placeholders หมายถึง placeholder ที่อยู่บนสไลด์ที่อ้างอิง. สไลด์ที่อ้างอิงใช้และพึ่งพา layout slide.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่ตั้งค่า. |