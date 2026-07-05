---
title: Presentation
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: เป็นตัวแทนของงานนำเสนอ Microsoft PowerPoint
type: docs
weight: 9590
url: /th/aspose.slides/presentation/
---
## คลาส Presentation

เป็นตัวแทนของงานนำเสนอ Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## ตัวสร้าง

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Presentation](presentation#constructor)() | คอนสตรัคเตอร์นี้สร้างงานนำเสนอใหม่ตั้งแต่ต้น งานนำเสนอที่สร้างจะมีสไลด์ว่างหนึ่งสไลด์ |
| [Presentation](presentation#constructor_1)(LoadOptions) | คอนสตรัคเตอร์นี้สร้างงานนำเสนอใหม่ตั้งแต่ต้น งานนำเสนอที่สร้างจะมีสไลด์ว่างหนึ่งสไลด์ |
| [Presentation](presentation#constructor_2)(Stream) | คอนสตรัคเตอร์นี้เป็นกลไกหลักสำหรับการอ่าน Presentation ที่มีอยู่ |
| [Presentation](presentation#constructor_4)(string) | คอนสตรัคเตอร์นี้รับเส้นทางไฟล์ต้นทางที่ใช้ในการอ่านเนื้อหาของ Presentation |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | คอนสตรัคเตอร์นี้เป็นกลไกหลักสำหรับการอ่าน Presentation ที่มีอยู่ |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | คอนสตรัคเตอร์นี้รับเส้นทางไฟล์ต้นทางที่ใช้ในการอ่านเนื้อหาของ Presentation |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | ส่งคืนส่วนข้อมูลที่กำหนดเองทั้งหมดในงานนำเสนอ อ่านอย่างเดียว [`ICustomXmlPart`](../icustomxmlpart)[] |
| [Audios](../../aspose.slides/presentation/audios) { get; } | ส่งคืนคอลเลกชันของไฟล์เสียงที่ฝังอยู่ทั้งหมดในงานนำเสนอ อ่านอย่างเดียว [`IAudioCollection`](../iaudiocollection) |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | ส่งคืนคอลเลกชันของผู้เขียนคอมเมนต์ อ่านอย่างเดียว [`ICommentAuthorCollection`](../icommentauthorcollection) |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | ส่งคืนหรือกำหนดวันที่และเวลาซึ่งจะแทนเนื้อหาของฟิลด์ datetime เวลาเริ่มต้นของวัตถุ Presentation นี้โดยค่าเริ่มต้น อ่าน/เขียน DateTime |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของงานนำเสนอ อ่านอย่างเดียว [`ICustomData`](../icustomdata) |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | ส่งคืนสไตล์ข้อความเริ่มต้นสำหรับรูปทรง อ่านอย่างเดียว [`ITextStyle`](../itextstyle) |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | ส่งคืนคอลเลกชันของลายเซ็นที่ใช้ลงนามในงานนำเสนอ อ่านอย่างเดียว [`IDigitalSignatureCollection`](../idigitalsignaturecollection) |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | ส่งคืนอ็อบเจ็กต์ DocumentProperties ซึ่งมีคุณสมบัติเอกสารมาตรฐานและกำหนดเอง อ่านอย่างเดียว [`IDocumentProperties`](../idocumentproperties) |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | แสดงหมายเลขสไลด์แรกในงานนำเสนอ |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | ส่งคืนตัวจัดการฟอนต์ อ่านอย่างเดียว [`IFontsManager`](../ifontsmanager) |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | ส่งคืนตัวจัดการ HeaderFooter ปัจจุบัน อ่านอย่างเดียว [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager) |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | ให้การเข้าถึงอย่างง่ายถึงไฮเปอร์ลิงก์ทั้งหมดที่อยู่ในสไลด์ของงานนำเสนอ (ไม่รวมสไลด์มาสเตอร์, เลย์เอาต์, โน้ต) อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries) |
| [Images](../../aspose.slides/presentation/images) { get; } | ส่งคืนคอลเลกชันของภาพทั้งหมดในงานนำเสนอ อ่านอย่างเดียว [`IImageCollection`](../iimagecollection) |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | ส่งคืนรายการของสไลด์เลย์เอาต์ทั้งหมดที่กำหนดในงานนำเสนอ อ่านอย่างเดียว [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection) |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | ส่งคืนตัวจัดการ handout master อ่านอย่างเดียว [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager) |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | ส่งคืนตัวจัดการ notes master อ่านอย่างเดียว [`IMasterNotesSlideManager`](../imasternotesslidemanager) |
| [Masters](../../aspose.slides/presentation/masters) { get; } | ส่งคืนรายการของสไลด์มาสเตอร์ทั้งหมดที่กำหนดในงานนำเสนอ อ่านอย่างเดียว [`IMasterSlideCollection`](../imasterslidecollection) |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | ส่งคืนธีมมาสเตอร์ อ่านอย่างเดียว [`IMasterTheme`](../../aspose.slides.theme/imastertheme) |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | ส่งคืนอ็อบเจ็กต์ขนาดสไลด์โน้ต อ่านอย่างเดียว [`INotesSize`](../inotessize) |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | รับตัวจัดการสิทธิ์สำหรับงานนำเสนอนี้ อ่านอย่างเดียว [`IProtectionManager`](../iprotectionmanager) |
| [Sections](../../aspose.slides/presentation/sections) { get; } | ส่งคืนรายการของส่วนสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ อ่านอย่างเดียว [`ISectionCollection`](../isectioncollection) |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | ส่งคืนคอลเลกชันของป้ายกำกับความอ่อนไหวที่ใช้กับเอกสารงานนำเสนอ อ่านอย่างเดียว [`ISensitivityLabelCollection`](../isensitivitylabelcollection) |
| [Slides](../../aspose.slides/presentation/slides) { get; } | ส่งคืนรายการของสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ อ่านอย่างเดียว [`ISlideCollection`](../islidecollection) |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | ส่งคืนการตั้งค่าแสดงสไลด์โชว์สำหรับงานนำเสนอ |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | ส่งคืนอ็อบเจ็กต์ขนาดสไลด์ อ่านอย่างเดียว [`ISlideSize`](../islidesize) |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | ส่งคืนข้อมูลเกี่ยวกับรูปแบบที่โหลดงานนำเสนอมา อ่านอย่างเดียว [`SourceFormat`](../sourceformat) |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | รับหรือกำหนดโครงการ VBA ที่มีแมโครของงานนำเสนอ อ่าน/เขียน [`IVbaProject`](../../aspose.slides.vba/ivbaproject) |
| [Videos](../../aspose.slides/presentation/videos) { get; } | ส่งคืนคอลเลกชันของไฟล์วิดีโอที่ฝังอยู่ทั้งหมดในงานนำเสนอ อ่านอย่างเดียว [`IVideoCollection`](../ivideocollection) |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | รับคุณสมบัตุมุมมองทั่วทั้งงานนำเสนอ อ่านอย่างเดียว [`IViewProperties`](../iviewproperties) |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจ็กต์ Presentation นี้ |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | ส่งคืนอ็อบเจ็กต์ Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอ |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยขนาดที่ระบุ |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยการปรับสเกลที่กำหนดเอง |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยขนาดที่ระบุ |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยการปรับสเกลที่กำหนดเอง |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | ส่งคืนอ็อบเจ็กต์ Slide, MasterSlide หรือ LayoutSlide ตาม Id |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | ไฮไลท์การจับคู่ทั้งหมดของ regular expression ด้วยสีที่ระบุ |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | รวมรันที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าในรูปทรงที่ยอมรับทั้งหมดในทุกสไลด์ |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | แทนที่การจับคู่ทั้งหมดของ regular expression ด้วยสตริงที่ระบุ |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความที่ระบุอื่น |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นชุดไฟล์ที่แสดง XAML markup |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในสตรีมในรูปแบบที่ระบุ |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นไฟล์ในรูปแบบที่ระบุ |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงสตรีมในรูปแบบที่ระบุพร้อมคงหมายเลขหน้า |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงสตรีมในรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงไฟล์ในรูปแบบที่ระบุพร้อมคงหมายเลขหน้า |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงสตรีมในรูปแบบที่ระบุพร้อมคงหมายเลขหน้าและตัวเลือกเพิ่มเติม |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงไฟล์ในรูปแบบที่ระบุพร้อมคงหมายเลขหน้าและตัวเลือกเพิ่มเติม |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการสร้าง PowerPoint Presentation

```csharp
[C#]
// สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
using (Presentation presentation = new Presentation())
{
    // ดึงสไลด์แรก
    ISlide slide = presentation.Slides[0];
    // เพิ่มรูปร่างอัตโนมัติประเภทเส้น
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// บันทึกไฟล์งานนำเสนอ.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีการเปิดและบันทึก Presentation

```csharp
[C#]
// โหลดไฟล์ที่รองรับทั้งหมดใน Presentation เช่น ppt, pptx, odp เป็นต้น
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// บันทึกไฟล์งานนำเสนอ.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IPresentation](../ipresentation)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->