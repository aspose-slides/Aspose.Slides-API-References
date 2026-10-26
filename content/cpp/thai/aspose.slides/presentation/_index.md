---
title: Presentation
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เป็นงานนำเสนอ Microsoft PowerPoint.
type: docs
weight: 4837
url: /th/aspose.slides/presentation/
---
## คลาส Presentation

Represents a Microsoft PowerPoint presentation.

```cpp
class Presentation : public Aspose::Slides::IPresentation,
                     public Aspose::Slides::IDOMObject
```

## เมธอด

| Method | Description |
| --- | --- |
| void [Dispose](./dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจ็กต์ [Presentation](./) นี้. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICustomXmlPart](../icustomxmlpart/)\>\> [get_AllCustomXmlParts](./get_allcustomxmlparts/)() override | ส่งคืนส่วนข้อมูลกำหนดเองทั้งหมดในงานนำเสนอ อ่านอย่างเดียว [ICustomXmlPart](../icustomxmlpart/)[]. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Audio](./get_audio/)(**int32_t**) override | ส่งคืนไฟล์เสียงที่ฝังในงานนำเสนอที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [Aspose::Slides::IAudio](../iaudio/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioCollection](../iaudiocollection/)\> [get_Audios](./get_audios/)() override | ส่งคืนคอลเลกชันของไฟล์เสียงที่ฝังทั้งหมดในงานนำเสนอ อ่านอย่างเดียว [IAudioCollection](../iaudiocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_CommentAuthor](./get_commentauthor/)(**int32_t**) override | ส่งคืนผู้เขียนความคิดเห็นที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [Aspose::Slides::ICommentAuthor](../icommentauthor/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthorCollection](../icommentauthorcollection/)\> [get_CommentAuthors](./get_commentauthors/)() override | ส่งคืนคอลเลกชันของผู้เขียนความคิดเห็น อ่านอย่างเดียว [ICommentAuthorCollection](../icommentauthorcollection/). |
| [System::DateTime](../../system/datetime/) [get_CurrentDateTime](./get_currentdatetime/)() override | ส่งคืนวันที่และเวลา ที่จะทดแทนเนื้อหาของฟิลด์วันที่และเวลา เวลาการสร้างอ็อบเจ็กต์ [Presentation](./) นี้โดยค่าเริ่มต้น อ่าน [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | ส่งคืนข้อมูลกำหนดเองของงานนำเสนอ อ่านอย่างเดียว [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_DefaultTextStyle](./get_defaulttextstyle/)() override | ส่งคืนสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง อ่านอย่างเดียว [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignature](../idigitalsignature/)\> [get_DigitalSignature](./get_digitalsignature/)(**int32_t**) override | ส่งคืนลายเซ็นดิจิตอลที่ใช้ในการลงนามงานนำเสนอที่ตำแหน่งที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignatureCollection](../idigitalsignaturecollection/)\> [get_DigitalSignatures](./get_digitalsignatures/)() override | ส่งคืนคอลเลกชันของลายเซ็นที่ใช้ในการลงนามงานนำเสนอ อ่านอย่างเดียว [IDigitalSignatureCollection](../idigitalsignaturecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [get_DocumentProperties](./get_documentproperties/)() override | ส่งคืนอ็อบเจ็กต์ [DocumentProperties](../documentproperties/) ที่มีคุณสมบัติเอกสารมาตรฐานและกำหนดเอง อ่านอย่างเดียว [IDocumentProperties](../idocumentproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_DocumentProperty](./get_documentproperty/)([System::String](../../system/string/)) override | ส่งคืนคุณสมบัติกำหนดเองที่กำหนดโดยชื่อ. |
| **int32_t** [get_FirstSlideNumber](./get_firstslidenumber/)() override | แสดงหมายเลขสไลด์แรกในงานนำเสนอ |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontsManager](../ifontsmanager/)\> [get_FontsManager](./get_fontsmanager/)() override | ส่งคืนตัวจัดการฟอนต์ อ่านอย่างเดียว [IFontsManager](../ifontsmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | ส่งคืนตัวจัดการ HeaderFooter จริง อ่านอย่างเดียว [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | ให้การเข้าถึงลิงก์ทั้งหมดที่อยู่ในสไลด์ของงานนำเสนอ (ไม่รวมสไลด์มาสเตอร์, layout, notes) อย่างง่าย อ่านอย่างเดียว [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)(**int32_t**) override | ส่งคืนภาพในงานนำเสนอที่ตำแหน่งที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImageCollection](../iimagecollection/)\> [get_Images](./get_images/)() override | ส่งคืนคอลเลกชันของภาพทั้งหมดในงานนำเสนอ อ่านอย่างเดียว [IImageCollection](../iimagecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | ส่งคืนสไลด์เลเอาต์ตามตำแหน่ง อ่านอย่างเดียว [Aspose::Slides::ILayoutSlide](../ilayoutslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | ส่งคืนรายการของสไลด์เลเอาต์ทั้งหมดที่กำหนดในงานนำเสนอ อ่านอย่างเดียว [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_Master](./get_master/)(**int32_t**) override | ส่งคืนสไลด์มาสเตอร์ที่กำหนดในงานนำเสนอที่ตำแหน่งที่ระบุอ่านอย่างเดียว [Aspose::Slides::IMasterSlide](../imasterslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideManager](../imasterhandoutslidemanager/)\> [get_MasterHandoutSlideManager](./get_masterhandoutslidemanager/)() override | ส่งคืนตัวจัดการ handout มาสเตอร์ อ่านอย่างเดียว [IMasterHandoutSlideManager](../imasterhandoutslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideManager](../imasternotesslidemanager/)\> [get_MasterNotesSlideManager](./get_masternotesslidemanager/)() override | ส่งคืนตัวจัดการโน้ตมาสเตอร์ อ่านอย่างเดียว [IMasterNotesSlideManager](../imasternotesslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideCollection](../imasterslidecollection/)\> [get_Masters](./get_masters/)() override | ส่งคืนรายการของสไลด์มาสเตอร์ทั้งหมดที่กำหนดในงานนำเสนออ่านอย่างเดียว [IMasterSlideCollection](../imasterslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)\> [get_MasterTheme](./get_mastertheme/)() override | ส่งคืนธีมมาสเตอร์อ่านอย่างเดียว [Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSize](../inotessize/)\> [get_NotesSize](./get_notessize/)() override | ส่งคืนอ็อบเจ็กต์ขนาดสไลด์โน้ตอ่านอย่างเดียว [INotesSize](../inotessize/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProtectionManager](../iprotectionmanager/)\> [get_ProtectionManager](./get_protectionmanager/)() override | รับตัวจัดการสิทธิ์สำหรับงานนำเสนอนี้อ่านอย่างเดียว [IProtectionManager](../iprotectionmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_Section](./get_section/)(**int32_t**) override | ส่งคืนส่วนสไลด์ที่กำหนดในงานนำเสนอที่ตำแหน่งที่ระบุอ่านอย่างเดียว [Aspose::Slides::ISection](../isection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionCollection](../isectioncollection/)\> [get_Sections](./get_sections/)() override | ส่งคืนรายการของส่วนสไลด์ทั้งหมดที่กำหนดในงานนำเสนออ่านอย่างเดียว [ISectionCollection](../isectioncollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabelCollection](../isensitivitylabelcollection/)\> [get_SensitivityLabels](./get_sensitivitylabels/)() override | ส่งคืนคอลเลกชันของป้ายกำกับความอ่อนไหวที่ใช้กับเอกสารงานนำเสนออ่านอย่างเดียว [ISensitivityLabelCollection](../isensitivitylabelcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)(**int32_t**) override | ส่งคืนสไลด์ที่กำหนดในงานนำเสนอที่ตำแหน่งที่ระบุอ่านอย่างเดียว [Aspose::Slides::ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideCollection](../islidecollection/)\> [get_Slides](./get_slides/)() override | ส่งคืนรายการของสไลด์ทั้งหมดที่กำหนดในงานนำเสนออ่านอย่างเดียว [ISlideCollection](../islidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowSettings](../slideshowsettings/)\> [get_SlideShowSettings](./get_slideshowsettings/)() const | ส่งคืนการตั้งค่าการแสดงสไลด์สำหรับงานนำเสนอ. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideSize](../islidesize/)\> [get_SlideSize](./get_slidesize/)() override | ส่งคืนอ็อบเจ็กต์ขนาดสไลด์อ่านอย่างเดียว [ISlideSize](../islidesize/). |
| [Aspose::Slides::SourceFormat](../sourceformat/) [get_SourceFormat](./get_sourceformat/)() override | ส่งคืนข้อมูลเกี่ยวกับรูปแบบที่โหลดงานนำเสนอ. อ่านอย่างเดียว [SourceFormat](../sourceformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\> [get_VbaProject](./get_vbaproject/)() override | รับโครงการ VBA ที่มีมาโครของงานนำเสนอ. อ่าน [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_Video](./get_video/)(**int32_t**) override | ส่งคืนไฟล์วิดีโอที่ฝังในงานนำเสนอที่ตำแหน่งที่ระบุอ่านอย่างเดียว [Aspose::Slides::IVideo](../ivideo/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoCollection](../ivideocollection/)\> [get_Videos](./get_videos/)() override | ส่งคืนคอลเลกชันของไฟล์วิดีโอที่ฝังทั้งหมดในงานนำเสนออ่านอย่างเดียว [IVideoCollection](../ivideocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IViewProperties](../iviewproperties/)\> [get_ViewProperties](./get_viewproperties/)() override | รับคุณสมบัติมุมมองทั่วงานนำเสนออ่านอย่างเดียว [IViewProperties](../iviewproperties/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบเดียวกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์กำหนดเองได้. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | ส่งคืนอ็อบเจ็กต์ Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอ. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอโดยใช้การสเกลแบบกำหนดเอง. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) override | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอโดยใช้การสเกลแบบกำหนดเอง. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยขนาดที่ระบุ. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) override | ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยขนาดที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [GetSlideById](./getslidebyid/)(**uint32_t**) override | ส่งคืน [Slide](../slide/), [MasterSlide](../masterslide/) หรือ [LayoutSlide](../layoutslide/) ตาม Id. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. แบบเดียวกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | เน้นการจับคู่ทั้งหมดของ regular expression ด้วยสีที่ระบุ. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) override | เน้นการจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | เน้นการจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. แบบเดียวกับตัวดำเนินการ 'is' ของ C#. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | รวม run ที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมดในรูปร่างที่ยอมรับได้ทุกรูปในสไลด์ทั้งหมด. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เหมือนการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้อ็อบเจ็กต์ดูแล [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบเดียวกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การมอบหมายค่า. ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
|  [Presentation](./presentation/)() | คอนสตรัคเตอร์นี้สร้างงานนำเสนอใหม่จากศูนย์ งานนำเสนอที่สร้างมีสไลด์ว่างหนึ่งสไลด์. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | คอนสตรัคเตอร์นี้สร้างงานนำเสนอใหม่จากศูนย์ งานนำเสนอที่สร้างมีสไลด์ว่างหนึ่งสไลด์. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | คอนสตรัคเตอร์นี้เป็นกลไกหลักสำหรับอ่าน [Presentation](./) ที่มีอยู่. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | คอนสตรัคเตอร์นี้เป็นกลไกหลักสำหรับอ่าน [Presentation](./) ที่มีอยู่. |
|  [Presentation](./presentation/)([System::String](../../system/string/)) | คอนสตรัคเตอร์นี้รับเส้นทางไฟล์ต้นทางที่ใช้เพื่ออ่านเนื้อหาของ [Presentation](./). |
|  [Presentation](./presentation/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | คอนสตรัคเตอร์นี้รับเส้นทางไฟล์ต้นทางที่ใช้เพื่ออ่านเนื้อหาของ [Presentation](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เป็นการกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เป็นการกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | แทนที่การจับคู่ทั้งหมดของ regular expression ด้วยสตริงที่ระบุ. |
| void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความที่ระบุอีกอัน. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นไฟล์ในรูปแบบที่ระบุ. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นสตรีมในรูปแบบที่ระบุ. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นไฟล์ในรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นสตรีมในรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../aspose.slides.export.xaml/ixamloptions/)\>) override | บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นชุดไฟล์ที่เป็น XAML markup. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | บันทึกสไลด์ที่ระบุของงานนำเสนอเป็นไฟล์ในรูปแบบที่ระบุโดยคงหมายเลขหน้า. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | บันทึกสไลด์ที่ระบุของงานนำเสนอเป็นไฟล์ในรูปแบบที่ระบุโดยคงหมายเลขหน้า. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | บันทึกสไลด์ที่ระบุของงานนำเสนอเป็นสตรีมในรูปแบบที่ระบุโดยคงหมายเลขหน้า. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | บันทึกสไลด์ที่ระบุของงานนำเสนอเป็นสตรีมในรูปแบบที่ระบุโดยคงหมายเลขหน้า. |
| void [set_CurrentDateTime](./set_currentdatetime/)([System::DateTime](../../system/datetime/)) override | ตั้งค่าวันที่และเวลาที่จะทดแทนเนื้อหาของฟิลด์วันที่และเวลา เวลาการสร้างอ็อบเจ็กต์ [Presentation](./) นี้โดยค่าเริ่มต้น เขียน [System::DateTime](../../system/datetime/). |
| void [set_DocumentProperty](./set_documentproperty/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | ตั้งค่าคุณสมบัติกำหนดเองที่กำหนดโดยชื่อ. |
| void [set_FirstSlideNumber](./set_firstslidenumber/)(**int32_t**) override | แสดงหมายเลขสไลด์แรกในงานนำเสนอ |
| void [set_VbaProject](./set_vbaproject/)([System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\>) override | ตั้งค่าโครงการ VBA กับมาโครของงานนำเสนอ. เขียน [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและส่งค่ากลับ. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบเดียวกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้แปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือนคำสั่ง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เหมือนการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้อ็อบเจ็กต์ดูแล [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## Remarks

ตัวอย่างต่อไปนี้แสดงวิธีสร้าง PowerPoint [Presentation](./). 
```cpp
// สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

// ดึงสไลด์แรก
auto slide = presentation->get_Slides()->idx_get(0);
// เพิ่มรูปอัตโนมัติประเภทเส้น
slide->get_Shapes()->AddAutoShape(ShapeType::Line, 50.0f, 150.0f, 300.0f, 0.0f);
// บันทึกไฟล์งานนำเสนอ
presentation->Save(u"NewPresentation_out.pptx", SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีเปิดและบันทึก [Presentation](./). 
```cpp
// โหลดไฟล์ที่รองรับใด ๆ ใน Presentation เช่น ppt, pptx, odp เป็นต้น
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"Sample.odp");

// บันทึกไฟล์งานนำเสนอ.
presentation->Save(u"OutputPresenation.pptx", SaveFormat::Pptx);
```

## See Also

* คลาส [IPresentation](../ipresentation/)
* คลาส [IDOMObject](../idomobject/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)