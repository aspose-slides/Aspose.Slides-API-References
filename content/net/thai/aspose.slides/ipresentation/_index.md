---
title: IPresentation
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: เอกสารการนำเสนอ
type: docs
weight: 6770
url: /th/aspose.slides/ipresentation/
---
## IPresentation อินเทอร์เฟซ

Presentation document

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | ส่งคืนส่วนข้อมูลที่กำหนดเองทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | ส่งคืนอินเทอร์เฟซ IDisposable. อ่านอย่างเดียว IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซ IPresentationComponent พื้นฐาน. อ่านอย่างเดียว [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | ส่งคืนคอลเลกชันของไฟล์เสียงแบบฝังทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | ส่งคืนคอลเลกชันของผู้เขียนความคิดเห็น. อ่านอย่างเดียว [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | ส่งคืนหรือกำหนดวันและเวลาที่จะแทนที่เนื้อหาของฟิลด์ datetime. เวลาในการสร้างออบเจกต์ Presentation นี้โดยค่าเริ่มต้น. อ่าน/เขียน DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | ส่งคืนข้อมูลที่กำหนดเองของงานนำเสนอ. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | ส่งคืนสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | ส่งคืนคอลเลกชันของลายเซ็นที่ใช้ในการลงนามงานนำเสนอ. อ่านอย่างเดียว [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | ส่งคืนอ็อบเจกต์ DocumentProperties ซึ่งมีคุณลักษณะเอกสารมาตรฐานและกำหนดเอง. อ่านอย่างเดียว [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | แทนหมายเลขสไลด์แรกในงานนำเสนอ. อ่าน/เขียน Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | ส่งคืนผู้จัดการแบบอักษร. อ่านอย่างเดียว [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | ส่งคืนผู้จัดการ HeaderFooter ของงานนำเสนอ. อ่านอย่างเดียว [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | ให้การเข้าถึงง่ายต่อไฮเปอร์ลิงก์ทั้งหมดที่อยู่ในสไลด์งานนำเสนอทั้งหมด (ไม่รวมมาสเตอร์, เลย์เอาต์, สไลด์บันทึก). อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | ส่งคืนคอลเลกชันของรูปภาพทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | ส่งคืนรายการของสไลด์เลย์เอาต์ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | ส่งคืนผู้จัดการ handout master. อ่านอย่างเดียว [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | ส่งคืนผู้จัดการ notes master. อ่านอย่างเดียว [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | ส่งคืนรายการของสไลด์มาสเตอร์ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | ส่งคืนธีมมาสเตอร์ของงานนำเสนอ. อ่านอย่างเดียว [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | ส่งคืนอ็อบเจกต์ขนาดสไลด์บันทึก. อ่านอย่างเดียว [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | รับผู้จัดการสิทธิ์สำหรับงานนำเสนอนี้. อ่านอย่างเดียว [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | ส่งคืนรายการของส่วนสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | ส่งคืนคอลเลกชันของป้ายความไวที่ใช้กับเอกสารงานนำเสนอ. อ่านอย่างเดียว [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | ส่งคืนรายการของสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ. อ่านอย่างเดียว [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | ส่งคืนอ็อบเจกต์ขนาดสไลด์. อ่านอย่างเดียว [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | ส่งคืนข้อมูลเกี่ยวกับว่าไฟล์งานนำเสนอถูกโหลดจากรูปแบบใด. อ่านอย่างเดียว [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | รับโครงการ VBA ที่มีแมโครของงานนำเสนอ. อ่าน/เขียน [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | ส่งคืนคอลเลกชันของไฟล์วิดีโอแบบฝังทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | รับคุณสมบัติมุมมองทั่วงานนำเสนอ. อ่านอย่างเดียว [`IViewProperties`](../iviewproperties). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | ส่งคืนอ็อบเจกต์ Thumbnail Bitmap สำหรับสไลด์ที่ระบุของงานนำเสนอ. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยขนาดที่ระบุ. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอโดยใช้การสเกลที่กำหนดเอง. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยขนาดที่ระบุ. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอโดยใช้การสเกลที่กำหนดเอง. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | ส่งคืน Slide, MasterSlide หรือ LayoutSlide ตาม Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | เน้นส่วนที่ตรงกับ regular expression ทั้งหมดด้วยสีที่ระบุ. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | เน้นส่วนที่ตรงกับข้อความตัวอย่างทั้งหมดด้วยสีที่ระบุ. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | เน้นส่วนที่ตรงกับข้อความตัวอย่างทั้งหมดด้วยสีที่ระบุ. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | รวม run ที่มีรูปแบบเดียวกันในย่อหน้าทั้งหมดในรูปร่างที่ยอมรับได้ทั้งหมดในสไลด์ทั้งหมด. |
| [RefreshChartsData](../../aspose.slides/ipresentation/refreshchartsdata)(bool) | โหลดข้อมูลของแผนภูมิทั้งหมดในงานนำเสนอใหม่จากแหล่ง workbook ของพวกมัน. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | แทนที่ส่วนที่ตรงกับ regular expression ทั้งหมดด้วยสตริงที่ระบุ. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | แทนที่ตำแหน่งที่พบของข้อความที่ระบุทั้งหมดด้วยข้อความที่ระบุอื่น. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นชุดไฟล์ที่เป็น XAML markup. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในสตรีมในรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงในสตรีมในรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในสตรีมในรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุและด้วยตัวเลือกเพิ่มเติม. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงในสตรีมในรูปแบบที่ระบุ. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงในไฟล์ด้วยรูปแบบที่ระบุ. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IPresentationComponent](../ipresentationcomponent)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซ็มบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->