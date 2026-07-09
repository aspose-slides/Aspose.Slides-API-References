---
title: SwfOptions
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอเป็นรูปแบบ Swf
type: docs
weight: 4530
url: /th/aspose.slides.export/swfoptions/
---
## SwfOptions คลาส

ให้ตัวเลือกที่ควบคุมการบันทึกงานนำเสนอเป็นรูปแบบ Swf

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## คอนสตรัคเตอร์

| ชื่อ | คำอธิบาย |
| --- | --- |
| [SwfOptions](swfoptions)() | คอนสตรัคเตอร์เริ่มต้น. |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | ระบุว่าดัชนี SWF ที่สร้างขึ้นควรทำการบีบอัดหรือไม่ ค่าเริ่มต้นคือ `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | คืนค่าหรือกำหนดแบบอักษรที่ใช้ในกรณีไม่พบแบบอักษรต้นทาง อ่าน-เขียน String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | เปิดหรือปิดเมนูบริบท ค่าเริ่มต้นคือ true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | คืนค่าหรือกำหนดรูปแบบการแสดงผลของการไล่สี อ่าน/เขียน [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | ระบุคุณภาพของภาพ JPEG ค่าเริ่มต้นคือ 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | ภาพที่จะปรากฏเป็นโลโก้ที่มุมบนขวาของตัวดู ควรเป็นภาพ PNG ขนาด 32x64 พิกเซล มิฉะนั้นโลโก้อาจแสดงไม่ถูกต้อง. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | รับหรือกำหนดที่อยู่ไฮเปอร์ลิงก์เต็มสำหรับโลโก้ จะมีผลเฉพาะเมื่อระบุ [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | แสดงถึงอ็อบเจ็กต์ callback สำหรับอัปเดตความคืบหน้าในการบันทึกเป็นเปอร์เซ็นต์ ดู [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | แสดง/ซ่อนแถบด้านล่าง สามารถแทนค่าผ่าน flashvars ได้ ค่าเริ่มต้นคือ true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | แสดง/ซ่อนปุ่มเต็มจอ สามารถแทนค่าผ่าน flashvars ได้ ค่าเริ่มต้นคือ true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | ระบุว่าตัวเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | แสดง/ซ่อนแถบด้านซ้าย สามารถแทนค่าผ่าน flashvars ได้ ค่าเริ่มต้นคือ true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | ระบุว่าควรแสดงกรอบรอบหน้าไหม ค่าเริ่มต้นคือ true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | แสดง/ซ่อนตัวควบคุมหน้ากระบวนการ (page stepper) สามารถแทนค่าผ่าน flashvars ได้ ค่าเริ่มต้นคือ true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | แสดง/ซ่อนส่วนค้นหา สามารถแทนค่าผ่าน flashvars ได้ ค่าเริ่มต้นคือ true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | แสดง/ซ่อนแถบบนทั้งหมด สามารถแทนค่าผ่าน flashvars ได้ ค่าเริ่มต้นคือ true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | ระบุว่าควรข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript เมื่อบันทึกงานนำเสนอหรือไม่ อ่าน/เขียน Boolean ค่าเริ่มต้นคือ **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | รับหรือกำหนดโหมดที่สไลด์จะจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [`ISlidesLayoutOptions`](../islideslayoutoptions) คุณสมบัตินี้ไม่รองรับการกำหนดอ็อบเจ็กต์ประเภท [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | เริ่มต้นด้วยแถบด้านซ้ายเปิดอยู่ สามารถแทนค่าผ่าน flashvars ได้ ค่าเริ่มต้นคือ false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | ระบุว่าดัชนี SWF ที่สร้างควรรวมตัวดูเอกสารแบบบูรณาการหรือไม่ ค่าเริ่มต้นคือ `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | คืนค่าหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก อ่าน/เขียน [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น SWF Flash.

```csharp
[C#]
// สร้างออบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์การนำเสนอ
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // บันทึกการนำเสนอและหน้าบันทึกย่อ
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions)
* อินเทอร์เฟส [ISwfOptions](../iswfoptions)
* เนมสเปซ [Aspose.Slides.Export](../../aspose.slides.export)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->