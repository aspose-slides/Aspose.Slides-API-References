---
title: TiffOptions
second_title: Aspose.Sildes สำหรับอ้างอิง API ของ .NET
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ TIFF
type: docs
weight: 4570
url: /th/aspose.slides.export/tiffoptions/
---
## TiffOptions คลาส

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ TIFF

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## คอนสตรัคเตอร์

| ชื่อ | คำอธิบาย |
| --- | --- |
| [TiffOptions](tiffoptions)() | คอนสตรัคเตอร์เริ่มต้น. |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | ระบุอัลกอริธึมสำหรับการแปลงภาพสีให้เป็นภาพขาว-ดำ ตัวเลือกนี้จะใช้ก็ต่อเมื่อ [`CompressionType`](./compressiontype) ถูกตั้งค่าเป็น CCITT4 หรือ CCITT3 อ่าน/เขียน [`BlackWhiteConversionMode`](../blackwhiteconversionmode). ค่าเริ่มต้นคือ Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | ระบุประเภทการบีบอัด. อ่าน/เขียน [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | คืนค่า หรือกำหนดแบบอักษรที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ. อ่าน-เขียน String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | ระบุความละเอียดแนวนอนเป็นจุดต่อนิ้ว. อ่าน/เขียน UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | ระบุความละเอียดแนวตั้งเป็นจุดต่อนิ้ว. อ่าน/เขียน UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | คืนค่า หรือกำหนดสไตล์ภาพของการไล่สี. อ่าน/เขียน [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | ระบุขนาดของภาพ TIFF ที่สร้างขึ้น ค่าเริ่มต้นคือ 0x0 ซึ่งหมายความว่าขนาดภาพที่สร้างจะคำนวนจากค่าขนาดสไลด์ของงานนำเสนอ. อ่าน/เขียน Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. อ่านอย่างเดียว [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | ระบุรูปแบบพิกเซลสำหรับภาพที่สร้างขึ้น. อ่าน/เขียน [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | เป็นอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์. ดู [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | ระบุว่าหนังสือที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ. อ่าน/เขียน Boolean. ค่าเริ่มต้นคือ **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | รับหรือกำหนดโหมดที่สไลด์จะวางบนหน้าเมื่อส่งออกงานนำเสนอ [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | คืนค่า หรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่าน/เขียน [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น TIFF ด้วยขนาดเริ่มต้น.

```csharp
[C#]
// สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนไฟล์งานนำเสนอ
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // บันทึกงานนำเสนอเป็นเอกสาร TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น TIFF ด้วยขนาดที่กำหนดเอง.

```csharp
[C#]
// สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนไฟล์ Presentation
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // สร้างอ็อบเจ็กต์ของคลาส TiffOptions
    TiffOptions opts = new TiffOptions();
    // ตั้งค่าชนิดการบีบอัด
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // ชนิดการบีบอัด
    // Default - ระบุโครงสร้างการบีบอัดเริ่มต้น (LZW).
    // None - ระบุว่าไม่มีการบีบอัด.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // ความลึกขึ้นอยู่กับชนิดการบีบอัดและไม่สามารถตั้งค่าด้วยตนเองได้.
    // หน่วยความละเอียดจะเท่ากับ “2” เสมอ (จุดต่ออินช์)
    // ตั้งค่า DPI ของภาพ
    opts.DpiX = 200;
    opts.DpiY = 100;
    // ตั้งค่าขนาดภาพ
    opts.ImageSize = new Size(1728, 1078);
    // บันทึกงานนำเสนอเป็น TIFF ด้วยขนาดภาพที่ระบุ
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น TIFF ด้วยรูปแบบพิกเซลของภาพที่กำหนดเอง.

```csharp
[C#]
// สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนไฟล์ Presentation
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat มีค่าต่อไปนี้ (ตามที่พบในเอกสาร):
    Format1bppIndexed; // 1 บิตต่อพิกเซล, แบบดัชนี.
    Format4bppIndexed; // 4 บิตต่อพิกเซล, แบบดัชนี.
    Format8bppIndexed; // 8 บิตต่อพิกเซล, แบบดัชนี.
    Format24bppRgb; // 24 บิตต่อพิกเซล, RGB.
    Format32bppArgb; // 32 บิตต่อพิกเซล, ARGB.
    */
    // บันทึกงานนำเสนอเป็น TIFF ด้วยขนาดภาพที่ระบุ
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions)
* อินเทอร์เฟซ [ITiffOptions](../itiffoptions)
* เนมสเปซ [Aspose.Slides.Export](../../aspose.slides.export)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->