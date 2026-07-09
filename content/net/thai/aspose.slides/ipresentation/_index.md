---
title: IPresentation
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
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

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | ส่งคืนส่วนข้อมูลที่กำหนดเองทั้งหมดใน presentation. อ่านอย่างเดียว [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | ส่งคืนอินเทอร์เฟซ IDisposable. อ่านอย่างเดียว IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซฐาน IPresentationComponent. อ่านอย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | ส่งคืนคอลเลกชันของไฟล์เสียงที่ฝังอยู่ทั้งหมดใน presentation. อ่านอย่างเดียว [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | ส่งคืนคอลเลกชันของผู้เขียนความคิดเห็น. อ่านอย่างเดียว [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | ส่งคืนหรือกำหนดวันที่และเวลาที่จะทดแทนเนื้อหาของฟิลด์ datetime. เวลาการสร้างออบเจ็กต์ Presentation นี้โดยค่าเริ่มต้น. อ่าน/เขียน DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | ส่งคืนข้อมูลที่กำหนดเองของ presentation. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | ส่งคืนสไตล์ข้อความเริ่มต้นสำหรับ shape. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | ส่งคืนคอลเลกชันของลายเซ็นที่ใช้เพื่อเซ็น presentation. อ่านอย่างเดียว [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | ส่งคืนอ็อบเจ็กต์ DocumentProperties ซึ่งมีคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร. อ่านอย่างเดียว [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | แสดงหมายเลขสไลด์แรกใน presentation. อ่าน/เขียน Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | ส่งคืนตัวจัดการฟอนต์. อ่านอย่างเดียว [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | ส่งคืนตัวจัดการ HeaderFooter ของ presentation. อ่านอย่างเดียว [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | ให้การเข้าถึงง่ายต่อไฮเปอร์ลิงก์ทั้งหมดที่อยู่ในสไลด์ของ presentation (ไม่รวมมาสเตอร์, เลย์เอาต์, โน้ต). อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | ส่งคืนคอลเลกชันของรูปภาพทั้งหมดใน presentation. อ่านอย่างเดียว [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | ส่งคืนรายการของสไลด์เลย์เอาต์ที่กำหนดไว้ใน presentation. อ่านอย่างเดียว [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | ส่งคืนตัวจัดการ handout master. อ่านอย่างเดียว [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | ส่งคืนตัวจัดการ notes master. อ่านอย่างเดียว [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | ส่งคืนรายการของสไลด์มาสเตอร์ที่กำหนดไว้ใน presentation. อ่านอย่างเดียว [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | ส่งคืนธีมมาสเตอร์ของ presentation. อ่านอย่างเดียว [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | ส่งคืนอ็อบเจ็กต์ขนาดสไลด์โน้ต. อ่านอย่างเดียว [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | รับตัวจัดการสิทธิ์ของ presentation นี้. อ่านอย่างเดียว [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | ส่งคืนรายการของส่วนสไลด์ทั้งหมดที่กำหนดไว้ใน presentation. อ่านอย่างเดียว [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | ส่งคืนคอลเลกชันของป้ายความอ่อนไหวที่ใช้กับเอกสาร presentation. อ่านอย่างเดียว [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | ส่งคืนรายการของสไลด์ทั้งหมดที่กำหนดไว้ใน presentation. อ่านอย่างเดียว [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | ส่งคืนอ็อบเจ็กต์ขนาดสไลด์. อ่านอย่างเดียว [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | ส่งคืนข้อมูลเกี่ยวกับรูปแบบที่ใช้ในการโหลด presentation. อ่านอย่างเดียว [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | รับโครงการ VBA ที่มีมาโครของ presentation. อ่าน/เขียน [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | ส่งคืนคอลเลกชันของไฟล์วิดีโอที่ฝังอยู่ทั้งหมดใน presentation. อ่านอย่างเดียว [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | รับคุณสมบัติดูการนำเสนอทั้งหมด. อ่านอย่างเดียว [`IViewProperties`](../iviewproperties). |

## วิธีการ

| Name | Description |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของ presentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | ส่งคืนอ็อบเจ็กต์ Thumbnail Bitmap สำหรับสไลด์ที่ระบุของ presentation. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของ presentation ด้วยขนาดที่ระบุ. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของ presentation ด้วยการสเกลที่กำหนดเอง. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของ presentation ด้วยขนาดที่ระบุ. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของ presentation ด้วยการสเกลที่กำหนดเอง. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | ส่งคืน Slide, MasterSlide หรือ LayoutSlide ตาม Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | ไฮไลท์ทุกการจับคู่ของ regular expression ด้วยสีที่ระบุ. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | ไฮไลท์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | ไฮไลท์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | ผสาน run ที่มีรูปแบบเดียวกันในทุก paragraph ของ shape ที่รับได้ทั้งหมดในทุกสไลด์. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | แทนที่ทุกการจับคู่ของ regular expression ด้วยสตริงที่ระบุ. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | แทนที่ทุกตำแหน่งของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | บันทึกสไลด์ทั้งหมดของ presentation เป็นชุดไฟล์ที่เป็น XAML markup. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | บันทึกสไลด์ทั้งหมดของ presentation ลงสตรีมในรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | บันทึกสไลด์ทั้งหมดของ presentation ลงไฟล์ด้วยรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของ presentation ลงสตรีมในรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | บันทึกสไลด์ทั้งหมดของ presentation ลงสตรีมในรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของ presentation ลงไฟล์ด้วยรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | บันทึกสไลด์ทั้งหมดของ presentation ลงไฟล์ด้วยรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของ presentation ลงสตรีมในรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของ presentation ลงไฟล์ด้วยรูปแบบที่ระบุ. |

### ดูเพิ่มเติม

* interface [IPresentationComponent](../ipresentationcomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->