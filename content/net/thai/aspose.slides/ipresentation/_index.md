---
title: IPresentation
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: เอกสารการนำเสนอ
type: docs
weight: 6750
url: /th/aspose.slides/ipresentation/
---
## IPresentation อินเทอร์เฟซ

Presentation document

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## คุณสมบัติ

| ชื่อ | รายละเอียด |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | ส่งคืนส่วนข้อมูลที่กำหนดเองทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | ส่งคืนอินเทอร์เฟซ IDisposable. อ่านอย่างเดียว IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซ IPresentationComponent พื้นฐาน. อ่านอย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | ส่งคืนชุดของไฟล์เสียงที่ฝังทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | ส่งคืนชุดของผู้เขียนความคิดเห็น. อ่านอย่างเดียว [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | ส่งคืนหรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาของฟิลด์ datetime. เวลาที่สร้างวัตถุ Presentation นี้เป็นค่าเริ่มต้น. อ่าน/เขียน DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของงานนำเสนอ. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | ส่งคืนสไตล์ข้อความเริ่มต้นสำหรับรูปทรง. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | ส่งคืนชุดของลายเซ็นที่ใช้ในการลงนามงานนำเสนอ. อ่านอย่างเดียว [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | ส่งคืนอ็อบเจ็กต์ DocumentProperties ที่มีคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร. อ่านอย่างเดียว [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | แสดงหมายเลขสไลด์แรกในงานนำเสนอ. อ่าน/เขียน Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | ส่งคืนตัวจัดการแบบอักษร. อ่านอย่างเดียว [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | ส่งคืนตัวจัดการ HeaderFooter ของงานนำเสนอ. อ่านอย่างเดียว [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | ให้การเข้าถึงลิงก์ทั้งหมดที่อยู่ในสไลด์งานนำเสนอทั้งหมด (ไม่รวมสไลด์แม่แบบ, Layout, Notes). อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | ส่งคืนชุดของภาพทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | ส่งคืนรายการสไลด์ Layout ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | ส่งคืนตัวจัดการ Handout Master. อ่านอย่างเดียว [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | ส่งคืนตัวจัดการ Notes Master. อ่านอย่างเดียว [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | ส่งคืนรายการ Master Slide ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | ส่งคืนธีมแม่ของงานนำเสนอ. อ่านอย่างเดียว [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | ส่งคืนอ็อบเจ็กต์ขนาดสไลด์ Notes. อ่านอย่างเดียว [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | รับตัวจัดการสิทธิ์สำหรับงานนำเสนอนี้. อ่านอย่างเดียว [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | ส่งคืนรายการส่วนของสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | ส่งคืนชุดของป้ายความอ่อนไหวที่ใช้กับเอกสารงานนำเสนอ. อ่านอย่างเดียว [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | ส่งคืนรายการสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | ส่งคืนอ็อบเจ็กต์ขนาดสไลด์. อ่านอย่างเดียว [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | ส่งคืนข้อมูลเกี่ยวกับรูปแบบที่โหลดงานนำเสนอ. อ่านอย่างเดียว [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | รับโปรเจกต์ VBA พร้อมมาโครของงานนำเสนอ. อ่าน/เขียน [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | ส่งคืนชุดของไฟล์วิดีโอที่ฝังทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | รับคุณสมบัติมุมมองทั่วงานนำเสนอ. อ่านอย่างเดียว [`IViewProperties`](../iviewproperties). |

## เมธอด

| ชื่อ | รายละเอียด |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | ส่งคืนอ็อบเจ็กต์ Thumbnail Bitmap สำหรับสไลด์ที่ระบุของงานนำเสนอ. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยขนาดที่ระบุ. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอโดยกำหนดสเกลแบบกำหนดเอง. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยขนาดที่ระบุ. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอโดยกำหนดสเกลแบบกำหนดเอง. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | ส่งคืน Slide, MasterSlide หรือ LayoutSlide ตาม Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | ไฮไลท์การจับคู่ทั้งหมดของ regular expression ด้วยสีที่ระบุ. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | ไฮไลท์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | รวมรันที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมดในรูปทรงที่ยอมรับได้ทั้งหมดในสไลด์ทั้งหมด. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | แทนที่การจับคู่ทั้งหมดของ regular expression ด้วยสตริงที่ระบุ. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นชุดไฟล์ที่เป็น XAML markup. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงสตรีมในรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงไฟล์ด้วยรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงสตรีมในรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงสตรีมในรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงไฟล์ด้วยรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงไฟล์ด้วยรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงสตรีมในรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงไฟล์ด้วยรูปแบบที่ระบุ. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IPresentationComponent](../ipresentationcomponent)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->