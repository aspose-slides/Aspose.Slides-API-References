---
title: SwfOptions
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: จัดหาตัวเลือกที่ควบคุมวิธีการบันทึกการพรีเซนเทชันในรูปแบบ Swf
type: docs
weight: 4550
url: /th/aspose.slides.export/swfoptions/
---
## SwfOptions คลาส

จัดหาตัวเลือกที่ควบคุมวิธีการบันทึกพรีเซนเทชันในรูปแบบ Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [SwfOptions](swfoptions)() | คอนสตรัคเตอร์เริ่มต้น |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | ระบุว่าเอกสาร SWF ที่สร้างขึ้นควรบีบอัดหรือไม่ ค่าตั้งต้นคือ `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | คืนค่า หรือกำหนดแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง อ่านและเขียน String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | เปิดหรือปิดเมนูบริบท ค่าตั้งต้นคือ true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | คืนค่า หรือกำหนดสไตล์การแสดงผลของการไล่ระดับสี อ่านและเขียน [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | ระบุคุณภาพของภาพ JPEG ค่าตั้งต้นคือ 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | รูปภาพที่จะถูกแสดงเป็นโลโก้ที่มุมขวาบนของตัวดูภาพ ควรเป็นภาพ PNG ขนาด 32x64 พิกเซล หากไม่เป็นอาจทำให้โลโก้แสดงผิดพลาด |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | คืนค่า หรือกำหนดที่อยู่ไฮเปอร์ลิงก์เต็มของโลโก้ มีผลต่อเฉพาะเมื่อมีการระบุ [`LogoImageBytes`](./logoimagebytes) |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | แสดงออบเจกต์ callback สำหรับอัปเดตความคืบหน้าการบันทึกเป็นเปอร์เซ็นต์ ดู [`IProgressCallback`](../../aspose.slides/iprogresscallback) |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | แสดงหรือซ่อนแผงด้านล่าง สามารถถูกทับค่าใน flashvars ค่าตั้งต้นคือ true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | แสดงหรือซ่อนปุ่มเต็มหน้าจอ สามารถถูกทับค่าใน flashvars ค่าตั้งต้นคือ true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนไว้หรือไม่ ค่าตั้งต้นคือ `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | แสดงหรือซ่อนแผงด้านซ้าย สามารถถูกทับค่าใน flashvars ค่าตั้งต้นคือ true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | ระบุว่าควรแสดงขอบของหน้าหรือไม่ ค่าตั้งต้นคือ true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | แสดงหรือซ่อนตัวควบคุมการเปลี่ยนหน้า สามารถถูกทับค่าใน flashvars ค่าตั้งต้นคือ true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | แสดงหรือซ่อนส่วนการค้นหา สามารถถูกทับค่าใน flashvars ค่าตั้งต้นคือ true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | แสดงหรือซ่อนแผงบนทั้งหมด สามารถถูกทับค่าใน flashvars ค่าตั้งต้นคือ true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript เมื่อบันทึกพรีเซนเทชันหรือไม่ อ่านและเขียน Boolean ค่าตั้งต้นคือ **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | คืนค่า หรือกำหนดโหมดที่สไลด์วางบนหน้าเมื่อส่งออกพรีเซนเทชัน [`ISlidesLayoutOptions`](../islideslayoutoptions) คุณสมบัตินี้ไม่สนับสนุนการกำหนดออบเจกต์ประเภท [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | เริ่มต้นด้วยแผงด้านซ้ายเปิดอยู่ สามารถถูกทับค่าใน flashvars ค่าตั้งต้นคือ false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | ระบุว่าเอกสาร SWF ที่สร้างควรรวมตัวดูเอกสารแบบบูรณาการหรือไม่ ค่าตั้งต้นคือ `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | คืนค่า หรือกำหนดออบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือหยุดลง อ่านและเขียน [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการแปลง PowerPoint เป็น SWF Flash.

```csharp
[C#]
// สร้างอ็อบเจกต์ Presentation ที่เป็นตัวแทนของไฟล์พรีเซนเทชัน
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // บันทึกรายการพรีเซนเทชันและหน้าบันทึกย่อ
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions)
* อินเทอร์เฟซ [ISwfOptions](../iswfoptions)
* เนมสเปซ [Aspose.Slides.Export](../../aspose.slides.export)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->