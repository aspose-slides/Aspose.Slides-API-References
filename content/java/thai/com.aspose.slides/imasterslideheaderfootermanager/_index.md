---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: แสดงถึงผู้จัดการที่ถือพฤติกรรมของตารางส่วนท้ายของสไลด์หลัก, ตัวกำหนดวันที่-เวลา, ตัวกำหนดหมายเลขหน้า และตารางส่วนย่อยทั้งหมด.
type: docs
url: /th/com.aspose.slides/imasterslideheaderfootermanager/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

เป็นผู้จัดการที่ถือพฤติกรรมของตารางส่วนท้ายของสไลด์หลัก, ตัวกำหนดวันที่-เวลา, ตัวกำหนดหมายเลขหน้าและตารางส่วนย่อยทั้งหมด. ตารางส่วนย่อยหมายถึงตารางที่อยู่ในสไลด์เทมเพลตที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เทมเพลตและสไลด์ที่ขึ้นกับใช้และพึ่งพาสไลด์หลัก.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes master slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes master slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes master slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to master slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to master slide date-time placeholder and all child date-time placeholders. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตารางส่วนท้ายของสไลด์หลักและตารางส่วนท้ายของส่วนย่อยทั้งหมด. ตารางส่วนย่อยหมายถึงตารางที่อยู่ในสไลด์เทมเพลตที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เทมเพลตและสไลด์ที่ขึ้นกับใช้และพึ่งพาสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตารางส่วนท้ายเป็นที่มองเห็น, มิฉะนั้น - ซ่อนมัน. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตารางหมายเลขหน้าของสไลด์หลักและตารางหมายเลขหน้าของส่วนย่อยทั้งหมด. ตารางส่วนย่อยหมายถึงตารางที่อยู่ในสไลด์เทมเพลตที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เทมเพลตและสไลด์ที่ขึ้นกับใช้และพึ่งพาสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตารางหมายเลขหน้เป็นที่มองเห็น, มิฉะนั้น - ซ่อนมัน. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

เปลี่ยนการมองเห็นของตารางวันที่-เวลาของสไลด์หลักและตารางวันที่-เวลาของส่วนย่อยทั้งหมด. ตารางส่วนย่อยหมายถึงตารางที่อยู่ในสไลด์เทมเพลตที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เทมเพลตและสไลด์ที่ขึ้นกับใช้และพึ่งพาสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| isVisible | boolean | true - ทำให้ตารางวันที่-เวลาเป็นที่มองเห็น, มิฉะนั้น - ซ่อนมัน. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

ตั้งค่าข้อความให้กับตารางส่วนท้ายของสไลด์หลักและตารางส่วนท้ายของส่วนย่อยทั้งหมด. ตารางส่วนย่อยหมายถึงตารางที่อยู่ในสไลด์เทมเพลตที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เทมเพลตและสไลด์ที่ขึ้นกับใช้และพึ่งพาสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

ตั้งค่าข้อความให้กับตารางวันที่-เวลาของสไลด์หลักและตารางวันที่-เวลาของส่วนย่อยทั้งหมด. ตารางส่วนย่อยหมายถึงตารางที่อยู่ในสไลด์เทมเพลตที่ขึ้นกับและสไลด์ที่ขึ้นกับ. สไลด์เทมเพลตและสไลด์ที่ขึ้นกับใช้และพึ่งพาสไลด์หลัก.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความที่จะตั้งค่า. |