---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แสดงถึงผู้จัดการที่ดูแลพฤติกรรมของส่วนท้ายสไลด์หลัก, วันที่-เวลา, ตัวพักหมายเลขหน้า และตัวพักลูกทั้งหมด.
type: docs
url: /th/com.aspose.slides/masterslideheaderfootermanager/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

แสดงถึงผู้จัดการที่ดูแลพฤติกรรมของตัวพักส่วนท้ายสไลด์หลัก, วันที่-เวลา, ตัวพักหมายเลขหน้า และตัวพักลูกทั้งหมด. ตัวพักลูกหมายถึงตัวพักที่อยู่บนสไลด์เลย์เอาต์ที่พึ่งพาและสไลด์ที่พึ่งพา. สไลด์เลย์เอตและสไลด์ใช้และขึ้นกับสไลด์หลัก.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวพักส่วนท้ายสไลด์หลักและตัวพักส่วนท้ายลูกทั้งหมด. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวพักหมายเลขหน้าสไลด์หลักและตัวพักหมายเลขหน้าลูกทั้งหมด. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวพักวันที่-เวลาในสไลด์หลักและตัวพักวันที่-เวลาในสไลด์ลูกทั้งหมด. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | ตั้งค่าข้อความให้กับตัวพักส่วนท้ายสไลด์หลักและตัวพักส่วนท้ายลูกทั้งหมด. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | ตั้งค่าข้อความให้กับตัวพักวันที่-เวลาในสไลด์หลักและตัวพักวันที่-เวลาในสไลด์ลูกทั้งหมด. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวพักส่วนท้ายสไลด์หลักและตัวพักส่วนท้ายลูกทั้งหมด. ตัวพักลูกหมายถึงตัวพักที่อยู่บนสไลด์เลย์เอาต์ที่พึ่งพาและสไลด์ที่พึ่งพา. สไลด์เลย์เอตและสไลด์ใช้และขึ้นกับสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวพักส่วนท้ายแสดงผล, มิฉะนั้น - ซ่อนตัวพัก. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวพักหมายเลขหน้าสไลด์หลักและตัวพักหมายเลขหน้าลูกทั้งหมด. ตัวพักลูกหมายถึงตัวพักที่อยู่บนสไลด์เลย์เอาต์ที่พึ่งพาและสไลด์ที่พึ่งพา. สไลด์เลย์เอตและสไลด์ใช้และขึ้นกับสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวพักหมายเลขหน้าแสดงผล, มิฉะนั้น - ซ่อนตัวพัก. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวพักวันที่-เวลาในสไลด์หลักและตัวพักวันที่-เวลาในสไลด์ลูกทั้งหมด. ตัวพักลูกหมายถึงตัวพักที่อยู่บนสไลด์เลย์เอาต์ที่พึ่งพาและสไลด์ที่พึ่งพา. สไลด์เลย์เอตและสไลด์ใช้และขึ้นกับสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวพักวันที่-เวลาแสดงผล, มิฉะนั้น - ซ่อนตัวพัก. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

ตั้งค่าข้อความให้กับตัวพักส่วนท้ายสไลด์หลักและตัวพักส่วนท้ายลูกทั้งหมด. ตัวพักลูกหมายถึงตัวพักที่อยู่บนสไลด์เลย์เอาต์ที่พึ่งพาและสไลด์ที่พึ่งพา. สไลด์เลย์เอตและสไลด์ใช้และขึ้นกับสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

ตั้งค่าข้อความให้กับตัวพักวันที่-เวลาในสไลด์หลักและตัวพักวันที่-เวลาในสไลด์ลูกทั้งหมด. ตัวพักลูกหมายถึงตัวพักที่อยู่บนสไลด์เลย์เอาต์ที่พึ่งพาและสไลด์ที่พึ่งพา. สไลด์เลย์เอตและสไลด์ใช้และขึ้นกับสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |