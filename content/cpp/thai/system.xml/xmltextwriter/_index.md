---
title: XmlTextWriter
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึง writer ที่ให้วิธีการสร้างสตรีมหรือไฟล์ที่มีข้อมูล XML อย่างรวดเร็ว ไม่ผ่านการแคช และแบบ forward-only ซึ่งสอดคล้องกับ W3C Extensible Markup Language (XML) 1.0 และข้อแนะนำ Namespaces in XML
type: docs
weight: 521
url: /th/system.xml/xmltextwriter/
---
## XmlTextWriter คลาส

Represents a writer that provides a fast, non-cached, forward-only way of generating streams or files containing XML data that conforms to the W3C Extensible Markup Language (XML) 1.0 and the Namespaces in XML recommendations.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Close](./close/)() override | ปิดสตรีมนี้และสตรีมพื้นฐาน. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ของ [XmlWriter](../xmlwriter/) ใหม่โดยใช้ชื่อไฟล์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | สร้างอินสแตนซ์ของ [XmlWriter](../xmlwriter/) ใหม่โดยใช้ชื่อไฟล์และอ็อบเจ็กต์ [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | สร้างอินสแตนซ์ของ [XmlWriter](../xmlwriter/) ใหม่โดยใช้สตรีมที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | สร้างอินสแตนซ์ของ [XmlWriter](../xmlwriter/) ใหม่โดยใช้สตรีมและอ็อบเจ็กต์ [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | สร้างอินสแตนซ์ของ [XmlWriter](../xmlwriter/) ใหม่โดยใช้ TextWriter ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | สร้างอินสแตนซ์ของ [XmlWriter](../xmlwriter/) ใหม่โดยใช้ TextWriter และอ็อบเจ็กต์ [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | สร้างอินสแตนซ์ของ [XmlWriter](../xmlwriter/) ใหม่โดยใช้ [Text::StringBuilder](../../system.text/stringbuilder/) ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | สร้างอินสแตนซ์ของ [XmlWriter](../xmlwriter/) ใหม่โดยใช้อ็อบเจ็กต์ [Text::StringBuilder](../../system.text/stringbuilder/) และ [XmlWriterSettings](../xmlwritersettings/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | สร้างอินสแตนซ์ของ [XmlWriter](../xmlwriter/) ใหม่โดยใช้อ็อบเจ็กต์ [XmlWriter](../xmlwriter/) ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | สร้างอินสแตนซ์ของ [XmlWriter](../xmlwriter/) ใหม่โดยใช้อ็อบเจ็กต์ [XmlWriter](../xmlwriter/) และ [XmlWriterSettings](../xmlwritersettings/) ที่ระบุ. |
| void [Dispose](../xmlwriter/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอินสแตนซ์ปัจจุบันของคลาส [XmlWriter](../xmlwriter/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซ็มานติคของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าตัวเลขแบบลอยตัวสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าชนิดใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าตัวเลขแบบลอยตัวสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าชนิดใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| void [Flush](./flush/)() override | ล้างบัฟเฟอร์ทั้งหมดไปยังสตรีมพื้นฐานและยังล้างสตรีมพื้นฐานด้วย. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | ส่งคืนอ็อบเจ็กต์สตรีมพื้นฐาน. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | บ่งชี้ว่าการออกผลลัพธ์ถูกฟอร์แมตอย่างไร. |
| **int32_t** [get_Indentation](./get_indentation/)() | ส่งคืนจำนวน IndentChars ที่จะเขียนสำหรับแต่ละระดับในโครงสร้างเมื่อ [XmlTextWriter::set_Formatting](./set_formatting/) ถูกตั้งค่าเป็น [Formatting::Indented](../formatting/). |
| char16_t [get_IndentChar](./get_indentchar/)() | ส่งคืนอักขระที่ใช้สำหรับการเว้นบรรทัดเมื่อ [XmlTextWriter::set_Formatting](./set_formatting/) ตั้งค่าเป็น [Formatting::Indented](../formatting/). |
| **bool** [get_Namespaces](./get_namespaces/)() | ส่งคืนค่าที่บ่งชี้ว่าจะเปิดการสนับสนุนเนมสเปซหรือไม่. |
| char16_t [get_QuoteChar](./get_quotechar/)() | ส่งคืนอักขระที่ใช้ใส่เครื่องหมายอัญประกาศให้ค่าคุณสมบัติ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | ส่งคืนอ็อบเจ็กต์ [XmlWriterSettings](../xmlwritersettings/) ที่ใช้สร้างอินสแตนซ์ [XmlWriter](../xmlwriter/) นี้. |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | ส่งคืนสถานะของ writer. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | ส่งคืนขอบเขต **xml:lang** ปัจจุบัน. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | ส่งคืน XmlSpace ที่แสดงขอบเขต **xml:space** ปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ targetType บรรยายหรือไม่ เป็นอเนกประสงค์ของอ็อพเจกต์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | ส่งคืนคำนำหน้าที่ใกล้ที่สุดที่กำหนดในขอบเขตเนมสเปซปัจจุบันสำหรับ URI ของเนมสเปซ. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning ชนิดกำหนดเองได้. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์และเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมลงตามค่าที่ระบุ. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | บ่งชี้ว่าการออกผลลัพธ์ถูกฟอร์แมตอย่างไร. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | ตั้งค่าจำนวน IndentChars ที่จะเขียนสำหรับแต่ละระดับในโครงสร้างเมื่อ [XmlTextWriter::set_Formatting](./set_formatting/) ถูกตั้งค่าเป็น [Formatting::Indented](../formatting/). |
| void [set_IndentChar](./set_indentchar/)(char16_t) | ตั้งค่าอักขระที่จะใช้สำหรับการเว้นบรรทัดเมื่อ [XmlTextWriter::set_Formatting](./set_formatting/) ตั้งเป็น [Formatting::Indented](../formatting/). |
| void [set_Namespaces](./set_namespaces/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าจะทำการสนับสนุนเนมสเปซหรือไม่. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | ตั้งค่าอักขระที่จะใช้ใส่เครื่องหมายอัญประกาศให้ค่าคุณสมบัติ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนจำนวนตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ควรใช้ smart pointers หรือ ThisProtector. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | เมื่อถูก override ในคลาสที่สืบทอด จะเขียนคุณสมบัติทั้งหมดที่พบในตำแหน่งปัจจุบันของ [XmlReader](../xmlreader/). |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อถูก override ในคลาสที่สืบทอด จะเขียนคุณสมบัติด้วยชื่อท้องถิ่น, URI ของเนมสเปซและค่า ที่ระบุ. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อถูก override ในคลาสที่สืบทอด จะเขียนคุณสมบัติกับชื่อท้องถิ่นและค่าที่ระบุ. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อถูก override ในคลาสที่สืบทอด จะเขียนคุณสมบัติกับคำนำหน้า, ชื่อท้องถิ่น, URI ของเนมสเปซและค่าที่ระบุ. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | เข้ารหัสไบต์ไบนารีที่ระบุเป็น base64 และเขียนข้อความที่ได้. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | เข้ารหัสไบต์ไบนารีที่ระบุเป็น binhex และเขียนข้อความที่ได้. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | เขียนบล็อก **...** ที่มีข้อความที่ระบุ. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | บังคับสร้างเอนทิตี้อักขระสำหรับค่าตัวอักษร Unicode ที่ระบุ. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | เขียนข้อความทีละบัฟเฟอร์. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | เขียนคอมเมนต์ **** ที่มีข้อความที่ระบุ. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | เขียนประกาศ DOCTYPE พร้อมชื่อที่ระบุและคุณสมบัติตามต้องการ. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เขียนองค์ประกอบด้วยชื่อท้องถิ่นและค่าที่ระบุ. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เขียนองค์ประกอบด้วยชื่อท้องถิ่น, URI ของเนมสเปซและค่า ที่ระบุ. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เขียนองค์ประกอบด้วยคำนำหน้า, ชื่อท้องถิ่น, URI ของเนมสเปซและค่า ที่ระบุ. |
| void [WriteEndAttribute](./writeendattribute/)() override | ปิดการเรียก [XmlTextWriter::WriteStartAttribute](./writestartattribute/) ก่อนหน้า. |
| void [WriteEndDocument](./writeenddocument/)() override | ปิดองค์ประกอบหรือคุณสมบัติที่เปิดอยู่ทั้งหมดและทำให้ writer กลับเข้าสู่สถานะ Start. |
| void [WriteEndElement](./writeendelement/)() override | ปิดองค์ประกอบหนึ่งและถอดขอบเขตเนมสเปซที่สอดคล้อง. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | เขียนการอ้างอิงเอนทิตี้เป็น **&name**;. |
| void [WriteFullEndElement](./writefullendelement/)() override | ปิดองค์ประกอบหนึ่งและถอดขอบเขตเนมสเปซที่สอดคล้อง. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | เขียนชื่อที่ระบุโดยตรวจสอบว่าถูกต้องตาม [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | เขียนชื่อที่ระบุโดยตรวจสอบว่าถูกต้องตาม **NmToken** ของ [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name). |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | เมื่อถูก override ในคลาสที่สืบทอด จะคัดลอกทุกอย่างจาก reader ไปยัง writer และย้าย reader ไปยังจุดเริ่มต้นของพี่น้องถัดไป. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | คัดลอกทุกอย่างจากอ็อบเจ็กต์ XPathNavigator ไปยัง writer ตำแหน่งของ XPathNavigator จะคงเดิม. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | เขียนคำสั่งประมวลผลโดยเว้นช่องว่างระหว่างชื่อและข้อความดังนี้: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | เขียนชื่อที่มีเนมสเปซโดยอ้างอิง วิธีนี้ค้นหาคำนำหน้าที่อยู่ในขอบเขตของเนมสเปซที่ให้. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | เขียนมาร์คอัปดิบด้วยตนเองจากบัฟเฟอร์อักขระ. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | เขียนมาร์คอัปดิบด้วยตนเองจากสตริง. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | เขียนจุดเริ่มต้นของคุณสมบัติ. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เขียนจุดเริ่มต้นของคุณสมบัติกับชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | เขียนจุดเริ่มต้นของคุณสมบัติกับชื่อท้องถิ่นที่ระบุ. |
| void [WriteStartDocument](./writestartdocument/)() override | เขียนประกาศ XML ด้วยเวอร์ชัน "1.0". |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | เขียนประกาศ XML ด้วยเวอร์ชัน "1.0" และคุณลักษณะ standalone. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | เขียนแท็กเริ่มต้นที่ระบุและเชื่อมโยงกับเนมสเปซและคำนำหน้าที่ให้. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เมื่อถูก override ในคลาสที่สืบทอด จะเขียนแท็กเริ่มต้นที่ระบุและเชื่อมโยงกับเนมสเปซที่ให้. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | เมื่อถูก override ในคลาสที่สืบทอด จะเขียนแท็กเริ่มต้นด้วยชื่อท้องถิ่นที่ระบุ. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | เขียนเนื้อหาข้อความที่ให้. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | สร้างและเขียนเอนทิตี้อักขระเซร็อกเกตสำหรับคู่อักขระเซร็อกเกต. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เขียนค่าของอ็อบเจ็กต์. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | เขียนค่า [String](../../system/string/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | เขียนค่า [Boolean](../../system/boolean/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | เขียนค่า [DateTime](../../system/datetime/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | เขียนค่า [DateTimeOffset](../../system/datetimeoffset/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | เขียนค่า [Double](../../system/double/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | เขียนเลขทศนิยมแบบความแม่นยำเดียว. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | เขียนค่า [Decimal](../../system/decimal/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | เขียนค่า [Int32](../../system/int32/). |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | เขียนค่า [Int64](../../system/int64/). |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | เขียนช่องว่างที่ให้. |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | สร้างอินสแตนซ์ของคลาส [XmlTextWriter](./) โดยใช้สตรีมและการเข้ารหัสที่ระบุ. |
| [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | สร้างอินสแตนซ์ของคลาส [XmlTextWriter](./) โดยใช้ไฟล์ที่ระบุ. |
| [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | สร้างอินสแตนซ์ของคลาส [XmlTextWriter](./) โดยใช้ TextWriter ที่ระบุ. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์และคืนหน่วยความจำของโครงสร้างข้อมูลภายใน. |

## นิยามชนิด

| นิยามชนิด | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ

แนะนำให้ใช้คลาส [XmlWriter](../xmlwriter/) แทน.

อ็อบเจ็กต์ของคลาสนี้ควรจัดสันทรัพยากรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการผิดพลาดของการตรวจสอบ ควรห่อคลาสนี้ในพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นั้นเพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

## ดูเพิ่มเติม

* คลาส [XmlWriter](../xmlwriter/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)