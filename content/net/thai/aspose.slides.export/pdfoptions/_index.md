---
title: PdfOptions
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
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

| ชื่อ | รายละเอียด |
| --- | --- |
| [PdfOptions](pdfoptions)() | คอนสตรักเตอร์เริ่มต้น. |

## คุณสมบัติ

| ชื่อ | รายละเอียด |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | ประกอบด้วยชุดของแฟลกที่ระบุว่าการอนุญาตการเข้าถึงใดควรได้รับเมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้ ดู [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | รับหรือกำหนดอาร์เรย์ของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง Aspose.Slides ควรพิจณาว่าเป็นฟอนต์ทั่วไป. อ่าน/เขียน String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | ใช้สีโปร่งแสงที่ระบุกับภาพหาก `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | ระบุว่าการบีบอัดที่มีประสิทธิภาพที่สุด (แทนการบีบอัดเริ่มต้น) สำหรับแต่ละภาพควรเลือกโดยอัตโนมัติหรือไม่ หากตั้งค่าเป็น Boolean.true, สำหรับทุกภาพในงานนำเสนอ อัลกอริทึมการบีบอัดที่เหมาะสมที่สุดจะถูกเลือก ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่ได้เล็กลง การเลือกอัตราการบีบอัดภาพที่ดีที่สุดมีการใช้คอมพิวเตอร์มากและต้องใช้ RAM เพิ่มเติม, และตัวเลือกนี้ตั้งค่าเริ่มต้นเป็น Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้างขึ้น. อ่าน/เขียน [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | รับหรือกำหนดฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นทาง. อ่าน/เขียน String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | ตั้งค่าเป็น `true` เพื่อวาดกรอบสีดำรอบสไลด์แต่ละสไลด์. อ่าน/เขียน Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | กำหนดว่าต้องฝังอักขระทั้งหมดของฟอนต์หรือเฉพาะชุดย่อยที่ใช้. อ่าน/เขียน Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | กำหนดว่า Aspose.Slides จะฝังฟอนต์ทั่วไปสำหรับข้อความ ASCII (ช่วงรหัส 33..127) หรือไม่. ฟอนต์สำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ. รายการฟอนต์ทั่วไปรวมถึงฟอนต์ฐาน 14 ของ PDF และฟอนต์เพิ่มเติมที่ผู้ใช้ระบุ. อ่าน/เขียน Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | รับหรือกำหนดสไตล์ภาพของการไล่สี. อ่าน/เขียน [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | รับหรือกำหนดสีโปร่งแสงของภาพ. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | ตั้งค่าเป็น `true` เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้. อ่าน/เขียน Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. อ่านอย่างเดียว [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | รับหรือกำหนดค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF. อ่าน/เขียน Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | ตั้งค่ารหัสผ่านผู้ใช้เพื่อป้องกันเอกสาร PDF. อ่าน/เขียน String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | เป็นอ็อบเจ็กต์ callback สำหรับอัปเดตความคืบหน้าในการบันทึกเป็นเปอร์เซ็นต์. ดู [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | ระบุว่าข้อความควรถูกแปลงเป็นบิตแมปและบันทึกเป็น PDF เมื่อฟอนต์ไม่สนับสนุนการทำตัวหนา วิธีนี้สามารถปรับปรุงคุณภาพของข้อความใน PDF ที่ได้สำหรับฟอนต์บางประเภท. อ่าน/เขียน Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | ตั้งค่าเป็น `true` เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. อ่าน/เขียน Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนไว้หรือไม่. ค่าเริ่มต้นคือ `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | ระบุว่าควรข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ. อ่าน/เขียน Boolean. ค่าเริ่มต้นคือ **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | รับหรือกำหนดค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | ระบุประเภทการบีบอัดที่จะใช้กับเนื้อหาเชิงข้อความทั้งหมดในเอกสาร. อ่าน/เขียน [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | รับหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือถูกยกเลิก. อ่าน/เขียน [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PDF พร้อมตัวเลือกที่กำหนดเอง.

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

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PDF พร้อมสไลด์ที่ซ่อน.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์ PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// สร้างอินสแตนซ์ของคลาส PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// เพิ่มสไลด์ที่ซ่อน
	pdfOptions.ShowHiddenSlides = true;
	// บันทึกงานนำเสนอเป็น PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PDF ที่มีการป้องกันด้วยรหัสผ่าน.

```csharp
[C#]
// สร้างอ็อบเจกต์ Presentation ที่แทนไฟล์ PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// สร้างอินสแตนซ์ของคลาส PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// ตั้งค่ารหัสผ่าน PDF และการอนุญาตการเข้าถึง
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// บันทึกงานนำเสนอเป็น PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PDF พร้อมบันทึกย่อ.

```csharp
[C#]
// สร้างอ็อบเจกต์ Presentation ที่แทนไฟล์การนำเสนอ
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// ตั้งค่าประเภทและขนาดสไลด์
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