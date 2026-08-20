---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงผู้จัดการที่เก็บพฤติกรรมของตัวย่อตัวอย่างส่วนท้ายของเลเอาต์สไลด์ วันที่-เวลา หมายเลขหน้าและตัวย่อตัวอย่างลูกทั้งหมด.
type: docs
url: /th/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

แสดงผู้จัดการที่เก็บพฤติกรรมของตัวย่อตัวอย่างส่วนท้ายของเลเอาต์สไลด์, วันที่-เวลา, ตัวเลขหน้าของเลเอาต์สไลด์และตัวย่อตัวอย่างลูกทั้งหมด. ตัวย่อตัวอย่างลูกหมายถึงตัวย่อตัวอย่างที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และพึ่งพาเลเอาต์สไลด์.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวย่อตัวอย่างส่วนท้ายของเลเอาต์สไลด์และตัวย่อตัวอย่างส่วนท้ายลูกทั้งหมด. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวย่อตัวอย่างหมายเลขหน้าของเลเอาต์สไลด์และตัวย่อตัวอย่างหมายเลขหน้าลูกทั้งหมด. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวย่อตัวอย่างวันที่-เวลาในเลเอาต์สไลด์และตัวย่อตัวอย่างวันที่-เวลาเด็กทั้งหมด. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | ตั้งข้อความให้กับตัวย่อตัวอย่างส่วนท้ายของเลเอาต์สไลด์และตัวย่อตัวอย่างส่วนท้ายลูกทั้งหมด. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | ตั้งข้อความให้กับตัวย่อตัวอย่างวันที่-เวลาในเลเอาต์สไลด์และตัวย่อตัวอย่างวันที่-เวลาเด็กทั้งหมด. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวย่อตัวอย่างส่วนท้ายของเลเอาต์สไลด์และตัวย่อตัวอย่างส่วนท้ายลูกทั้งหมด. ตัวย่อตัวอย่างลูกหมายถึงตัวย่อตัวอย่างที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และพึ่งพาแม่สไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวย่อตัวอย่างส่วนท้ายมองเห็นได้, มิฉะนั้น - ซ่อนมัน. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวย่อตัวอย่างหมายเลขหน้าของเลเอาต์สไลด์และตัวย่อตัวอย่างหมายเลขหน้าลูกทั้งหมด. ตัวย่อตัวอย่างลูกหมายถึงตัวย่อตัวอย่างที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และพึ่งพาเลเอาต์สไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวย่อตัวอย่างหมายเลขหน้ามองเห็นได้, มิฉะนั้น - ซ่อนมัน. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวย่อตัวอย่างวันที่-เวลาในเลเอาต์สไลด์และตัวย่อตัวอย่างวันที่-เวลาเด็กทั้งหมด. ตัวย่อตัวอย่างลูกหมายถึงตัวย่อตัวอย่างที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และพึ่งพาเลเอาต์สไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวย่อตัวอย่างวันที่-เวลามองเห็นได้, มิฉะนั้น - ซ่อนมัน. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

ตั้งข้อความให้กับตัวย่อตัวอย่างส่วนท้ายของเลเอาต์สไลด์และตัวย่อตัวอย่างส่วนท้ายลูกทั้งหมด. ตัวย่อตัวอย่างลูกหมายถึงตัวย่อตัวอย่างที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และพึ่งพาเลเอาต์สไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้ง. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

ตั้งข้อความให้กับตัวย่อตัวอย่างวันที่-เวลาในเลเอาต์สไลด์และตัวย่อตัวอย่างวันที่-เวลาเด็กทั้งหมด. ตัวย่อตัวอย่างลูกหมายถึงตัวย่อตัวอย่างที่อยู่ในสไลด์ที่ขึ้นอยู่. สไลด์ที่ขึ้นอยู่ใช้และพึ่งพาเลเอาต์สไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้ง. |