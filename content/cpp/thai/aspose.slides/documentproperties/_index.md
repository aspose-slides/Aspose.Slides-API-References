---
title: DocumentProperties
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แสดงคุณสมบัติของงานนำเสนอ.
type: docs
weight: 794
url: /th/aspose.slides/documentproperties/
---
## DocumentProperties คลาส

Represents properties of a presentation.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | ล้างและตั้งค่าตั้งต้นสำหรับคุณสมบัติ builtIn ทั้งหมด |
| void [ClearCustomProperties](./clearcustomproperties/)() override | ลบคุณสมบัติ custom ทั้งหมด |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | ทำสำเนาวัตถุปัจจุบัน |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | ทำสำเนาวัตถุปัจจุบัน |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | ตรวจสอบการมีอยู่ของคุณสมบัติ custom ที่มีชื่อระบุ |
|  [DocumentProperties](./documentproperties/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [DocumentProperties](./) |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าถือว่ามีค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าถือว่ามีค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | ส่งคืนเทมเพลตของแอปพลิเคชัน อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | ส่งคืนเวอร์ชันของแอป อ่านอย่างเดียว [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | ส่งคืนผู้เขียนของงานนำเสนอ อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | ส่งคืนหมวดหมู่ของงานนำเสนอ อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | ส่งคืนความคิดเห็นของงานนำเสนอ อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | ส่งคืนคุณสมบัติบริษัท อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | ส่งคืนสถานะเนื้อหาของงานนำเสนอ อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | ส่งคืนประเภทเนื้อหาของงานนำเสนอ อ่าน [System::String](../../system/string/) |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | ส่งคืนจำนวนคุณสมบัติ custom ที่อยู่ในคอลเลกชันจริง ๆ อ่านอย่างเดียว **int32_t** |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | ส่งคืนวันที่สร้างงานนำเสนอ ค่าต่าง ๆ อยู่ในรูปแบบ UTC อ่าน [System::DateTime](../../system/datetime/) |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | ระบุการจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม อ่านอย่างเดียว [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/) |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | ส่งคืนจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารงานนำเสนอ อ่านอย่างเดียว **int32_t** |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | ส่งคืนคุณสมบัติ HyperlinkBase ของเอกสาร อ่าน [System::String](../../system/string/) |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตโดยเฉพาะ ส่วนผู้ผลิตถัดไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้ อ่าน **bool** |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | ส่งคืนคำสำคัญของงานนำเสนอ อ่าน [System::String](../../system/string/) |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | ส่งคืนวันที่พิมพ์งานนำเสนอครั้งสุดท้าย อ่าน [System::DateTime](../../system/datetime/) |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | ส่งคืนชื่อของผู้ที่แก้ไขงานนำเสนอเป็นคนล่าสุด อ่าน [System::String](../../system/string/) |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | ส่งคืนวันที่แก้ไขงานนำเสนอครั้งสุดท้าย ค่าต่าง ๆ อยู่ในรูปแบบ UTC อ่านอย่างเดียวในกรณีของ [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (เพราะจะถูกอัปเดตภายในขณะกระบวนการบันทึกวัตถุ [IPresentation](../ipresentation/)) สามารถเปลี่ยนได้ผ่านอินสแตนซ์ [DocumentProperties](./) ที่คืนโดยเมธอด [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) โปรดดูตัวอย่างในสรุปเมธอด [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | ระบุว่าลิงก์ในเอกสารเป็นปัจจุบันหรือไม่ ตั้งค่าส่วนนี้เป็น **true** เพื่อระบุว่าลิงก์อัปเดตแล้ว ตั้งเป็น **false** เพื่อระบุว่าลิงก์ล้าสมัย อ่าน **bool** |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | ส่งคืนคุณสมบัติผู้จัดการ อ่าน [System::String](../../system/string/) |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | ส่งคืนจำนวนทั้งหมดของคลิปเสียงหรือวิดีโอที่อยู่ในเอกสาร อ่านอย่างเดียว **int32_t** |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | ส่งคืนชื่อของแอปพลิเคชัน อ่าน [System::String](../../system/string/) |
| **int32_t** [get_Notes](./get_notes/)() override | ส่งคืนจำนวนสไลด์ในงานนำเสนอที่มีโน๊ต อ่านอย่างเดียว **int32_t** |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | ส่งคืนจำนวนทั้งหมดของย่อหน้าที่พบในเอกสาร (ถ้ามี) อ่านอย่างเดียว **int32_t** |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | ส่งคืนรูปแบบที่ต้องการของงานนำเสนอ อ่าน [System::String](../../system/string/) |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | ส่งคืนหมายเลขฉบับแก้ไขของงานนำเสนอ อ่าน **int32_t** |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | ระบุโหมดการแสดงผลของภาพย่อเอกสาร ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดการขยายขนาดภาพย่อให้พอดีกับการแสดงผล ตั้งเป็น **false** เพื่อเปิดการตัดภาพย่อให้แสดงเฉพาะส่วนที่พอดีกับการแสดงผล อ่าน **bool** |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | กำหนดว่ามีการแชร์งานนำเสนอระหว่างหลายคนหรือไม่ อ่าน **bool** |
| **int32_t** [get_Slides](./get_slides/)() override | ส่งคืนจำนวนทั้งหมดของสไลด์ในเอกสารงานนำเสนอ อ่านอย่างเดียว **int32_t** |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | ส่งคืนหัวข้อของงานนำเสนอ อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | ส่งคืนชื่อเรื่องของงานนำเสนอ อ่าน [System::String](../../system/string/) |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | ระบุชื่อเรื่องของแต่ละส่วนเอกสาร ส่วนเหล่านี้ไม่ใช่ส่วนของเอกสารจริง แต่เป็นการแทนแนวคิดของส่วนต่าง ๆ ของเอกสาร อ่านอย่างเดียว [System::ArrayPtr<System::String>](../../system/arrayptr/) |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | ระยะเวลาการแก้ไขทั้งหมดของงานนำเสนอ อ่าน [System::TimeSpan](../../system/timespan/) |
| **int32_t** [get_Words](./get_words/)() override | ส่งคืนจำนวนทั้งหมดของคำที่อยู่ในเอกสาร อ่านอย่างเดียว **int32_t** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับวัตถุ |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | คืนชื่อคุณสมบัติ custom ที่ตำแหน่งที่ระบุ |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | รับค่าบูลีนที่ตั้งชื่อจากคุณสมบัติ custom |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | รับค่าจำนวนเต็มที่ตั้งชื่อจากคุณสมบัติ custom |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | รับค่าวันเวลา (DateTime) ที่ตั้งชื่อจากคุณสมบัติ custom |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | รับค่าสตริงที่ตั้งชื่อจากคุณสมบัติ custom |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | รับค่า float ที่ตั้งชื่อจากคุณสมบัติ custom |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | รับค่า double ที่ตั้งชื่อจากคุณสมบัติ custom |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อเนกอนของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถสร้างแฮชของอ็อบเจ็กต์ custom |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | รับอาเรย์ของป้ายความอ่อนไหวจากคุณสมบัติเอกสาร custom (Metadata ของ Microsoft Information Protection SDK) |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ อเนกอนของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | ส่งคืนคุณสมบัติ custom ที่เชื่อมกับชื่อที่ระบุ อ่าน [System::Object](../../system/object/) |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | ตั้งค่าคุณสมบัติ custom ที่เชื่อมกับชื่อที่ระบุ เขียน [System::Object](../../system/object/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType อเนกอนของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อเนกอนของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถสร้างสำเนาของประเภท custom |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไร เพียงเริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | ลบคุณสมบัติ custom ที่เชื่อมกับชื่อที่ระบุ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | ตั้งค่าเทมเพลตของแอปพลิเคชัน เขียน [System::String](../../system/string/) |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | ตั้งค่าผู้เขียนของงานนำเสนอ เขียน [System::String](../../system/string/) |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | ตั้งค่าหมวดหมู่ของงานนำเสนอ เขียน [System::String](../../system/string/) |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | ตั้งค่าความคิดเห็นของงานนำเสนอ เขียน [System::String](../../system/string/) |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | ตั้งค่าคุณสมบัติบริษัท เขียน [System::String](../../system/string/) |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | ตั้งค่าสถานะเนื้อหาของงานนำเสนอ เขียน [System::String](../../system/string/) |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | ตั้งค่าประเภทเนื้อหาของงานนำเสนอ เขียน [System::String](../../system/string/) |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | ตั้งค่าวันที่สร้างงานนำเสนอ ค่าต่าง ๆ อยู่ในรูปแบบ UTC เขียน [System::DateTime](../../system/datetime/) |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | ตั้งค่าคุณสมบัติ HyperlinkBase ของเอกสาร เขียน [System::String](../../system/string/) |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตโดยเฉพาะ ส่วนผู้ผลิตถัดไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้ เขียน **bool** |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | ตั้งค่าคำสำคัญของงานนำเสนอ เขียน [System::String](../../system/string/) |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | ตั้งค่าวันที่พิมพ์งานนำเสนอครั้งสุดท้าย เขียน [System::DateTime](../../system/datetime/) |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | ตั้งค่าชื่อของผู้ที่แก้ไขงานนำเสนอเป็นคนล่าสุด เขียน [System::String](../../system/string/) |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | ส่งคืนวันที่แก้ไขงานนำเสนอครั้งสุดท้าย ค่าต่าง ๆ อยู่ในรูปแบบ UTC อ่านอย่างเดียวในกรณีของ [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (เพราะจะถูกอัปเดตภายในขณะกระบวนการบันทึกวัตถุ [IPresentation](../ipresentation/)) สามารถเปลี่ยนได้ผ่านอินสแตนซ์ [DocumentProperties](./) ที่คืนโดยเมธอด [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) โปรดดูตัวอย่างในสรุปเมธอด [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | ระบุว่าลิงก์ในเอกสารเป็นปัจจุบันหรือไม่ ตั้งค่าส่วนนี้เป็น **true** เพื่อระบุว่าลิงก์อัปเดตแล้ว ตั้งเป็น **false** เพื่อระบุว่าลิงก์ล้าสมัย เขียน **bool** |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | ตั้งค่าคุณสมบัติผู้จัดการ เขียน [System::String](../../system/string/) |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | ตั้งค่าชื่อของแอปพลิเคชัน เขียน [System::String](../../system/string/) |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | ตั้งค่ารูปแบบที่ต้องการของงานนำเสนอ เขียน [System::String](../../system/string/) |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | ตั้งค่าหมายเลขฉบับแก้ไขของงานนำเสนอ เขียน **int32_t** |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | ระบุโหมดการแสดงผลของภาพย่อเอกสาร ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดการขยายขนาดภาพย่อให้พอดีกับการแสดงผล ตั้งเป็น **false** เพื่อเปิดการตัดภาพย่อให้แสดงเฉพาะส่วนที่พอดีกับการแสดงผล เขียน **bool** |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | กำหนดว่ามีการแชร์งานนำเสนอระหว่างหลายคนหรือไม่ เขียน **bool** |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | ตั้งค่าหัวข้อของงานนำเสนอ เขียน [System::String](../../system/string/) |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | ตั้งค่าชื่อเรื่องของงานนำเสนอ เขียน [System::String](../../system/string/) |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | ตั้งค่าเวลาการแก้ไขทั้งหมดของงานนำเสนอ เขียน [System::TimeSpan](../../system/timespan/) |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | ตั้งค่าคุณสมบัติบูลีนที่ตั้งชื่อใน custom |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | ตั้งค่าคุณสมบัติจำนวนเต็มที่ตั้งชื่อใน custom |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | ตั้งค่าคุณสมบัติ DateTime ที่ตั้งชื่อใน custom |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | ตั้งค่าคุณสมบัติสตริงที่ตั้งชื่อใน custom |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | ตั้งค่าคุณสมบัติ float ที่ตั้งชื่อใน custom |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | ตั้งค่าคุณสมบัติ double ที่ตั้งชื่อใน custom |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (ไม่ใช่ shared) ให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงร่วม ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนตัวนับการอ้างอิงร่วม ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อเนกอนของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ custom เป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการ construct C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

The following example shows how to access built-in Properties of PowerPoint [Presentation](../presentation/). 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่แสดงงานนำเสนอ
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
 The following example shows how to modify built-in Properties of PowerPoint [Presentation](../presentation/). 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่แสดง Presentation
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// สร้างอ้างอิงไปยังอ็อบเจ็กต์ IDocumentProperties ที่เชื่อมกับ Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// ตั้งค่าคุณสมบัติ built-in
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// บันทึกงานนำเสนอของคุณลงไฟล์
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IDocumentProperties](../idocumentproperties/)
* คลาส [IGenericCloneable](../igenericcloneable/)
* เนมสเปซ [Aspose::Slides](../)
* Library [Aspose.Slides](../../)