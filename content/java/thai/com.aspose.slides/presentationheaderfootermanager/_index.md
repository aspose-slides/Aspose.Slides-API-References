---
title: PresentationHeaderFooterManager
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: เป็นตัวจัดการที่มีพฤติกรรมของตัวยึดส่วนท้าย วันที่-เวลา และหมายเลขหน้าทั้งหมดของงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/presentationheaderfootermanager/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)

**ทั้งหมดของอินเทอร์เฟซที่ทำการใช้งาน:**
[com.aspose.slides.IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
```
public class PresentationHeaderFooterManager extends BaseHeaderFooterManager implements IPresentationHeaderFooterManager
```

เป็นตัวจัดการที่มีพฤติกรรมของตัวยึดส่วนท้าย, วันที่-เวลา และหมายเลขหน้าทั้งหมดของงานนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวยึดส่วนหัวทั้งหมด รวมถึง notes master, notes slides และ handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวยึดส่วนท้ายทั้งหมด รวมถึง master slides, layout slides, slides, notes master, notes slides และ handout master. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวยึดหมายเลขหน้าทั้งหมด รวมถึง master slides, layout slides, slides, notes master, notes slides และ handout master. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | เปลี่ยนการมองเห็นของตัวยึดวันที่-เวลา ทั้งหมด รวมถึง master slides, layout slides, slides, notes master, notes slides และ handout master. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | กำหนดข้อความให้กับตัวยึดส่วนหัวทั้งหมด รวมถึง notes master, notes slides และ handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | กำหนดข้อความให้กับตัวยึดส่วนท้ายทั้งหมด รวมถึง master slides, layout slides, slides, notes master, notes slides และ handout master. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | กำหนดข้อความให้กับตัวยึดวันที่-เวลา ทั้งหมด รวมถึง master slides, layout slides, slides, notes master, notes slides และ handout master. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | เปลี่ยนการมองเห็นของตัวยึดส่วนท้าย, วันที่-เวลา และหมายเลขหน้าสำหรับสไลด์หัวเรื่องทั้งหมดและสไลด์เลเอาต์แรก. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public final void setAllHeadersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวยึดส่วนหัวทั้งหมด รวมถึง notes master, notes slides และ handout master.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดส่วนหัวเป็นที่มองเห็น, หากไม่เช่นนั้น - ซ่อนตัวยึดเหล่านั้น. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public final void setAllFootersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวยึดส่วนท้ายทั้งหมด รวมถึง master slides, layout slides, slides, notes master, notes slides และ handout master.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดส่วนท้ายเป็นที่มองเห็น, หากไม่เช่นนั้น - ซ่อนตัวยึดเหล่านั้น. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public final void setAllSlideNumbersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวยึดหมายเลขหน้าทั้งหมด รวมถึง master slides, layout slides, slides, notes master, notes slides และ handout master.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดหมายเลขหน้าเป็นที่มองเห็น, หากไม่เช่นนั้น - ซ่อนตัวยึดเหล่านั้น. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public final void setAllDateTimesVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวยึดวันที่-เวลา ทั้งหมด รวมถึง master slides, layout slides, slides, notes master, notes slides และ handout master.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดวันที่-เวลาเป็นที่มองเห็น, หากไม่เช่นนั้น - ซ่อนตัวยึดเหล่านั้น. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public final void setAllHeadersText(String text)
```

กำหนดข้อความให้กับตัวยึดส่วนหัวทั้งหมด รวมถึง notes master, notes slides และ handout master.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public final void setAllFootersText(String text)
```

กำหนดข้อความให้กับตัวยึดส่วนท้ายทั้งหมด รวมถึง master slides, layout slides, slides, notes master, notes slides และ handout master.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public final void setAllDateTimesText(String text)
```

กำหนดข้อความให้กับตัวยึดวันที่-เวลา ทั้งหมด รวมถึง master slides, layout slides, slides, notes master, notes slides และ handout master.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public final void setVisibilityOnAllTitleSlides(boolean isVisible)
```

เปลี่ยนการมองเห็นของตัวยึดส่วนท้าย, วันที่-เวลา และหมายเลขหน้าสำหรับสไลด์หัวเรื่องทั้งหมดและสไลด์เลเอาต์แรก. สไลด์หัวเรื่อง \\u2013 สไลด์ที่อิงจากสไลด์เลเอาต์แรก (โดยไม่คำนึงถึงประเภทของเลเอาต์แรกนี้).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตัวยึดต่าง ๆ เป็นที่มองเห็น, หากไม่เช่นนั้น - ซ่อนตัวยึด. |