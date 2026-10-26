---
title: XmlTextReader
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึงรีดเดอร์ที่ให้การเข้าถึงข้อมูล XML อย่างรวดเร็ว ไม่ใช้แคช และเป็นการเข้าถึงแบบไปข้างหน้าเท่านั้น
type: docs
weight: 508
url: /th/system.xml/xmltextreader/
---
## XmlTextReader คลาส

Represents a reader that provides fast, non-cached, forward-only access to XML data.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## เมธอด

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | เปลี่ยน [XmlReader::get_ReadState](../xmlreader/get_readstate/) ให้เป็น **Closed**. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) พร้อม URI ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้ URI และการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้ URI ที่ระบุ การตั้งค่า และข้อมูลบริบทสำหรับการแยกวิเคราะห์. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้สตรีมที่ระบุพร้อมการตั้งค่าเริ่มต้น. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) พร้อมสตรีมและการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้สตรีม, URI ฐาน, และการตั้งค่า. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้สตรีม, การตั้งค่า, และข้อมูลบริบทสำหรับการแยกวิเคราะห์. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้ตัวอ่านข้อความที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้ตัวอ่านข้อความและการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้ตัวอ่านข้อความ, การตั้งค่า, และ URI ฐานที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) ด้วยตัวอ่านข้อความ, การตั้งค่า, และข้อมูลบริบทสำหรับการแยกวิเคราะห์. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | สร้างอินสแทนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้ตัวอ่าน XML และการตั้งค่าที่ระบุ. |
| void [Dispose](../xmlreader/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอินสแทนซ์ปัจจุบันของคลาส [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าเทียบเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | คืนจำนวนแอตทริบิวต์ของโหนดปัจจุบัน. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | คืนค่า base URI ของโหนดปัจจุบัน. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | คืนค่าแสดงว่า [XmlTextReader](./) รองรับวิธีการอ่านเนื้อหาดิจิทัลหรือไม่. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | คืนค่าแสดงว่า [XmlTextReader](./) รองรับเมธอด [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) หรือไม่. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | คืนค่าแสดงว่าตัวอ่านนี้สามารถแยกวิเคราะห์และแก้ไขเอนทิตี้ได้หรือไม่. |
| **int32_t** [get_Depth](./get_depth/)() override | คืนความลึกของโหนดปัจจุบันในเอกสาร XML. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | คืนค่า enumeration DtdProcessing. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | คืนการเข้ารหัสของเอกสาร. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | คืนค่าที่ระบุว่าตัวอ่านจัดการเอนทิตี้อย่างไร. |
| **bool** [get_EOF](./get_eof/)() override | คืนค่าแสดงว่าตัวอ่านอยู่ที่ตำแหน่งสิ้นสุดของสตรีมหรือไม่. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | คืนค่าแสดงว่าโหนดปัจจุบันมีแอตทริบิวต์หรือไม่. |
| **bool** [get_HasValue](./get_hasvalue/)() override | คืนค่าแสดงว่าโหนดปัจจุบันสามารถมี [XmlTextReader::get_Value](./get_value/) ที่ไม่ใช่ [String::Empty](../../system/string/empty/) หรือไม่. |
| **bool** [get_IsDefault](./get_isdefault/)() override | คืนค่าแสดงว่าโหนดปัจจุบันเป็นแอตทริบิวต์ที่สร้างจากค่าเริ่มต้นที่กำหนดใน DTD หรือสคีมาหรือไม่. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | คืนค่าแสดงว่าโหนดปัจจุบันเป็นองค์ประกอบว่าง (เช่น **<MyElement/>**) หรือไม่. |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | คืนหมายเลขบรรทัดปัจจุบัน. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | คืนตำแหน่งบรรทัดปัจจุบัน. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | คืนชื่อท้องถิ่นของโหนดปัจจุบัน. |
| [String](../../system/string/) [get_Name](./get_name/)() override | คืนชื่อเต็มของโหนดปัจจุบัน. |
| **bool** [get_Namespaces](./get_namespaces/)() | คืนค่าแสดงว่าจะเปิดการสนับสนุนเนมสเปซหรือไม่. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | คืนค่า namespace URI (ตามสเปค W3C Namespace) ของโหนดที่ตัวอ่านกำลังชี้อยู่. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | คืนค่า [XmlNameTable](../xmlnametable/) ที่เชื่อมโยงกับการทำงานนี้. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | คืนประเภทของโหนดปัจจุบัน. |
| **bool** [get_Normalization](./get_normalization/)() | คืนค่าแสดงว่าจะทำให้ช่องว่างและค่าแอตทริบิวต์เป็นรูปแบบมาตรฐานหรือไม่. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | คืนคำนำหน้า namespace ที่เชื่อมโยงกับโหนดปัจจุบัน. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | คืนค่าแสดงว่าจะอนุญาตการประมวลผล DTD หรือไม่. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | คืนอักขระเครื่องหมายคำพูดที่ใช้ล้อมค่าของแอตทริบิวต์โหนด. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | คืนสถานะของตัวอ่าน. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | คืนข้อมูลสคีมาที่กำหนดให้กับโหนดปัจจุบันจากการตรวจสอบสคีมา. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | คืนอ็อบเจกต์ [XmlReaderSettings](../xmlreadersettings/) ที่ใช้สร้างอินสแทนซ์ [XmlReader](../xmlreader/) นี้. |
| [String](../../system/string/) [get_Value](./get_value/)() override | คืนค่าข้อความของโหนดปัจจุบัน. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | คืนประเภทของโหนดปัจจุบัน. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | คืนค่าที่ระบุวิธีการจัดการช่องว่าง. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | คืนขอบเขต **xml:lang** ปัจจุบัน. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | คืนขอบเขต **xml:space** ปัจจุบัน. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | คืนค่าของแอตทริบิวต์ที่มีชื่อที่ระบุ. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | คืนค่าของแอตทริบิวต์ที่มีชื่อท้องถิ่นและ namespace URI ที่ระบุ. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | คืนค่าของแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดการทำแฮชของอ็อบเจกต์แบบกำหนดเอง. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | คืนคอลเลกชันที่มีเนมสเปซทั้งหมดที่อยู่ในขอบเขตปัจจุบัน. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | คืนส่วนที่เหลือของ XML ที่บัฟเฟอร์. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | คืนค่าแสดงว่าคลาสสามารถคืนข้อมูลบรรทัดได้หรือไม่. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าของแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าของแอตทริบิวต์ที่มีค่า [XmlReader::get_Name](../xmlreader/get_name/) ที่ระบุ. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าของแอตทริบิวต์ที่มีค่า [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแทนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | คืนค่าแสดงว่าข้อความที่ส่งเป็นชื่อ XML ที่ถูกต้องหรือไม่. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | คืนค่าแสดงว่าข้อความที่ส่งเป็น token ชื่อ XML ที่ถูกต้องหรือไม่. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | เรียก [XmlReader::MoveToContent](../xmlreader/movetocontent/) และตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กองค์ประกอบว่างหรือไม่. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | เรียก [XmlReader::MoveToContent](../xmlreader/movetocontent/) และตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กองค์ประกอบว่างและว่าค่า [XmlReader::get_Name](../xmlreader/get_name/) ขององค์ประกอบที่พบตรงกับอาร์กิวเมนต์ที่ให้หรือไม่. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | เรียก [XmlReader::MoveToContent](../xmlreader/movetocontent/) และตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กองค์ประกอบว่างและว่าค่า [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ขององค์ประกอบที่พบตรงกับสตริงที่ให้หรือไม่. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ใส่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | แก้ไขคำนำหน้า namespace ในขอบเขตขององค์ประกอบปัจจุบัน. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดการโคลนประเภทที่กำหนดเอง. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | ย้ายไปยังแอตทริบิวต์ที่มีชื่อที่ระบุ. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | ย้ายไปยังแอตทริบิวต์ที่มีชื่อท้องถิ่นและ namespace URI ที่ระบุ. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | ย้ายไปยังแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | ตรวจสอบว่าโหนดปัจจุบันเป็นโหนดเนื้อหา (ข้อความที่ไม่ใช่ช่องว่าง, **CDATA**, **Element**, **EndElement**, **EntityReference**, หรือ **EndEntity**) หรือไม่ หากไม่ใช่โหนดเนื้อหา ตัวอ่านจะข้ามไปยังโหนดเนื้อถัดไปหรือจบไฟล์ โดยข้ามโหนดประเภทต่อไปนี้: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, หรือ **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | ย้ายไปยังองค์ประกอบที่บรรจุแอตทริบิวต์โหนดปัจจุบัน. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | ย้ายไปยังแอตทริบิวต์แรก. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | ย้ายไปยังแอตทริบิวต์ถัดไป. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาของซับคลาส. |
| **bool** [Read](./read/)() override | อ่านโหนดต่อไปจากสตรีม. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | แยกค่าแอตทริบิวต์เป็นหนึ่งหรือหลายโหนด **[Text](../../system.text/)**, **EntityReference**, หรือ **EndEntity**. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | ถอดรหัส Base64 และคืนไบท์ไบนารีที่ถอดรหัสแล้ว. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | ถอดรหัส **BinHex** และคืนไบท์ไบนารีที่ถอดรหัสแล้ว. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | อ่านเนื้อหาข้อความขององค์ประกอบเข้าไปในบัฟเฟอร์อักขระ. วิธีการนี้ออกแบบมาสำหรับการอ่านสตรีมข้อความฝังขนาดใหญ่โดยเรียกใช้งานต่อเนื่อง. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | อ่านเนื้อหาเป็นออบเจ็กต์ของประเภทที่ระบุ. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก **Base64**. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก **BinHex**. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็น [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นออบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นออบเจ็กต์ [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นออบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนเลขทศนิยมแบบ double-precision. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนเลขทศนิยมแบบ single-precision. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนเต็มแบบ 32-bit signed integer. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนเต็มแบบ 64-bit signed integer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็น [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นออบเจ็กต์ [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | อ่านเนื้อหาองค์ประกอบตามประเภทที่ร้องขอ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน, จากนั้นอ่านเนื้อหาองค์ประกอบตามประเภทที่ร้องขอ. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านองค์ประกอบและถอดรหัสเนื้อหา Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านองค์ประกอบและถอดรหัสเนื้อหา **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นออบเจ็กต์ [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน, จากนั้นอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นออบเจ็กต์ [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นออบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน, จากนั้นอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นออบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นออบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน, จากนั้นอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นออบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเลขทศนิยมแบบ double-precision. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน, จากนั้นอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเลขทศนิยมแบบ double-precision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเลขทศนิยมแบบ single-precision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่ชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน, จากนั้นอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเลขทศนิยมแบบ single-precision. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็มแบบ 32-bit signed integer. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน, จากนั้นอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็มแบบ 32-bit signed integer. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็มแบบ 64-bit signed integer. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน, จากนั้นอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็มแบบ 64-bit signed integer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็น [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน, จากนั้นอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็น [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นออบเจ็กต์ [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน, จากนั้นอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นออบเจ็กต์ [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | อ่านองค์ประกอบที่เป็นข้อความเท่านั้น. อย่างไรก็ตามแนะนำให้ใช้วิธี [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) แทน, เนื่องจากมันให้วิธีที่ตรงไปตรงมามากขึ้นสำหรับการจัดการการดำเนินการนี้. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | ตรวจสอบว่าค่าของ [XmlReader::get_Name](../xmlreader/get_name/) ขององค์ประกอบที่พบตรงกับสตริงที่ให้ไว้ก่อนอ่านองค์ประกอบที่เป็นข้อความเท่านั้น. อย่างไรก็ตามแนะนำให้ใช้วิธี [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) แทน, เนื่องจากมันให้วิธีที่ตรงไปตรงมามากขึ้นสำหรับการจัดการการดำเนินการนี้. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าค่า [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ขององค์ประกอบที่พบตรงกับสตริงที่ให้ไว้ก่อนอ่านองค์ประกอบที่เป็นข้อความเท่านั้น. อย่างไรก็ตามแนะนำให้ใช้วิธี [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) แทน, เนื่องจากมันให้วิธีที่ตรงไปตรงมามากขึ้นสำหรับการจัดการการดำเนินการนี้. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | ตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นแท็กสิ้นสุดและเลื่อนตัวอ่านไปยังโหนดถัดไป. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | เมื่อถูก Override ในคลาสที่สืบทอด, อ่านเนื้อหาทั้งหมดรวมถึง markup เป็นสตริง. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | เมื่อถูก Override ในคลาสที่สืบทอด, อ่านเนื้อหารวมถึง markup ที่แสดงโหนดนี้และโหนดลูกทั้งหมด. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | ตรวจสอบว่าโหนดปัจจุบันเป็นองค์ประกอบและเลื่อนตัวอ่านไปยังโหนดถัดไป. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | ตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นองค์ประกอบที่มีค่า [XmlReader::get_Name](../xmlreader/get_name/) ที่กำหนดและเลื่อนตัวอ่านไปยังโหนดถัดไป. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นองค์ประกอบที่มีค่า [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ที่กำหนดและเลื่อนตัวอ่านไปยังโหนดถัดไป. |
| [String](../../system/string/) [ReadString](./readstring/)() override | อ่านเนื้อหาขององค์ประกอบหรือโหนดข้อความเป็นสตริง. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | คืนค่าอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่ที่สามารถใช้ในการอ่านโหนดปัจจุบันและบุตรทั้งหมดของมัน. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบลูกต่อไปที่มีชื่อคุณลักษณะที่ระบุ. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบลูกต่อไปที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | อ่านจนกว่าจะพบองค์ประกอบที่มีชื่อคุณลักษณะที่ระบุ. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | อ่านจนกว่าจะพบองค์ประกอบที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบพี่น้องถัดไปที่มีชื่อคุณลักษณะที่ระบุ. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบพี่น้องถัดไปที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | อ่านสตรีมข้อความขนาดใหญ่ที่ฝังอยู่ในเอกสาร XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [ResetState](./resetstate/)() | รีเซ็ตสถานะของตัวอ่านเป็น [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | แก้ไขการอ้างอิงเอนทิตีสำหรับโหนด **EntityReference**. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | ตั้งค่าการนับรายการ DtdProcessing. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | ตั้งค่าที่ระบุวิธีที่ตัวอ่านจัดการเอนทิตี. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | ตั้งค่าที่ระบุว่าจะเปิดการสนับสนุนเนมสเปซหรือไม่. |
| void [set_Normalization](./set_normalization/)(**bool**) | ตั้งค่าที่ระบุว่าจะแนวโน้มการทำ normalize ช่องว่างและค่าคุณลักษณะหรือไม่. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | ตั้งค่าที่ระบุว่าจะอนุญาตการประมวลผล DTD หรือไม่. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | ตั้งค่าที่ระบุวิธีจัดการช่องว่าง. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | ตั้งค่า [XmlResolver](../xmlresolver/) ที่ใช้สำหรับการแก้ไขการอ้างอิง DTD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). ช่วยให้เปลี่ยนพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [Skip](./skip/)() override | ข้ามลูกของโหนดปัจจุบัน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกอนของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการดำเนินการ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วยสตรีมที่ระบุ. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วย URL และสตรีมที่ระบุ. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วยสตรีมและ [XmlNameTable](../xmlnametable/) ที่ระบุ. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วย URL, สตรีม และ [XmlNameTable](../xmlnametable/) ที่ระบุ. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วย TextReader ที่ระบุ. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วย URL และ TextReader ที่ระบุ. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วย TextReader และ [XmlNameTable](../xmlnametable/) ที่ระบุ. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วย URL, TextReader และ [XmlNameTable](../xmlnametable/) ที่ระบุ. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วย stream, XmlNodeType และ [XmlParserContext](../xmlparsercontext/) ที่ระบุ. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วย string, XmlNodeType และ [XmlParserContext](../xmlparsercontext/) ที่ระบุ. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วยไฟล์ที่ระบุ. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlTextReader](./) ด้วยไฟล์และ [XmlNameTable](../xmlnametable/) ที่ระบุ. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## การกำหนดชนิด

| การนิยามชนิด | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |
## หมายเหตุ

แนะนำให้ใช้คลาส [XmlReader](../xmlreader/) แทน. 

วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันทันเวลาและ/หรือการละเมิดเงื่อนไข. ห่อคลาสนี้ในตัวชี้ [System::SmartPtr](../../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. 

## ดูเพิ่มเติม

* คลาส [XmlReader](../xmlreader/)
* คลาส [IXmlLineInfo](../ixmllineinfo/)
* คลาส [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)