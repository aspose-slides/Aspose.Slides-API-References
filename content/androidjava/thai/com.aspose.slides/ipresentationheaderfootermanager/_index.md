---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวจัดการที่ถือพฤติกรรมของตำแหน่งที่เก็บข้อมูลส่วนท้าย, วันที่-เวลา และหมายเลขหน้าทั้งหมดของการนำเสนอ
type: docs
url: /th/com.aspose.slides/ipresentationheaderfootermanager/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

เป็นตัวจัดการที่ถือพฤติกรรมของตำแหน่งที่เก็บข้อมูลส่วนท้าย, วันที่-เวลา และหมายเลขหน้า ของการนำเสนอทั้งหมด.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | เปลี่ยนการมองเห็นของตำแหน่งที่เก็บข้อมูลส่วนหัวทั้งหมด รวมถึง notes master, notes slides และ handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | เปลี่ยนการมองเห็นของตำแหน่งที่เก็บข้อมูลส่วนท้ายทั้งหมด รวมถึง master slides, layout slides และ slides. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | เปลี่ยนการมองเห็นของตำแหน่งที่เก็บข้อมูลหมายเลขหน้าทั้งหมด รวมถึง master slides, layout slides และ slides. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | เปลี่ยนการมองเห็นของตำแหน่งที่เก็บข้อมูลวันที่-เวลาทั้งหมด รวมถึง master slides, layout slides และ slides. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | ตั้งข้อความให้กับตำแหน่งที่เก็บข้อมูลส่วนหัวทั้งหมด รวมถึง notes master, notes slides และ handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | ตั้งข้อความให้กับตำแหน่งที่เก็บข้อมูลส่วนท้ายทั้งหมด รวมถึง master slides, layout slides และ slides. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | ตั้งข้อความให้กับตำแหน่งที่เก็บข้อมูลวันที่-เวลาทั้งหมด รวมถึง master slides, layout slides และ slides. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | เปลี่ยนการมองเห็นของตำแหน่งที่เก็บข้อมูลส่วนท้าย, วันที่-เวลา และหมายเลขหน้า สำหรับสไลด์หัวเรื่องทั้งหมดและสไลด์เลย์เอาต์แรก สไลด์หัวเรื่อง – สไลด์ที่อิงตามสไลด์เลย์เอาต์แรก (โดยไม่คำนึงถึงประเภทของเลย์เอาต์แรกนี้). |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตำแหน่งที่เก็บข้อมูลส่วนหัวทั้งหมด รวมถึง notes master, notes slides และ handout master.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตำแหน่งที่เก็บข้อมูลส่วนหัวแสดงผล, มิฉะนั้น - ซ่อนมัน. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตำแหน่งที่เก็บข้อมูลส่วนท้ายทั้งหมด รวมถึง master slides, layout slides และ slides.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตำแหน่งที่เก็บข้อมูลส่วนท้ายแสดงผล, มิฉะนั้น - ซ่อนมัน. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตำแหน่งที่เก็บข้อมูลหมายเลขหน้าทั้งหมด รวมถึง master slides, layout slides และ slides.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตำแหน่งที่เก็บข้อมูลหมายเลขหน้าแสดงผล, มิฉะนั้น - ซ่อนมัน. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตำแหน่งที่เก็บข้อมูลวันที่-เวลาทั้งหมด รวมถึง master slides, layout slides และ slides.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตำแหน่งที่เก็บข้อมูลวันที่-เวลาแสดงผล, มิฉะนั้น - ซ่อนมัน. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

ตั้งข้อความให้กับตำแหน่งที่เก็บข้อมูลส่วนหัวทั้งหมด รวมถึง notes master, notes slides และ handout master.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้ง. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

ตั้งข้อความให้กับตำแหน่งที่เก็บข้อมูลส่วนท้ายทั้งหมด รวมถึง master slides, layout slides และ slides.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้ง. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

ตั้งข้อความให้กับตำแหน่งที่เก็บข้อมูลวันที่-เวลาทั้งหมด รวมถึง master slides, layout slides และ slides.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้ง. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

เปลี่ยนการมองเห็นของตำแหน่งที่เก็บข้อมูลส่วนท้าย, วันที่-เวลา และหมายเลขหน้า สำหรับสไลด์หัวเรื่องทั้งหมดและสไลด์เลย์เอาต์แรก true - ทำให้ตำแหน่งที่เก็บข้อมูลแสดงผล, มิฉะนั้น - ซ่อนมัน.