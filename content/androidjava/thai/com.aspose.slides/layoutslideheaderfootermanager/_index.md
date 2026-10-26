---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นผู้จัดการที่ถือพฤติกรรมของส่วนท้ายสไลด์เค้าโครง ตัวกำหนดตำแหน่งวันที่-เวลาและหมายเลขหน้า รวมถึงตัวกำหนดตำแหน่งลูกทั้งหมด
type: docs
url: /th/com.aspose.slides/layoutslideheaderfootermanager/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**ทุกอินเทอร์เฟสที่นำไปใช้:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Represents manager which holds behavior of the layout slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on layout slide.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวแทนส่วนท้ายสไลด์เค้าโครงและตัวแทนส่วนท้ายของลูกทั้งหมด. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวแทนหมายเลขหน้าสไลด์เค้าโครงและตัวแทนหมายเลขหน้าของลูกทั้งหมด. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวแทนวันที่-เวลาในสไลด์เค้าโครงและตัวแทนวันที่-เวลาในลูกทั้งหมด. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | ตั้งค่าข้อความให้กับตัวแทนส่วนท้ายสไลด์เค้าโครงและตัวแทนส่วนท้ายของลูกทั้งหมด. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | ตั้งค่าข้อความให้กับตัวแทนวันที่-เวลาในสไลด์เค้าโครงและตัวแทนวันที่-เวลาในลูกทั้งหมด. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวแทนส่วนท้ายสไลด์เค้าโครงและตัวแทนส่วนท้ายของลูกทั้งหมด. ตัวแทนส่วนท้ายของลูกหมายถึงตัวแทนที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และพึ่งพาสไลด์แม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวแทนส่วนท้ายมองเห็นได้, มิฉะนั้น - จะทำให้มองไม่เห็น. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวแทนหมายเลขหน้าสไลด์เค้าโครงและตัวแทนหมายเลขหน้าของลูกทั้งหมด. ตัวแทนหมายเลขหน้าของลูกหมายถึงตัวแทนที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และพึ่งพาสไลด์เค้าโครง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวแทนหมายเลขหน้ามองเห็นได้, มิฉะนั้น - จะทำให้มองไม่เห็น. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวแทนวันที่-เวลาในสไลด์เค้าโครงและตัวแทนวันที่-เวลาในลูกทั้งหมด. ตัวแทนวันที่-เวลาในลูกหมายถึงตัวแทนที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และพึ่งพาสไลด์เค้าโครง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวแทนวันที่-เวลามองเห็นได้, มิฉะนั้น - จะทำให้มองไม่เห็น. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

ตั้งค่าข้อความให้กับตัวแทนส่วนท้ายสไลด์เค้าโครงและตัวแทนส่วนท้ายของลูกทั้งหมด. ตัวแทนส่วนท้ายของลูกหมายถึงตัวแทนที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และพึ่งพาสไลด์เค้าโครง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

ตั้งค่าข้อความให้กับตัวแทนวันที่-เวลาในสไลด์เค้าโครงและตัวแทนวันที่-เวลาในลูกทั้งหมด. ตัวแทนวันที่-เวลาในลูกหมายถึงตัวแทนที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และพึ่งพาสไลด์เค้าโครง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |