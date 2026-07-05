---
title: TiffOptions
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ TIFF.
type: docs
weight: 4570
url: /th/aspose.slides.export/tiffoptions/
---
## คลาส TiffOptions

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ TIFF

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [TiffOptions](tiffoptions)() | ตัวสร้างเริ่มต้น |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | ระบุอัลกอริทึมสำหรับการแปลงภาพสีให้เป็นภาพขาว-ดำ ตัวเลือกนี้จะมีผลเฉพาะเมื่อ [`CompressionType`](./compressiontype) ถูกตั้งค่าเป็น CCITT4 หรือ CCITT3 อ่าน/เขียน [`BlackWhiteConversionMode`](../blackwhiteconversionmode) ค่าเริ่มต้นคือ Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | ระบุประเภทการบีบอัด อ่าน/เขียน [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | คืนค่า หรือกำหนดฟอนท์ที่ใช้ในกรณีที่ไม่พบฟอนท์ต้นฉบับ อ่าน/เขียน String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | ระบุความละเอียดแนวนอนในหน่วยจุดต่อหนึ่งนิ้ว อ่าน/เขียน UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | ระบุความละเอียดแนวตั้งในหน่วยจุดต่อหนึ่งนิ้ว อ่าน/เขียน UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | คืนค่า หรือกำหนดสไตล์การแสดงผลของการไล่สี อ่าน/เขียน [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | ระบุขนาดของภาพ TIFF ที่สร้างขึ้น ค่าเริ่มต้นคือ 0x0 ซึ่งหมายความว่าขนาดภาพที่สร้างจะคำนวณจากค่าขนาดสไลด์ของงานนำเสนอ อ่าน/เขียน Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจกต์ Ink ในเอกสารที่ส่งออก อ่านอย่างเดียว [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | ระบุรูปแบบพิกเซลสำหรับภาพที่สร้างขึ้น อ่าน/เขียน [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | แสดงอ็อบเจกต์ callback สำหรับอัปเดตความคืบหน้าในการบันทึกเป็นเปอร์เซ็นต์ ดู [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ ค่าเริ่มต้นคือ `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript เมื่อบันทึกงานนำเสนอหรือไม่ อ่าน/เขียน Boolean ค่าตั้งต้นคือ **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | รับหรือกำหนดโหมดที่สไลด์จะวางบนหน้าเมื่อส่งออกงานนำเสนอ [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | คืนค่า หรือกำหนดอ็อบเจกต์ที่รับการเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิกอ่าน/เขียน [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น TIFF ด้วยขนาดเริ่มต้น.

```csharp
[C#]
// สร้างอ็อบเจกต์ Presentation ที่แสดงถึงไฟล์งานนำเสนอ
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // บันทึกงานนำเสนอเป็นเอกสาร TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น TIFF ด้วยขนาดที่กำหนดเอง.

```csharp
[C#]
// สร้างอ็อบเจกต์ Presentation ที่แสดงถึงไฟล์ Presentation
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // สร้างอ็อบเจกต์ของคลาส TiffOptions
    TiffOptions opts = new TiffOptions();
    // ตั้งค่าชนิดการบีบอัด
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // ชนิดการบีบอัด
    // Default - ระบุโครงการการบีบอัดเริ่มต้น (LZW).
    // None - ระบุว่าไม่มีการบีบอัด.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // ความลึกขึ้นอยู่กับชนิดการบีบอัดและไม่สามารถตั้งค่าได้ด้วยตนเอง.
    // Resolution unit  is always equal to “2” (dots per inch)
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
// สร้างอ็อบเจกต์ Presentation ที่แสดงถึงไฟล์ Presentation
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat มีค่าต่อไปนี้ (ตามที่ระบุในเอกสาร):
    Format1bppIndexed; // 1 บิตต่อพิกเซล, แบบจัดทำดัชนี.
    Format4bppIndexed; // 4 บิตต่อพิกเซล, แบบจัดทำดัชนี.
    Format8bppIndexed; // 8 บิตต่อพิกเซล, แบบจัดทำดัชนี.
    Format24bppRgb; // 24 บิตต่อพิกเซล, RGB.
    Format32bppArgb; // 32 บิตต่อพิกเซล, ARGB.
    */
    // บันทึกงานนำเสนอเป็น TIFF ด้วยขนาดภาพที่ระบุ
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

## ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions)
* อินเทอร์เฟซ [ITiffOptions](../itiffoptions)
* เนมสเปซ [Aspose.Slides.Export](../../aspose.slides.export)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->