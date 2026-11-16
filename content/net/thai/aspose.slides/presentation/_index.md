---
title: Presentation
second_title: อ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: เป็นตัวแทนของ Microsoft PowerPoint presentation.
type: docs
weight: 9610
url: /th/aspose.slides/presentation/
---
## Presentation คลาส

เป็นตัวแทนของ Microsoft PowerPoint Presentation.

```csharp
public sealed class Presentation : IPresentation
```

## คอนสตรักเตอร์

| Name | Description |
| --- | --- |
| [Presentation](presentation#constructor)() | คอนสตรักเตอร์นี้สร้าง Presentation ใหม่จากศูนย์. Presentation ที่สร้างมีสไลด์เปล่า 1 แผ่น. |
| [Presentation](presentation#constructor_1)(LoadOptions) | คอนสตรักเตอร์นี้สร้าง Presentation ใหม่จากศูนย์. Presentation ที่สร้างมีสไลด์เปล่า 1 แผ่น. |
| [Presentation](presentation#constructor_2)(Stream) | คอนสตรักเตอร์นี้เป็นกลไกหลักสำหรับการอ่าน Presentation ที่มีอยู่. |
| [Presentation](presentation#constructor_4)(string) | คอนสตรักเตอร์นี้รับเส้นทางไฟล์ต้นทางที่ใช้ในการอ่านเนื้อหาของ Presentation. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | คอนสตรักเตอร์นี้เป็นกลไกหลักสำหรับการอ่าน Presentation ที่มีอยู่. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | คอนสตรักเตอร์นี้รับเส้นทางไฟล์ต้นทางที่ใช้ในการอ่านเนื้อหาของ Presentation. |

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | ส่งคืนส่วนข้อมูล custom ทั้งหมดใน Presentation. อ่านอย่างเดียว [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | ส่งคืนคอลเลกชันของไฟล์เสียงที่ฝังอยู่ทั้งหมดใน Presentation. อ่านอย่างเดียว [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | ส่งคืนคอลเลกชันของผู้เขียนความคิดเห็น. อ่านอย่างเดียว [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | ส่งคืนหรือกำหนดวันและเวลา ที่จะใช้แทนเนื้อหาของฟิลด์ datetime. ค่าเริ่มต้นคือเวลาที่สร้างวัตถุ Presentation นี้. อ่าน/เขียน DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | ส่งคืนข้อมูล custom ของ Presentation. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | ส่งคืนรูปแบบข้อความเริ่มต้นสำหรับ shapes. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | ส่งคืนคอลเลกชันของลายเซ็นที่ใช้ในการลงนาม Presentation. อ่านอย่างเดียว [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | ส่งคืนอ็อบเจ็กต์ DocumentProperties ซึ่งบรรจุคุณสมบัติมาตรฐานและ custom ของเอกสาร. อ่านอย่างเดียว [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | แสดงหมายเลขสไลด์แรกใน Presentation |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | ส่งคืนตัวจัดการฟอนต์. อ่านอย่างเดียว [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | ส่งคืนตัวจัดการ HeaderFooter ที่ใช้งานจริง. อ่านอย่างเดียว [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | ให้การเข้าถึงง่ายต่อ hyperlinks ทั้งหมดที่อยู่ในสไลด์ของ Presentation (ไม่รวมสไลด์ master, layout, notes). อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | ส่งคืนคอลเลกชันของรูปภาพทั้งหมดใน Presentation. อ่านอย่างเดียว [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | ส่งคืนรายการของสไลด์ layout ทั้งหมดที่กำหนดใน Presentation. อ่านอย่างเดียว [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | ส่งคืนตัวจัดการ handout master. อ่านอย่างเดียว [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | ส่งคืนตัวจัดการ notes master. อ่านอย่างเดียว [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | ส่งคืนรายการของสไลด์ master ทั้งหมดที่กำหนดใน Presentation. อ่านอย่างเดียว [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | ส่งคืน master theme. อ่านอย่างเดียว [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | ส่งคืนอ็อบเจ็กต์ขนาดสไลด์ notes. อ่านอย่างเดียว [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | รับตัวจัดการสิทธิ์ของ Presentation นี้. อ่านอย่างเดียว [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | ส่งคืนรายการของส่วนสไลด์ทั้งหมดที่กำหนดใน Presentation. อ่านอย่างเดียว [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | ส่งคืนคอลเลกชันของป้ายกำกับความสำคัญ (sensitivity labels) ที่ใช้กับเอกสาร Presentation. อ่านอย่างเดียว [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | ส่งคืนรายการของสไลด์ทั้งหมดที่กำหนดใน Presentation. อ่านอย่างเดียว [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | ส่งคืนการตั้งค่า slide show ของ Presentation. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | ส่งคืนอ็อบเจ็กต์ขนาดสไลด์.อ่านอย่างเดียว [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | ส่งคืนข้อมูลเกี่ยวกับรูปแบบที่ Presentation ถูกโหลดจาก. อ่านอย่างเดียว [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | รับหรือกำหนดโครงการ VBA ที่มีมาโครของ Presentation. อ่าน/เขียน [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | ส่งคืนคอลเลกชันของไฟล์วิดีโอที่ฝังอยู่ทั้งหมดใน Presentation. อ่านอย่างเดียว [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | รับคุณสมบัติมุมมองทั่วไประดับ Presentation. อ่านอย่างเดียว [`IViewProperties`](../iviewproperties). |

## เมธอด

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจ็กต์ Presentation นี้. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | ส่งคืนอ็อบเจ็กต์ Image สำหรับสไลด์ทั้งหมดของ Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของ Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของ Presentation ด้วยขนาดที่กำหนด. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของ Presentation ด้วยการสเกลแบบกำหนดเอง. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของ Presentation ด้วยขนาดที่กำหนด. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของ Presentation ด้วยการสเกลแบบกำหนดเอง. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | ส่งคืน Slide, MasterSlide หรือ LayoutSlide ตาม Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | ไฮไลท์การจับคู่ทั้งหมดของ regular expression ด้วยสีที่ระบุ. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | รวม run ที่มีรูปแบบเดียวกันในทุกพารากราฟของ shape ที่รับได้ทั้งหมดในทุกสไลด์. |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | รีโหลดข้อมูลสำหรับแผนภูมิทั้งหมดใน Presentation จาก workbook ต้นทางของพวกมัน. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | แทนที่การจับคู่ทั้งหมดของ regular expression ด้วยสตริงที่ระบุ. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความที่ระบุอื่น. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | บันทึกสไลด์ทั้งหมดของ Presentation เป็นชุดไฟล์ที่เป็น XAML markup. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | บันทึกสไลด์ทั้งหมดของ Presentation ไปยัง stream ในรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | บันทึกสไลด์ทั้งหมดของ Presentation ไปยังไฟล์ด้วยรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของ Presentation ไปยัง stream ในรูปแบบที่ระบุโดยคงหมายเลขหน้า. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | บันทึกสไลด์ทั้งหมดของ Presentation ไปยัง stream ในรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของ Presentation ไปยังไฟล์ด้วยรูปแบบที่ระบุโดยคงหมายเลขหน้า. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของ Presentation ไปยัง stream ในรูปแบบที่ระบุโดยคงหมายเลขหน้าและตัวเลือกเพิ่มเติม. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของ Presentation ไปยังไฟล์ด้วยรูปแบบที่ระบุโดยคงหมายเลขหน้าและตัวเลือกเพิ่มเติม. |

### ตัวอย่าง

ตัวอย่างต่อไปนี้แสดงวิธีสร้าง PowerPoint Presentation.

```csharp
[C#]
// สร้างอ็อบเจ็กต์ Presentation ที่แสดงถึงไฟล์พรีเซนเทชัน
using (Presentation presentation = new Presentation())
{
    // ดึงสไลด์แรก
    ISlide slide = presentation.Slides[0];
    // เพิ่ม autoshape ประเภทเส้น
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// บันทึกไฟล์พรีเซนเทชัน.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

ตัวอย่างต่อไปนี้แสดงวิธีเปิดและบันทึก Presentation.

```csharp
[C#]
// โหลดไฟล์ที่รองรับทั้งหมดใน Presentation เช่น ppt, pptx, odp เป็นต้น
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// บันทึกไฟล์พรีเซนเทชัน.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IPresentation](../ipresentation)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->