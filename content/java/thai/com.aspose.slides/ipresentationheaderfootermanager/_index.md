---
title: IPresentationHeaderFooterManager
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวจัดการที่เก็บพฤติกรรมของส่วนตำแหน่งส่วนท้าย วันที่-เวลา และหมายเลขหน้าทั้งหมดของงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/ipresentationheaderfootermanager/
---
**ส่วนอินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

เป็นตัวจัดการที่เก็บพฤติกรรมของส่วนตำแหน่งส่วนท้าย, วันที่-เวลา และหมายเลขหน้า ทั้งหมดของงานนำเสนอ.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | เปลี่ยนการมองเห็นของส่วนตำแหน่งหัวเรื่องทั้งหมด รวมถึง notes master, notes slides และ handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | เปลี่ยนการมองเห็นของส่วนตำแหน่งส่วนท้ายทั้งหมด รวมถึง master slides, layout slides และ slides. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | เปลี่ยนการมองเห็นของส่วนตำแหน่งหมายเลขหน้าทั้งหมด รวมถึง master slides, layout slides และ slides. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | เปลี่ยนการมองเห็นของส่วนตำแหน่งวันที่-เวลาทั้งหมด รวมถึง master slides, layout slides และ slides. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | ตั้งค่าข้อความให้กับส่วนตำแหน่งหัวเรื่องทั้งหมด รวมถึง notes master, notes slides และ handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | ตั้งค่าข้อความให้กับส่วนตำแหน่งส่วนท้ายทั้งหมด รวมถึง master slides, layout slides และ slides. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | ตั้งค่าข้อความให้กับส่วนตำแหน่งวันที่-เวลาทั้งหมด รวมถึง master slides, layout slides และ slides. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | เปลี่ยนการมองเห็นของส่วนตำแหน่งส่วนท้าย, วันที่-เวลา และหมายเลขหน้า สำหรับสไลด์หัวเรื่องทั้งหมดและสไลด์เค้าโครงแรก. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของส่วนตำแหน่งหัวเรื่องทั้งหมด รวมถึง notes master, notes slides และ handout master.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ส่วนตำแหน่งหัวเรื่องแสดงผล, มิฉะนั้น - ซ่อน. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของส่วนตำแหน่งส่วนท้ายทั้งหมด รวมถึง master slides, layout slides และ slides.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ส่วนตำแหน่งส่วนท้ายแสดงผล, มิฉะนั้น - ซ่อน. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของส่วนตำแหน่งหมายเลขหน้าทั้งหมด รวมถึง master slides, layout slides และ slides.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ส่วนตำแหน่งหมายเลขหน้าแสดงผล, มิฉะนั้น - ซ่อน. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของส่วนตำแหน่งวันที่-เวลาทั้งหมด รวมถึง master slides, layout slides และ slides.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ส่วนตำแหน่งวันที่-เวลาแสดงผล, มิฉะนั้น - ซ่อน. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

ตั้งค่าข้อความให้กับส่วนตำแหน่งหัวเรื่องทั้งหมด รวมถึง notes master, notes slides และ handout master.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

ตั้งค่าข้อความให้กับส่วนตำแหน่งส่วนท้ายทั้งหมด รวมถึง master slides, layout slides และ slides.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

ตั้งค่าข้อความให้กับส่วนตำแหน่งวันที่-เวลาทั้งหมด รวมถึง master slides, layout slides และ slides.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

เปลี่ยนการมองเห็นของส่วนตำแหน่งส่วนท้าย, วันที่-เวลา และหมายเลขหน้า สำหรับสไลด์หัวเรื่องทั้งหมดและสไลด์เค้าโครงแรก. สไลด์หัวเรื่อง \\u2013 สไลด์ที่อิงจากสไลด์เค้าโครงแรก (โดยไม่คำนึงถึงประเภทของเค้าโครงแรกนี้).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตำแหน่งทั้งหมดแสดงผล, มิฉะนั้น - ซ่อน. |