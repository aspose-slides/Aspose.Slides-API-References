---
title: SVGOptions
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: เป็นตัวเลือกของ SVG.
type: docs
weight: 4430
url: /th/aspose.slides.export/svgoptions/
---
## SVGOptions คลาส

เป็นตัวเลือกของ SVG

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## คอนสตรัคเตอร์

| ชื่อ | คำอธิบาย |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | สร้างอินสแตนซ์ใหม่ของคลาส SVGOptions โดยระบุอ็อบเจกต์ตัวควบคุมการฝังลิงก์ |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | คืนค่าการตั้งค่าเริ่มต้น. อ่านอย่างเดียว [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | คืนค่าการตั้งค่าสำหรับการสร้างไฟล์ SVG ที่เรียบง่ายและขนาดเล็กที่สุด. อ่านอย่างเดียว [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | คืนค่าการตั้งค่าสำหรับการสร้างไฟล์ SVG ที่แม่นยำที่สุด. อ่านอย่างเดียว [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | รับหรือกำหนดแบบอักษรที่ใช้ในกรณีไม่พบแบบอักษรต้นฉบับ. อ่านเขียน String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | ฟลักบูลีนระบุว่าตำแหน่งที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่. หากเป็น true ตำแหน่งที่ถูกตัดจะถูกลบ, หากเป็น false จะถูกจัดเก็บในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น) |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | กำหนดว่าจะปิดใช้งานข้อความ 3D ใน SVG หรือไม่. อ่านเขียน Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความจะถูกเรนเดอร์โดยไม่ใช้ลิแกเชอร์หรือไม่. เมื่อกำหนดเป็น `true` ลิแกเชอร์จะถูกปิดใช้งานในผลลัพธ์ที่เรนเดอร์. โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งค่าเป็น `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | ปิดการแยกส่วนของกราเดียน FromCornerX และ FromCenter. อ่านเขียน Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 ขาดความสามารถในการกำหนดอินเซตสำหรับมาร์คเกอร์. เอนจิ์นการเขียน SVG ของ Aspose.Slides มีวิธีแก้ไขปัญหานี้: มันจะตัดส่วนปลายของเส้นที่มีลูกศรเพื่อไม่ให้เส้นทับมาร์คเกอร์. ตัวเลือกนี้ปิดการทำพฤติกรรมดังกล่าว. อ่านเขียน Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | กำหนดวิธีการจัดการแบบอักษรที่โหลดจากภายนอก. อ่านเขียน [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | รับหรือกำหนดสไตล์การแสดงผลของกราเดียน. อ่านเขียน [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจกต์ Ink ในเอกสารที่ส่งออก. อ่านอย่างเดียว [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | กำหนดคุณภาพการเข้ารหัส JPEG. อ่านเขียน Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | รับหรือกำหนดขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไลซ์เมตาฟายล์. อ่านเขียน Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | แสดงระดับการบีบอัดรูปภาพ |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | แสดงอ็อบเจกต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์. ดู [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | รับและกำหนดอินเทอร์เฟซ callback ที่ให้ผู้ใช้ควบคุมการแปลงรูปร่าง. อ่านเขียน [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript เมื่อบันทึกงานนำเสนอหรือไม่. อ่านเขียน Boolean. ค่าเริ่มต้นคือ **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | กำหนดว่าจะทำการหมุนรูปร่างตามที่ระบุเมื่อเรนเดอร์หรือไม่. อ่านเขียน Boolean. ค่าเริ่มต้นคือ true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | กำหนดว่าจะรวมเฟรมข้อความในพื้นที่เรนเดอร์หรือไม่. อ่านเขียน Boolean. ค่าเริ่มต้นคือ false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | กำหนดว่าจะบันทึกข้อความบนสไลด์เป็นกราฟิกหรือไม่. อ่านเขียน Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | รับหรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่านเขียน [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions)
* อินเทอร์เฟซ [ISVGOptions](../isvgoptions)
* เนมสเปซ [Aspose.Slides.Export](../../aspose.slides.export)
* อเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->