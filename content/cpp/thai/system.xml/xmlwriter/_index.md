---
title: XmlWriter
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: แสดงถึงผู้เขียนที่ให้วิธีที่เร็ว ไม่ใช้แคช และทำงานต่อหน้าเดียวเพื่อสร้างสตรีมหรือไฟล์ที่มีข้อมูล XML
type: docs
weight: 573
url: /th/system.xml/xmlwriter/
---
## XmlWriter คลาส


Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data.

```cpp
class XmlWriter : public System::IDisposable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [Close](./close/)() | เมื่อทำการเขียนทับในคลาสที่สืบทอด, ปิดสตรีมนี้และสตรีมพื้นฐาน. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ใหม่ของ [XmlWriter](./) โดยใช้ชื่อไฟล์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | สร้างอินสแตนซ์ใหม่ของ [XmlWriter](./) โดยใช้ชื่อไฟล์และอ็อบเจกต์ [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlWriter](./) โดยใช้สตรีมที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | สร้างอินสแตนซ์ใหม่ของ [XmlWriter](./) โดยใช้สตรีมและอ็อบเจกต์ [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlWriter](./) โดยใช้ TextWriter ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | สร้างอินสแตนซ์ใหม่ของ [XmlWriter](./) โดยใช้ TextWriter และอ็อบเจกต์ [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlWriter](./) โดยใช้ [Text::StringBuilder](../../system.text/stringbuilder/) ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | สร้างอินสแตนซ์ใหม่ของ [XmlWriter](./) โดยใช้อ็อบเจกต์ [Text::StringBuilder](../../system.text/stringbuilder/) และ [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlWriter](./) โดยใช้อ็อบเจกต์ [XmlWriter](./) ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | สร้างอินสแตนซ์ใหม่ของ [XmlWriter](./) โดยใช้อ็อบเจกต์ [XmlWriter](./) และ [XmlWriterSettings](../xmlwritersettings/) ที่ระบุ. |
| void [Dispose](./dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอินสแตนซ์ปัจจุบันของคลาส [XmlWriter](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น. |
| virtual void [Flush](./flush/)() | เมื่อทำการเขียนทับในคลาสที่สืบทอด, ทำการฟลัชข้อมูลใด ๆ ที่อยู่ในบัฟเฟอร์ไปยังสตรีมพื้นฐานและฟลัชสตรีมพื้นฐานด้วย. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | คืนค่าอ็อบเจกต์ [XmlWriterSettings](../xmlwritersettings/) ที่ใช้สร้างอินสแตนซ์ [XmlWriter](./) นี้. |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | เมื่อทำการเขียนทับในคลาสที่สืบทอด, ดึงสถานะของตัวเขียน. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | เมื่อทำการเขียนทับในคลาสที่สืบทอด, ดึงขอบเขต **xml:lang** ปัจจุบัน. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | เมื่อทำการเขียนทับในคลาสที่สืบทอด, ดึง XmlSpace ที่แสดงขอบเขต **xml:space** ปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเวอร์ชันคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถทำแฮชอ็อบเจกต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจกต์. เป็นเวอร์ชันคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นเวอร์ชันคล้ายตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, คืนค่าพรีฟิกซ์ที่ใกล้ที่สุดที่กำหนดในขอบเขตเนมสเปซปัจจุบันสำหรับ URI ของเนมสเปซ. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเวอร์ชันคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ในคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ในคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับการอ้างอิงที่แชร์ลงด้วยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้เปลี่ยนพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเวอร์ชันคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนออกทั้งหมดของแอตทริบิวต์ที่พบในตำแหน่งปัจจุบันใน [XmlReader](../xmlreader/). |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนแอตทริบิวต์ด้วยชื่อท้องถิ่น, URI ของเนมสเปซ, และค่าที่ระบุ. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนแอตทริบิวต์ด้วยชื่อท้องถิ่นและค่าที่ระบุ. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนแอตทริบิวต์ด้วยพรีฟิกซ์, ชื่อท้องถิ่น, URI ของเนมสเปซ, และค่าที่ระบุ. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เข้ารหัสไบต์ไบนารีที่ระบุเป็น Base64 และเขียนข้อความที่ได้. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เข้ารหัสไบต์ไบนารีที่ระบุเป็น **BinHex** และเขียนข้อความที่ได้. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนบล็อก **...** ที่มีข้อความที่ระบุ. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, บังคับให้สร้างเอนทิตีของอักขระสำหรับค่าตัวอักษร Unicode ที่ระบุ. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนข้อความทีละบัฟเฟอร์. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนคอมเมนต์ **** ที่มีข้อความที่ระบุ. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนประกาศ DOCTYPE ด้วยชื่อที่ระบุและแอตทริบิวต์เพิ่มเติม (ถ้ามี). |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เขียนอิลิเมนต์ด้วยชื่อท้องถิ่นและค่าที่ระบุ. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เขียนอิลิเมนต์ด้วยชื่อท้องถิ่น, URI ของเนมสเปซ, และค่าที่ระบุ. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เขียนอิลิเมนต์ด้วยพรีฟิกซ์, ชื่อท้องถิ่น, URI ของเนมสเปซ, และค่าที่ระบุ. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | เมื่อทำการเขียนทับในคลาสที่สืบทอด, ปิดการเรียก XmlWriter::WriteStartAttribute(String,String) ก่อนหน้า. |
| virtual void [WriteEndDocument](./writeenddocument/)() | เมื่อทำการเขียนทับในคลาสที่สืบทอด, ปิดอิลิเมนต์หรือแอตทริบิวต์ที่เปิดอยู่ทั้งหมดและตั้งค่าตัวเขียนกลับสู่สถานะ Start. |
| virtual void [WriteEndElement](./writeendelement/)() | เมื่อทำการเขียนทับในคลาสที่สืบทอด, ปิดอิลิเมนต์หนึ่งและถอดขอบเขตเนมสเปซที่สัมพันธ์. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนอ้างอิงเอนทิตีเป็น **&name**;. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | เมื่อทำการเขียนทับในคลาสที่สืบทอด, ปิดอิลิเมนต์หนึ่งและถอดขอบเขตเนมสเปซที่สัมพันธ์. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนชื่อที่ระบุโดยตรวจสอบว่าชื่อนั้นเป็นชื่อที่ถูกต้องตามข้อแนะนำ XML 1.0 ของ W3C ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนชื่อที่ระบุโดยตรวจสอบว่าเป็น NmToken ที่ถูกต้องตามข้อแนะนำ XML 1.0 ของ W3C ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)). |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, คัดลอกทุกอย่างจากรีดเดอร์ไปยังไรเตอร์และย้ายรีดเดอร์ไปยังจุดเริ่มต้นของน้องที่ต่อไป. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | คัดลอกทุกอย่างจากอ็อบเจกต์ XPathNavigator ไปยังไรเตอร์. ตำแหน่งของ XPathNavigator ยังคงไม่เปลี่ยน. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนคำสั่งการประมวลผลโดยมีช่องว่างระหว่างชื่อและข้อความดังนี้: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนชื่อที่มีการระบุเนมสเปซ. วิธีนี้ค้นหาพรีฟิกซ์ที่อยู่ในขอบเขตสำหรับเนมสเปซที่กำหนด. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนมาร์คอัปดิบด้วยตนเองจากบัฟเฟอร์อักขระ. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนมาร์คอัปดิบด้วยตนเองจากสตริง. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เขียนจุดเริ่มต้นของแอตทริบิวต์ด้วยชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนจุดเริ่มต้นของแอตทริบิวต์ด้วยพรีฟิกซ์, ชื่อท้องถิ่น, และ URI ของเนมสเปซที่ระบุ. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | เขียนจุดเริ่มต้นของแอตทริบิวต์ด้วยชื่อท้องถิ่นที่ระบุ. |
| virtual void [WriteStartDocument](./writestartdocument/)() | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนการประกาศ XML ด้วยเวอร์ชัน "1.0". |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนการประกาศ XML ด้วยเวอร์ชัน "1.0" และแอตทริบิวต์ standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนแท็กเริ่มต้นที่ระบุและเชื่อมโยงกับเนมสเปซที่กำหนด. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนแท็กเริ่มต้นที่ระบุและเชื่อมโยงกับเนมสเปซและพรีฟิกซ์ที่กำหนด. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนแท็กเริ่มต้นด้วยชื่อท้องถิ่นที่ระบุ. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนเนื้อหาข้อความที่ให้. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, สร้างและเขียนเอนทิตีอักขระโซลูชั่นสำหรับคู่อักขระโซลูชั่น. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เขียนค่าของอ็อบเจกต์. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | เขียนค่า [String](../../system/string/). |
| virtual void [WriteValue](./writevalue/)(**bool**) | เขียนค่า [Boolean](../../system/boolean/). |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | เขียนค่า [DateTime](../../system/datetime/). |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | เขียนค่า [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](./writevalue/)(**double**) | เขียนค่า [Double](../../system/double/). |
| virtual void [WriteValue](./writevalue/)(**float**) | เขียนตัวเลขจุดลอยตัวความแม่นยำเดี่ยว. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | เขียนค่า [Decimal](../../system/decimal/). |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | เขียนค่า [Int32](../../system/int32/). |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | เขียนค่า [Int64](../../system/int64/). |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | เมื่อทำการเขียนทับในคลาสที่สืบทอด, เขียนช่องว่างที่ให้. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ประเภทนิยาม

| ประเภทนิยาม | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | เป็นนามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## ดูเพิ่มเติม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)