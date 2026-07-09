---
title: SVGOptions
second_title: Aspose.Sildes สำหรับ .NET API อ้างอิง
description: เป็นตัวแทนของตัวเลือก SVG.
type: docs
weight: 4430
url: /th/aspose.slides.export/svgoptions/
---
## SVGOptions คลาส

เป็นตัวแทนของตัวเลือก SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions โดยระบุอ็อบเจ็กต์ตัวควบคุมการฝังลิงก์. |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | คืนค่าการตั้งค่าเริ่มต้น. อ่านอย่างเดียว [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | คืนค่าการตั้งค่าสำหรับการสร้างไฟล์ SVG ที่ง่ายที่สุดและเล็กที่สุด. อ่านอย่างเดียว [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | คืนค่าการตั้งสําหรับการสร้างไฟล์ SVG ที่แม่นยำที่สุด. อ่านอย่างเดียว [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | คืนค่า或กำหนดฟอนต์ที่จะใช้ในกรณีที่ไม่พบฟอนต์ต้นทาง. อ่าน/เขียน String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | แฟล็กบูลีนระบุว่าตำแหน่งที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. ถ้าเป็น true ส่วนที่ถูกตัดจะถูกลบ, ถ้าเป็น false จะถูกจัดเก็บในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น) |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | กำหนดว่าข้อความ 3D จะถูกปิดใช้งานใน SVG หรือไม่. อ่าน/เขียน Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกแสดงโดยไม่ใช้ลิเกเจอร์. เมื่อกำหนดเป็น `true` ลิเกเจอร์จะถูกปิดในผลลัพธ์ที่แสดง. ค่าเริ่มต้นของคุณสมบัตินี้คือ `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | ปิดการแยกส่วนกราเดียน FromCornerX และ FromCenter. อ่าน/เขียน Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 ไม่สามารถกำหนดช่องว่างสำหรับมาร์คเกอร์ได้. เครื่องมือเขียน SVG ของ Aspose.Slides มีวิธีแก้ไขปัญหานี้: จะตัดส่วนปลายของเส้นที่มีลูกศรเพื่อไม่ให้เส้นทับกับมาร์คเกอร์. ตัวเลือกนี้จะปิดการทำงานดังกล่าว. อ่าน/เขียน Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก. อ่าน/เขียน [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | คืนค่า或กำหนดสไตล์การแสดงผลของกราเดียน. อ่าน/เขียน [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก. อ่านอย่างเดียว [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | กำหนดคุณภาพการเข้ารหัส JPEG. อ่าน/เขียน Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | คืนค่า或กำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์เมต้าไฟล์. อ่าน/เขียน Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | แสดงระดับการบีบอัดรูปภาพ |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | แสดงอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์. ดู [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | คืนค่าและกำหนดอินเทอร์เฟซ callback ที่ให้ผู้ใช้ควบคุมการแปลงรูปทรง. อ่าน/เขียน [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ. อ่าน/เขียน Boolean. ค่าเริ่มต้นคือ **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | กำหนดว่าจะทำการหมุนรูปทรงตามที่ระบุขณะเรนเดอร์หรือไม่. อ่าน/เขียน Boolean. ค่าเริ่มต้นคือ true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | กำหนดว่าจะรวมเฟรมข้อความในพื้นที่เรนเดอร์หรือไม่. อ่าน/เขียน Boolean. ค่าเริ่มต้นคือ false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | กำหนดว่าจะบันทึกข้อความบนสไลด์เป็นกราฟิกหรือไม่. อ่าน/เขียน Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | คืนค่าและกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่าน/เขียน [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions)
* อินเทอร์เฟซ [ISVGOptions](../isvgoptions)
* เนมสเปซ [Aspose.Slides.Export](../../aspose.slides.export)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->