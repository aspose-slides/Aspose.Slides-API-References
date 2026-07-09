---
title: Presentation
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: เป็นการนำเสนอ Microsoft PowerPoint.
type: docs
weight: 9590
url: /th/aspose.slides/presentation/
---
## คลาส Presentation

แสดงการนำเสนอ Microsoft PowerPoint

```csharp
public sealed class Presentation : IPresentation
```

## คอนสตรักเตอร์

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Presentation](presentation#constructor)() | คอนสตรักเตอร์นี้สร้างการนำเสนอใหม่จากศูนย์. การนำเสนอที่สร้างมีสไลด์เปล่า 1 แผ่น |
| [Presentation](presentation#constructor_1)(LoadOptions) | คอนสตรักเตอร์นี้สร้างการนำเสนอใหม่จากศูนย์. การนำเสนอที่สร้างมีสไลด์เปล่า 1 แผ่น |
| [Presentation](presentation#constructor_2)(Stream) | คอนสตรักเตอร์นี้เป็นกลไกหลักสำหรับการอ่าน Presentation ที่มีอยู่แล้ว |
| [Presentation](presentation#constructor_4)(string) | คอนสตรักเตอร์นี้รับเส้นทางไฟล์ต้นฉบับที่ใช้ในการอ่านเนื้อหาของ Presentation |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | คอนสตรักเตอร์นี้เป็นกลไกหลักสำหรับการอ่าน Presentation ที่มีอยู่แล้ว |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | คอนสตรักเตอร์นี้รับเส้นทางไฟล์ต้นฉบับที่ใช้ในการอ่านเนื้อหาของ Presentation |

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | คืนค่าทุกส่วนข้อมูลกำหนดเองในการนำเสนอ. อ่านอย่างเดียว [`ICustomXmlPart`](../icustomxmlpart)[] |
| [Audios](../../aspose.slides/presentation/audios) { get; } | คืนค่าชุดของไฟล์เสียงที่ฝังอยู่ทั้งหมดในการนำเสนอ. อ่านอย่างเดียว [`IAudioCollection`](../iaudiocollection) |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | คืนค่าชุดของผู้ส่งความคิดเห็น. อ่านอย่างเดียว [`ICommentAuthorCollection`](../icommentauthorcollection) |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | คืนค่าหรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาของฟิลด์ datetime. โดยค่าเริ่มต้นเป็นเวลาที่สร้างวัตถุ Presentation นี้. อ่าน/เขียน DateTime |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของการนำเสนอ. อ่านอย่างเดียว [`ICustomData`](../icustomdata) |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | คืนค่าสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง. อ่านอย่างเดียว [`ITextStyle`](../itextstyle) |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | คืนค่าชุดลายเซ็นที่ใช้ในการลงนามการนำเสนอ. อ่านอย่างเดียว [`IDigitalSignatureCollection`](../idigitalsignaturecollection) |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | คืนค่าอ็อบเจ็กต์ DocumentProperties ที่มีคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร. อ่านอย่างเดียว [`IDocumentProperties`](../idocumentproperties) |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | แสดงหมายเลขสไลด์แรกในการนำเสนอ |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | คืนค่าผู้จัดการแบบอักษร. อ่านอย่างเดียว [`IFontsManager`](../ifontsmanager) |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | คืนค่าผู้จัดการ HeaderFooter จริง. อ่านอย่างเดียว [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager) |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | ให้การเข้าถึงง่ายต่อไฮเปอร์ลิงก์ทั้งหมดที่อยู่ในสไลด์ของการนำเสนอ (ไม่รวมสไลด์มาสเตอร์, เลย์เอาต์, โน้ต). อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries) |
| [Images](../../aspose.slides/presentation/images) { get; } | คืนค่าชุดของรูปภาพทั้งหมดในการนำเสนอ. อ่านอย่างเดียว [`IImageCollection`](../iimagecollection) |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | คืนค่ารายการของสไลด์เลย์เอาต์ทั้งหมดที่กำหนดในการนำเสนอ. อ่านอย่างเดียว [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection) |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | คืนค่าผู้จัดการ handout master. อ่านอย่างเดียว [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager) |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | คืนค่าผู้จัดการ notes master. อ่านอย่างเดียว [`IMasterNotesSlideManager`](../imasternotesslidemanager) |
| [Masters](../../aspose.slides/presentation/masters) { get; } | คืนค่ารายการของสไลด์มาสเตอร์ทั้งหมดที่กำหนดในการนำเสนอ. อ่านอย่างเดียว [`IMasterSlideCollection`](../imasterslidecollection) |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | คืนค่าธีมมาสเตอร์. อ่านอย่างเดียว [`IMasterTheme`](../../aspose.slides.theme/imastertheme) |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | คืนค่าอ็อบเจ็กต์ขนาดสไลด์โน้ต. อ่านอย่างเดียว [`INotesSize`](../inotessize) |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | รับผู้จัดการสิทธิ์สำหรับการนำเสนอนี้. อ่านอย่างเดียว [`IProtectionManager`](../iprotectionmanager) |
| [Sections](../../aspose.slides/presentation/sections) { get; } | คืนค่ารายการของส่วนสไลด์ทั้งหมดที่กำหนดในการนำเสนอ. อ่านอย่างเดียว [`ISectionCollection`](../isectioncollection) |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | คืนค่าชุดของป้ายกำกับความอ่อนไหวที่ใช้กับเอกสารการนำเสนอ. อ่านอย่างเดียว [`ISensitivityLabelCollection`](../isensitivitylabelcollection) |
| [Slides](../../aspose.slides/presentation/slides) { get; } | คืนค่ารายการของสไลด์ทั้งหมดที่กำหนดในการนำเสนอ. อ่านอย่างเดียว [`ISlideCollection`](../islidecollection) |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | คืนค่าการตั้งค่าสไลด์โชว์สำหรับการนำเสนอ |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | คืนค่าอ็อบเจ็กต์ขนาดสไลด์. อ่านอย่างเดียว [`ISlideSize`](../islidesize) |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | คืนข้อมูลเกี่ยวกับฟอร์แมตที่การนำเข้าถูกโหลดมา. อ่านอย่างเดียว [`SourceFormat`](../sourceformat) |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | รับหรือกำหนดโปรเจกต์ VBA ที่มีมาโครของการนำเสนอ. อ่าน/เขียน [`IVbaProject`](../../aspose.slides.vba/ivbaproject) |
| [Videos](../../aspose.slides/presentation/videos) { get; } | คืนค่าชุดของไฟล์วิดีโอที่ฝังอยู่ทั้งหมดในการนำเสนอ. อ่านอย่างเดียว [`IVideoCollection`](../ivideocollection) |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | รับคุณสมบัติมุมมองทั่วการนำเสนอ. อ่านอย่างเดียว [`IViewProperties`](../iviewproperties) |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจ็กต์ Presentation นี้ |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | คืนค่าอ็อบเจ็กต์ Image สำหรับสไลด์ทั้งหมดของการนำเสนอ |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอ |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยขนาดที่ระบุ |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยการปรับขนาดที่กำหนดเอง |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยขนาดที่ระบุ |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยการปรับขนาดที่กำหนดเอง |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | คืนค่า Slide, MasterSlide หรือ LayoutSlide ตาม Id |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | เน้นทั้งหมดที่ตรงกับ regular expression ด้วยสีที่ระบุ |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | เน้นทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | เน้นทั้งหมดที่ตรงกับข้อความตัวอย่างด้วยสีที่ระบุ |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | รวม runs ที่มีรูปแบบเดียวกันในทุกย่อหน้าในรูปร่างที่ยอมรับทั้งหมดในทุกสไลด์ |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | แทนที่ทั้งหมดที่ตรงกับ regular expression ด้วยสตริงที่ระบุ |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | แทนที่ทั้งหมดของข้อความที่ระบุด้วยข้อความที่ระบุอื่น |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นชุดไฟล์ที่เป็น XAML markup |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | บันทึกสไลด์ทั้งหมดของการนำเสนอเข้าสู่สตรีมในรูปแบบที่ระบุ |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุ |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของการนำเข้าสู่สตรีมในรูปแบบที่ระบุโดยรักษาเลขหน้า |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | บันทึกสไลด์ทั้งหมดของการนำเสนอเข้าสู่สตรีมในรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุโดยรักษาเลขหน้า |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของการนำเข้าสู่สตรีมในรูปแบบที่ระบุโดยรักษาเลขหน้า |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของการนำเสนอเป็นไฟล์ด้วยรูปแบบที่ระบุโดยรักษาเลขหน้า |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีการสร้าง PowerPoint Presentation.

```csharp
[C#]
// สร้างอ็อบเจ็กต์ Presentation ที่แทนไฟล์การนำเสนอ
using (Presentation presentation = new Presentation())
{
    // รับสไลด์แรก
    ISlide slide = presentation.Slides[0];
    // เพิ่มรูปอัตโนมัติประเภทเส้น
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// บันทึกไฟล์การนำเสนอ
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีการเปิดและบันทึก Presentation.

```csharp
[C#]
// โหลดไฟล์ที่รองรับทั้งหมดใน Presentation เช่น ppt, pptx, odp เป็นต้น
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// บันทึกไฟล์การนำเสนอ
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### รายการที่เกี่ยวข้อง

* อินเทอร์เฟซ [IPresentation](../ipresentation)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->