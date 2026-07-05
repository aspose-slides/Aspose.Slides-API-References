---
title: SwfOptions
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ Swf.
type: docs
weight: 4530
url: /th/aspose.slides.export/swfoptions/
---
## SwfOptions คลาส

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ Swf

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## คอนสตรัคเตอร์

| ชื่อ | คำอธิบาย |
| --- | --- |
| [SwfOptions](swfoptions)() | คอนสตรัคเตอร์เริ่มต้น |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | ระบุว่าเอกสาร SWF ที่สร้างขึ้นควรบีบอัดหรือไม่ ค่าเริ่มต้นคือ `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | คืนค่าหรือกำหนดแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง. อ่าน-เขียน String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | เปิด/ปิดเมนูบริบท. ค่าเริ่มต้นคือ true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | คืนค่าหรือกำหนดสไตล์การแสดงผลของการไล่สี. อ่าน/เขียน [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | ระบุคุณภาพของรูปภาพ JPEG. ค่าเริ่มต้นคือ 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | รูปภาพที่จะถูกแสดงเป็นโลโก้ที่มุมบนขวาของตัวดู. รูปภาพควรเป็น PNG ขนาด 32x64 พิกเซล, มิฉะนั้นโลโก้อาจแสดงไม่ถูกต้อง. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | รับหรือกำหนดที่อยู่ว hyperlink เต็มสำหรับโลโก้. มีผลเฉพาะเมื่อมีการระบุ [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | เป็นออบเจกต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์. ดู [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | แสดง/ซ่อนแผงด้านล่าง. สามารถแทนค่าผ่าน flashvars. ค่าเริ่มต้นคือ true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | แสดง/ซ่อนปุ่มเต็มจอ. สามารถแทนค่าผ่าน flashvars. ค่าเริ่มต้นคือ true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | ระบุว่าเอกสารที่สร้างขึ้นควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | แสดง/ซ่อนแผงด้านซ้าย. สามารถแทนค่าผ่าน flashvars. ค่าเริ่มต้นคือ true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | ระบุว่าขอบรอบหน้า should be shown. ค่าเริ่มต้นคือ true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | แสดง/ซ่อนตัวควบคุมขั้นตอนหน้า. สามารถแทนค่าผ่าน flashvars. ค่าเริ่มต้นคือ true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | แสดง/ซ่อนส่วนค้นหา. สามารถแทนค่าผ่าน flashvars. ค่าเริ่มต้นคือ true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | แสดง/ซ่อนแผงบนทั้งหมด. สามารถแทนค่าผ่าน flashvars. ค่าเริ่มต้นคือ true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | ระบุว่าจะข้าม hyperlink ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ. อ่าน/เขียน Boolean. ค่าดีฟอลต์คือ **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกการนำเสนอ [`ISlidesLayoutOptions`](../islideslayoutoptions). คุณสมบัตินี้ไม่รองรับการกำหนดออบเจกต์ประเภท [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | เริ่มต้นด้วยแผงด้านซ้ายที่เปิดอยู่. สามารถแทนค่าผ่าน flashvars. ค่าเริ่มต้นคือ false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | ระบุว่าเอกสาร SWF ที่สร้างขึ้นควรรวมตัวดูเอกสารแบบบูรณาการหรือไม่. ค่าเริ่มต้นคือ `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | คืนค่า หรือกำหนดออบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่าน/เขียน [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น SWF Flash

```csharp
[C#]
// สร้างอ็อบเจกต์ Presentation ที่เป็นตัวแทนของไฟล์การนำเสนอ
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // บันทึกการนำเสนอและหน้าโน้ต
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