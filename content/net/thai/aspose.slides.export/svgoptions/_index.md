---
title: SVGOptions
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: เป็นตัวเลือกของ SVG.
type: docs
weight: 4450
url: /th/aspose.slides.export/svgoptions/
---
## SVGOptions คลาส

เป็นตัวเลือก SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## คอนสตรักเตอร์

| Name | Description |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initializes a new instance of the SVGOptions class. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

## คุณสมบัติ

| Name | Description |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | คืนค่าการตั้งค่าเริ่มต้น. อ่านอย่างเดียว [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | คืนค่าการตั้งค่าสำหรับการสร้างไฟล์ SVG ที่ง่ายที่สุดและมีขนาดเล็กที่สุด. อ่านอย่างเดียว [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | คืนค่าการตั้งค่าสำหรับการสร้างไฟล์ SVG ที่แม่นยำที่สุด. อ่านอย่างเดียว [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | คืนค่าหรือกำหนดแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. อ่านและเขียน String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | แฟล็กแบบบูลีนบ่งบอกว่าชิ้นส่วนที่ตัดออกยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่. หากเป็น true ชิ้นส่วนที่ตัดออกจะถูกลบ, หากเป็น false จะถูกจัดเก็บเป็นซีเรียลไลซ์ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น) |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | กำหนดว่าข้อความ 3D จะถูกปิดใช้งานใน SVG หรือไม่. อ่านและเขียน Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกแสดงผลโดยไม่ใช้ลิการอร์ดหรือไม่. เมื่อกำหนดเป็น `true` ลิการอร์ดจะถูกปิดในผลลัพธ์ที่แสดง. ค่าเริ่มต้นของคุณสมบัตินี้คือ `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | ปิดการแยกเกรเดียนต์ FromCornerX และ FromCenter. อ่านและเขียน Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 ขาดความสามารถในการกำหนดอินเซ็ตสำหรับมาร์กเกอร์. Enginer การเขียน SVG ของ Aspose.Slides มีวิธีแก้ปัญหานี้: มันตัดส่วนท้ายของเส้นที่มีลูกศร, ดังนั้นเส้นจะไม่ทับมาร์กเกอร์. ตัวเลือกนี้ปิดพฤติกรรมดังกล่าว. อ่านและเขียน Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | กำหนดวิธีการจัดการแบบอักษรที่โหลดจากภายนอก. อ่านและเขียน [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | คืนค่าหรือกำหนดรูปแบบการแสดงผลของเกรเดียนต์. อ่านและเขียน [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก. อ่านอย่างเดียว [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | กำหนดคุณภาพการเข้ารหัส JPEG. อ่านและเขียน Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | คืนค่าหรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไลซ์เมตาฟายล์. อ่านและเขียน Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | แสดงระดับการบีบอัดรูปภาพ |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | แสดงวัตถุ callback สำหรับบันทึกการอัพเดตความคืบหน้าเป็นเปอร์เซ็นต์. ดู [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | คืนค่าและกำหนดอินเทอร์เฟซ callback ที่ให้ผู้ใช้ควบคุมการแปลงรูปร่าง. อ่านและเขียน [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่เรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ. อ่านและเขียน Boolean. ค่าเริ่มต้นคือ **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | กำหนดว่าจะทำการหมุนรูปร่างตามที่ระบุเมื่อเรนเดอร์หรือไม่. อ่านและเขียน Boolean. ค่าเริ่มต้นคือ true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | กำหนดว่าจะรวมเฟรมข้อความในพื้นที่เรนเดอร์หรือไม่. อ่านและเขียน Boolean. ค่าเริ่มต้นคือ false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | กำหนดว่าข้อความบนสไลด์จะถูกบันทึกเป็นกราฟิกหรือไม่. อ่านและเขียน Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | คืนค่าและกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่านและเขียน [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions)
* อินเทอร์เฟซ [ISVGOptions](../isvgoptions)
* เนมสเปซ [Aspose.Slides.Export](../../aspose.slides.export)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->