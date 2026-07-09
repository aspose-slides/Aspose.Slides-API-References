---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงผู้จัดการที่ดูแลพฤติกรรมของตัวเว้นส่วนคอลังท้ายของสไลด์บันทึกหลัก วันที่และเวลาหมายเลขหน้า และตัวเว้นทั้งหมดของสไลด์ลูก ตัวเว้นลูกหมายถึงตัวเว้นที่อยู่ในสไลด์บันทึกที่ขึ้นกับสไลด์หลัก สไลด์บันทึกที่ขึ้นกับใช้และพึ่งพาสไลด์บันทึกหลัก
type: docs
weight: 8020
url: /th/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager คลาส

Represents manager which holds behavior of the master notes slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending notes slides. Depending notes slides use and depend on master notes slide.

```csharp
public sealed class MasterNotesSlideHeaderFooterManager : BaseHandoutNotesSlideHeaderFooterManager, 
    IMasterNotesSlideHeaderFooterManager
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [IsDateTimeVisible](../../aspose.slides/baseslideheaderfootermanager/isdatetimevisible) { get; } | รับค่าที่บ่งชี้ว่ามีตัวเว้นของวันที่และเวลาอยู่. ReadBoolean. |
| [IsFooterVisible](../../aspose.slides/baseslideheaderfootermanager/isfootervisible) { get; } | รับค่าที่บ่งชี้ว่ามีตัวเว้นส่วนคอลังท้ายอยู่. Read Boolean. |
| [IsHeaderVisible](../../aspose.slides/basehandoutnotesslideheaderfootermanager/isheadervisible) { get; } | รับค่าที่บ่งชี้ว่ามีตัวเว้นส่วนหัวอยู่. Read Boolean. |
| [IsSlideNumberVisible](../../aspose.slides/baseslideheaderfootermanager/isslidenumbervisible) { get; } | รับค่าที่บ่งชี้ว่ามีตัวเว้นหมายเลขหน้อยู่. ReadBoolean. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [SetDateTimeAndChildDateTimesText](../../aspose.slides/masternotesslideheaderfootermanager/setdatetimeandchilddatetimestext)(string) | กำหนดข้อความให้กับตัวเว้นของวันที่และเวลาในสไลด์หลักและตัวเว้นของวันที่และเวลาในสไลด์ลูกทั้งหมด. ตัวเว้นลูกหมายถึงตัวเว้นที่อยู่ในสไลด์บันทึกที่ขึ้นกับสไลด์หลัก. สไลด์บันทึกที่ขึ้นกับใช้และพึ่งพาสไลด์บันทึกหลัก. |
| [SetDateTimeAndChildDateTimesVisibility](../../aspose.slides/masternotesslideheaderfootermanager/setdatetimeandchilddatetimesvisibility)(bool) | เปลี่ยนการแสดงผลของตัวเว้นของวันที่และเวลาในสไลด์หลักและตัวเว้นของวันที่และเวลาในสไลด์ลูกทั้งหมด. ตัวเว้นลูกหมายถึงตัวเว้นที่อยู่ในสไลด์บันทึกที่ขึ้นกับสไลด์หลัก. |
| [SetDateTimeText](../../aspose.slides/baseslideheaderfootermanager/setdatetimetext)(string) | กำหนดข้อความให้กับตัวเว้นของวันที่และเวลาในสไลด์. |
| [SetDateTimeVisibility](../../aspose.slides/baseslideheaderfootermanager/setdatetimevisibility)(bool) | เปลี่ยนการแสดงผลของตัวเว้นของวันที่และเวลาในสไลด์. |
| [SetFooterAndChildFootersText](../../aspose.slides/masternotesslideheaderfootermanager/setfooterandchildfooterstext)(string) | กำหนดข้อความให้กับตัวเว้นส่วนคอลังท้ายของสไลด์หลักและตัวเว้นส่วนคอลังท้ายของสไลด์ลูกทั้งหมด. ตัวเว้นลูกหมายถึงตัวเว้นที่อยู่ในสไลด์บันทึกที่ขึ้นกับสไลด์หลัก. |
| [SetFooterAndChildFootersVisibility](../../aspose.slides/masternotesslideheaderfootermanager/setfooterandchildfootersvisibility)(bool) | เปลี่ยนการแสดงผลของตัวเว้นส่วนคอลังท้ายของสไลด์หลักและตัวเว้นส่วนคอลังท้ายของสไลด์ลูกทั้งหมด. ตัวเว้นลูกหมายถึงตัวเว้นที่อยู่ในสไลด์บันทึกที่ขึ้นกับสไลด์หลัก. |
| [SetFooterText](../../aspose.slides/baseslideheaderfootermanager/setfootertext)(string) | กำหนดข้อความให้กับตัวเว้นส่วนคอลังท้ายในสไลด์. |
| [SetFooterVisibility](../../aspose.slides/baseslideheaderfootermanager/setfootervisibility)(bool) | เปลี่ยนการแสดงผลของตัวเว้นส่วนคอลังท้ายในสไลด์. |
| [SetHeaderAndChildHeadersText](../../aspose.slides/masternotesslideheaderfootermanager/setheaderandchildheaderstext)(string) | กำหนดข้อความให้กับตัวเว้นส่วนหัวของสไลด์บันทึกหลักและตัวเว้นส่วนหัวของสไลด์ลูกทั้งหมด. ตัวเว้นลูกหมายถึงตัวเว้นที่อยู่ในสไลด์บันทึกที่ขึ้นกับสไลด์หลัก. |
| [SetHeaderAndChildHeadersVisibility](../../aspose.slides/masternotesslideheaderfootermanager/setheaderandchildheadersvisibility)(bool) | เปลี่ยนการแสดงผลของตัวเว้นส่วนหัวของสไลด์บันทึกหลักและตัวเว้นส่วนหัวของสไลด์ลูกทั้งหมด. ตัวเว้นลูกหมายถึงตัวเว้นที่อยู่ในสไลด์บันทึกที่ขึ้นกับสไลด์หลัก. |
| [SetHeaderText](../../aspose.slides/basehandoutnotesslideheaderfootermanager/setheadertext)(string) | กำหนดข้อความให้กับตัวเว้นส่วนหัวในสไลด์. |
| [SetHeaderVisibility](../../aspose.slides/basehandoutnotesslideheaderfootermanager/setheadervisibility)(bool) | เปลี่ยนการแสดงผลของตัวเว้นส่วนหัวในสไลด์. |
| [SetSlideNumberAndChildSlideNumbersVisibility](../../aspose.slides/masternotesslideheaderfootermanager/setslidenumberandchildslidenumbersvisibility)(bool) | เปลี่ยนการแสดงผลของตัวเว้นหมายเลขหน้าของสไลด์หลักและตัวเว้นหมายเลขหน้าของสไลด์ลูกทั้งหมด. ตัวเว้นลูกหมายถึงตัวเว้นที่อยู่ในสไลด์บันทึกที่ขึ้นกับสไลด์หลัก. |
| [SetSlideNumberVisibility](../../aspose.slides/baseslideheaderfootermanager/setslidenumbervisibility)(bool) | เปลี่ยนการแสดงผลของตัวเว้นหมายเลขหน้าในสไลด์. |

### ดูเพิ่มเติม

* คลาส [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager)
* อินเทอร์เฟซ [IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->