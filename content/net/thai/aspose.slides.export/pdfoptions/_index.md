---
title: PdfOptions
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ Pdf.
type: docs
weight: 4330
url: /th/aspose.slides.export/pdfoptions/
---
## PdfOptions คลาส

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ Pdf

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [PdfOptions](pdfoptions)() | ตัวสร้างเริ่มต้น |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | มีชุดของแฟล็กที่ระบุว่าการอนุญาตการเข้าถึงใดควรให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้ ดู [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | คืนค่า หรือกำหนดอาร์เรย์ของชื่อฟอนต์ฟาเมลี่ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรถือว่าเป็นฟอนต์ทั่วไป. Read/write String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | ใช้สีโปร่งใสที่กำหนดกับภาพหาก `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | ระบุว่าควรเลือกการบีบอัดที่มีประสิทธิภาพสูงสุด (แทนการบีบอัดค่าเริ่มต้น) สำหรับแต่ละภาพโดยอัตโนมัติหรือไม่. หากตั้งค่าเป็น Boolean.true, สำหรับทุกภาพในงานนำเสนอจะเลือกอัลกอริธึมการบีบอัดที่เหมาะสมที่สุด ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่ได้เล็กลง. การเลือกอัตราการบีบอัดภาพที่ดีที่สุดต้องใช้การคำนวณมากและใช้หน่วยความจำเพิ่มเติม, ตัวเลือกนี้มีค่าเริ่มต้นเป็น Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | ระดับความสอดคล้องที่ต้องการสำหรับเอกสาร PDF ที่สร้างขึ้น. Read/write [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | คืนค่า หรือกำหนดฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นทาง. Read-write String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True เพื่อวาดกรอบสีดำรอบแต่ละสไลด์. Read/write Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | กำหนดว่าจะฝังอักขระทั้งหมดของฟอนต์หรือเพียงส่วนย่อยที่ใช้. Read/write Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | กำหนดว่า Aspose.Slides จะฝังฟอนต์ทั่วไปสำหรับข้อความ ASCII (ช่วงโค้ด 33..127) หรือไม่. ฟอนต์สำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ. รายการฟอนต์ทั่วไปประกอบด้วยฟอนต์ฐาน 14 ของ PDF และฟอนต์ที่ผู้ใช้กำหนดเพิ่มเติม. Read/write Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | คืนค่า หรือกำหนดสไตล์ภาพกราเดียนท์. Read/write [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | รับ หรือกำหนดสีโปร่งใสของภาพ. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. Read/write Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. Read-only [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | คืนค่า หรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. Read/write Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | ตั้งรหัสผ่านของผู้ใช้เพื่อปกป้องเอกสาร PDF. Read/write String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | เป็นอ็อบเจ็กต์ callback สำหรับอัพเดตความคืบหน้าในการบันทึกเป็นเปอร์เซ็นต์. ดู [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | ระบุว่าข้อความควรถูกแรสเตอร์ไลซ์เป็นบิทแมพและบันทึกเป็น PDF เมื่อฟอนต์ไม่สนับสนุนการทำตัวหนา. วิธีนี้สามารถปรับปรุงคุณภาพของข้อความใน PDF ที่ได้สำหรับฟอนต์บางรุ่น. Read/write Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. Read/write Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript เมื่อบันทึกงานนำเสนอหรือไม่. Read/write Boolean. ค่าเริ่มต้นคือ **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | รับ หรือกำหนดโหมดที่สไลด์จัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | คืนค่า หรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | ระบุประเภทการบีบอัดที่จะใช้สำหรับเนื้อหาข้อความทั้งหมดในเอกสาร. Read/write [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | คืนค่า หรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. Read/write [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PDF ด้วยตัวเลือกแบบกำหนดเอง.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// สร้างอินสแตนซ์ของคลาส PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// ตั้งค่าคุณภาพของ Jpeg
	pdfOptions.JpegQuality = 90;
	// ตั้งค่าพฤติกรรมสำหรับเมตาไฟล์
	pdfOptions.SaveMetafilesAsPng = true;
	// ตั้งค่าระดับการบีบอัดข้อความ
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// กำหนดมาตรฐาน PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// บันทึกงานนำเสนอเป็น PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PDF พร้อมสไลด์ที่ซ่อนอยู่.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation ที่แสดงไฟล์ PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// สร้างอินสแตนซ์ของคลาส PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// เพิ่มสไลด์ที่ซ่อนอยู่
	pdfOptions.ShowHiddenSlides = true;
	// บันทึกงานนำเสนอเป็น PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PDF ที่มีการป้องกันด้วยรหัสผ่าน.

```csharp
[C#]
// สร้างอินสแตนซ์ของออบเจ็กต์ Presentation ที่แสดงไฟล์ PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// สร้างอินสแตนซ์ของคลาส PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// ตั้งค่ารหัสผ่าน PDF และสิทธิ์การเข้าถึง
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// บันทึกงานนำเสนอเป็น PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PDF พร้อมบันทึกย่อ.

```csharp
[C#]
// สร้างอินสแตนซ์ของออบเจ็กต์ Presentation ที่แสดงไฟล์งานนำเสนอ
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// ตั้งค่าชนิดและขนาดสไลด์
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions)
* อินเทอร์เฟซ [IPdfOptions](../ipdfoptions)
* เนมสเปซ [Aspose.Slides.Export](../../aspose.slides.export)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->