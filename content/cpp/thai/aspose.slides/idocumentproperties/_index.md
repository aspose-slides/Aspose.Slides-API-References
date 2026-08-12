---
title: IDocumentProperties
second_title: Aspose.Slides สำหรับการอ้างอิง API C++
description: เป็นตัวแทนของคุณสมบัติของงานนำเสนอ.
type: docs
weight: 1977
url: /th/aspose.slides/idocumentproperties/
---
## IDocumentProperties คลาส

Represents properties of a presentation.

```cpp
class IDocumentProperties : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | ล้างและตั้งค่าดีฟอลต์สำหรับคุณสมบัติ builtIn ทั้งหมด. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | ลบคุณสมบัติ custom ทั้งหมด. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | ตรวจสอบการมีอยู่ของคุณสมบัติ custom ที่มีชื่อระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ double ตามสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | ส่งคืนแม่แบบของแอปพลิเคชัน อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | ส่งคืนเวอร์ชันของแอป อ่านอย่างเดียว [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | ส่งคืนผู้เขียนของงานนำเสนอ อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | ส่งคืนประเภทของงานนำเสนอ อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | ส่งคืนความคิดเห็นของงานนำเสนอ อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | ส่งคืนคุณสมบัติบริษัท อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | ส่งคืนสถานะเนื้อหาของงานนำเสนอ อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | ส่งคืนประเภทเนื้อหาของงานนำเสนอ อ่าน [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | ส่งคืนจำนวนของคุณสมบัติ custom ที่จริง ๆ แล้วอยู่ในคอลเลกชัน อ่านอย่างเดียว **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | ส่งคืนวันที่งานนำเสนอถูกสร้าง ค่าเป็น UTC อ่าน [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | บ่งชี้การจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม อ่านอย่างเดียว [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | ระบุจำนวนสไลด์ซ่อนในเอกสารงานนำเสนอ อ่านอย่างเดียว **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | ส่งคืนคุณสมบัติ HyperlinkBase ของเอกสาร อ่าน [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ถูกอัปเดตโดยผู้ผลิตเฉพาะในส่วนนี้ ผู้ผลิตถัดไปที่เปิดเอกสารนี้จะอัปเดตความสัมพันธ์ของลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้ อ่าน **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | ส่งคืนคีย์เวิร์ดของงานนำเสนอ อ่าน [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | ส่งคืนวันที่งานนำเสนอถูกพิมพ์ครั้งล่าสุด อ่าน [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | ส่งคืนชื่อของบุคคลสุดท้ายที่แก้ไขงานนำเสนอ อ่าน [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | ส่งคืนวันที่งานนำเสนอถูกแก้ไขครั้งสุดท้าย ค่าเป็น UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะจะถูกอัปเดตภายในขณะกระบวนการบันทึกวัตถุ [IPresentation](../ipresentation/)) สามารถเปลี่ยนได้ผ่านอ็อบเจกต์ [DocumentProperties](../documentproperties/) ที่ส่งกลับโดยเมธอด [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) โปรดดูตัวอย่างในสรุปเมธอด [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | ระบุว่าลิงก์ในเอกสารเป็นรุ่นล่าสุดหรือไม่ ตั้งค่าส่วนนี้เป็น **true** เพื่อบ่งชี้ว่าลิงก์อัปเดตแล้ว ตั้งค่าเป็น **false** เพื่อบ่งชี้ว่าลิงก์ล้าสมัย อ่าน **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | ส่งคืนคุณสมบัติผู้จัดการ อ่าน [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | ระบุจำนวนคลิปเสียงหรือวิดีโอทั้งหมดที่มีอยู่ในเอกสาร อ่านอย่างเดียว **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | ส่งคืนชื่อของแอปพลิเคชัน อ่าน [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | ระบุจำนวนสไลด์ในงานนำเสนอที่มีโน้ต อ่านอย่างเดียว **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | ระบุจำนวนย่อหน้าทั้งหมดที่พบในเอกสาร (หากมี) อ่านอย่างเดียว **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | ส่งคืนรูปแบบที่ตั้งใจของงานนำเสนอ อ่าน [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | ส่งคืนหมายเลขรุ่นของงานนำเสนอ อ่าน **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | ระบุโหมดการแสดงผลของรูปย่อเอกสาร ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดการปรับขนาดของรูปย่อให้พอดีกับจอแสดงผล ตั้งค่าเป็น **false** เพื่อเปิดการครอบตัดรูปย่อให้แสดงเฉพาะส่วนที่พอดีจอ แสดงอ่าน **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | กำหนดว่าหน้าที่นำเสนอถูกแชร์ระหว่างหลายคนหรือไม่ อ่าน **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | ระบุจำนวนสไลด์ทั้งหมดในเอกสารงานนำเสนอ อ่านอย่างเดียว **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | ส่งคืนหัวข้อของงานนำเสนอ อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | ส่งคืนชื่อเรื่องของงานนำเสนอ อ่าน [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | ระบุตำแหน่งหัวข้อของแต่ละส่วนของเอกสาร ส่วนเหล่านี้ไม่ใช่ส่วนของเอกสารจริง ๆ แต่เป็นการแทนแนวคิดของส่วนเอกสาร อ่านอย่างเดียว [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | เวลาการแก้ไขทั้งหมดของงานนำเสนอ อ่าน [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | ระบุจำนวนคำทั้งหมดที่อยู่ในเอกสาร อ่านอย่างเดียว **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับข้อมูลโครงสร้างตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | ส่งคืนชื่อคุณสมบัติ custom ที่ตำแหน่งเฉพาะ. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | รับค่า boolean ที่กำหนดชื่อจากคุณสมบัติ custom. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | รับค่า integer ที่กำหนดชื่อจากคุณสมบัติ custom. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | รับค่า DateTime ที่กำหนดชื่อจากคุณสมบัติ custom. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | รับค่า string ที่กำหนดชื่อจากคุณสมบัติ custom. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | รับค่า float ที่กำหนดชื่อจากคุณสมบัติ custom. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | รับค่า double ที่กำหนดชื่อจากคุณสมบัติ custom. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอันตรของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชอ็อบเจกต์ custom. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | รับอาร์เรย์ของป้ายความไวจากคุณสมบัติเอกสาร custom (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ เป็นอันตรของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | ส่งคืนคุณสมบัติ custom ที่เชื่อมโยงกับชื่อที่ระบุ อ่าน [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | ตั้งค่าคุณสมบัติ custom ที่เชื่อมโยงกับชื่อที่ระบุ เขียน [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นอันตรของโอเปอร์เรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอันตรของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภท custom. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ ตั้งค่าโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คัดลอกคอนสตรัคเตอร์ ไม่ได้ทำการคัดลอกอะไรจริง ๆ เพียงแค่ตั้งค่าอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่ตั้งค่าอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การประยุกต์พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การประยุกต์พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | ลบคุณสมบัติ custom ที่เชื่อมโยงกับชื่อที่ระบุ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ด้วยค่าที่ระบุ. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | ตั้งค่าแม่แบบของแอปพลิเคชัน เขียน [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | ตั้งค่าผู้เขียนของงานนำเสนอ เขียน [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | ตั้งค่าประเภทของงานนำเสนอ เขียน [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | ตั้งค่าความคิดเห็นของงานนำเสนอ เขียน [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | ตั้งค่าคุณสมบัติบริษัท เขียน [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | ตั้งค่าสถานะเนื้อหาของงานนำเสนอ เขียน [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | ตั้งค่าประเภทเนื้อหาของงานนำเสนอ เขียน [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | ส่งคืนวันที่งานนำเสนอถูกสร้าง ค่าเป็น UTC เขียน [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | ตั้งค่าคุณสมบัติ HyperlinkBase ของเอกสาร เขียน [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ถูกอัปเดตโดยผู้ผลิตเฉพาะในส่วนนี้ ผู้ผลิตถัดไปที่เปิดเอกสารนี้จะอัปเดตความสัมพันธ์ของลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้ เขียน **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | ตั้งค่าคีย์เวิร์ดของงานนำเสนอ เขียน [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | ส่งคืนวันที่งานนำเสนอถูกพิมพ์ครั้งล่าสุด เขียน [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | ตั้งค่าชื่อของบุคคลสุดท้ายที่แก้ไขงานนำเสนอ เขียน [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | ส่งคืนวันที่งานนำเสนอถูกแก้ไขครั้งสุดท้าย ค่าเป็น UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะจะอัปเดตภายในขณะกระบวนการบันทึกวัตถุ [IPresentation](../ipresentation/)) สามารถเปลี่ยนได้ผ่านอ็อบเจกต์ [DocumentProperties](../documentproperties/) ที่ส่งกลับโดยเมธอด [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) โปรดดูตัวอย่างในสรุปเมธอด [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) เขียน |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | ระบุว่าลิงก์ในเอกสารเป็นรุ่นล่าสุดหรือไม่ ตั้งค่าส่วนนี้เป็น **true** เพื่อบ่งชี้ว่าลิงก์อัปเดตแล้ว ตั้งค่าเป็น **false** เพื่อบ่งชี้ว่าลิงก์ล้าสมัย เขียน **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | ตั้งค่าคุณสมบัติผู้จัดการ เขียน [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | ตั้งค่าชื่อของแอปพลิเคชัน เขียน [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | ตั้งค่ารูปแบบที่ตั้งใจของงานนำเสนอ เขียน [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | ตั้งค่าหมายเลขรุ่นของงานนำเสนอ เขียน **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | ระบุโหมดการแสดงผลของรูปย่อเอกสาร ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดการปรับขนาดของรูปย่อให้พอดีกับจอแสดงผล ตั้งค่าเป็น **false** เพื่อเปิดการครอบตัดรูปย่อให้แสดงเฉพาะส่วนที่พอดีจอ เขียน **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | กำหนดว่าหน้าที่นำเสนอถูกแชร์ระหว่างหลายคนหรือไม่ เขียน **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | ตั้งค่าหัวข้อของงานนำเสนอ เขียน [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | ตั้งค่าชื่อเรื่องของงานนำเสนอ เขียน [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | เวลาการแก้ไขทั้งหมดของงานนำเสนอ เขียน [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | ตั้งค่าคุณสมบัติ custom แบบ boolean ที่กำหนดชื่อ. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | ตั้งค่าคุณสมบัติ custom แบบ integer ที่กำหนดชื่อ. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | ตั้งค่าคุณสมบัติ custom แบบ DateTime ที่กำหนดชื่อ. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | ตั้งค่าคุณสมบัติ custom แบบ string ที่กำหนดชื่อ. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | ตั้งค่าคุณสมบัติ custom แบบ float ที่กำหนดชื่อ. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | ตั้งค่าคุณสมบัติ custom แบบ double ที่กำหนดชื่อ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์แม่แบบที่ n เป็น weak pointer (แทนการ shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอันตรของเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจกต์ custom เป็น string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)