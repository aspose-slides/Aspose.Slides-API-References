---
title: XmlValidatingReader
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นตัวอ่านที่ให้การตรวจสอบความถูกต้องของการกำหนดประเภทเอกสาร (DTD), XML-Data Reduced (XDR) schema, และ XML Schema definition language (XSD)
type: docs
weight: 547
url: /th/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader คลาส

แสดงถึงตัวอ่านที่ให้การตรวจสอบเอกสารประเภท (DTD), สคีม่า XML-Data Reduced (XDR) และภาษา [Schema](../../system.xml.schema/) (XSD)

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Close](./close/)() override | เปลี่ยน [XmlReader::get_ReadState](../xmlreader/get_readstate/) ให้เป็น Closed. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่ด้วย URI ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่โดยใช้ URI และการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่โดยใช้ URI การตั้งค่า และข้อมูลบริบทสำหรับการแยกวิเคราะห์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่โดยใช้สตรีมที่ระบุพร้อมการตั้งค่าเริ่มต้น. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่ด้วยสตรีมและการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่โดยใช้สตรีม URI ฐานและการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่โดยใช้สตรีม การตั้งค่า และข้อมูลบริบทสำหรับการแยกวิเคราะห์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่โดยใช้ตัวอ่านข้อความที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่โดยใช้ตัวอ่านข้อความและการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่โดยใช้ตัวอ่านข้อความ การตั้งค่า และ Base URI ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่โดยใช้ตัวอ่านข้อความ การตั้งค่า และข้อมูลบริบทสำหรับการแยกวิเคราะห์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | สร้างอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่โดยใช้ XML reader และการตั้งค่าที่ระบุ. |
| void [Dispose](../xmlreader/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอินสแตนซ์ปัจจุบันของคลาส [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ซึ่ง NaN สองค่าได้รับการถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ซึ่ง NaN สองค่าได้รับการถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | คืนค่าจำนวนแอตทริบิวต์บนโหนดปัจจุบัน. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | คืนค่า base URI ของโหนดปัจจุบัน. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | คืนค่าแสดงว่า [XmlValidatingReader](./) ทำงานเมธอดอ่านเนื้อหาด้านไบนารีหรือไม่. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | คืนค่าแสดงว่า [XmlReader](../xmlreader/) ทำงานเมธอด [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) หรือไม่. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | คืนค่าแสดงว่าตัวอ่านนี้สามารถแยกวิเคราะห์และแก้ไขเอนทิตี้ได้หรือไม่. |
| **int32_t** [get_Depth](./get_depth/)() override | คืนค่าความลึกของโหนดปัจจุบันในเอกสาร XML. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | คืนค่าแอตทริบิวต์ encoding ของเอกสาร. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | คืนค่าที่กำหนดวิธีที่ตัวอ่านจัดการเอนทิตี้. |
| **bool** [get_EOF](./get_eof/)() override | คืนค่าแสดงว่าตัวอ่านอยู่ที่ตำแหน่งสิ้นสุดของสตรีมหรือไม่. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | คืนค่าแสดงว่าโหนดปัจจุบันมีแอตทริบิวต์หรือไม่. |
| **bool** [get_HasValue](./get_hasvalue/)() override | คืนค่าแสดงว่าโหนดปัจจุบันสามารถมี [XmlValidatingReader::get_Value](./get_value/) ที่ไม่ใช่ [String::Empty](../../system/string/empty/) ได้หรือไม่. |
| **bool** [get_IsDefault](./get_isdefault/)() override | คืนค่าแสดงว่าโหนดปัจจุบันเป็นแอตทริบิวต์ที่สร้างจากค่าดีฟอลต์ที่กำหนดใน DTD หรือสคีม่า. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | คืนค่าแสดงว่าโหนดปัจจุบันเป็นองค์ประกอบว่าง (เช่น **<MyElement/>**) หรือไม่. |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | คืนหมายเลขบรรทัดปัจจุบัน. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | คืนตำแหน่งบรรทัดปัจจุบัน. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | คืนค่าชื่อท้องถิ่นของโหนดปัจจุบัน. |
| [String](../../system/string/) [get_Name](./get_name/)() override | คืนค่าชื่อที่มีคุณลักษณะครบของโหนดปัจจุบัน. |
| **bool** [get_Namespaces](./get_namespaces/)() | คืนค่าแสดงว่าจะทำการสนับสนุนเนมสเปซหรือไม่. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | คืนค่า Uniform Resource Identifier (URI) ของเนมส페ซ (ตามที่กำหนดใน World Wide [Web](../../system.web/) Consortium (W3C) Namespace specification) ของโหนดที่ตัวอ่านอยู่. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | คืนค่า [XmlNameTable](../xmlnametable/) ที่เกี่ยวข้องกับการนำไปใช้นี้. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | คืนค่าชนิดของโหนดปัจจุบัน. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | คืนค่าพรีฟิกซ์ของเนมส페ซที่เกี่ยวข้องกับโหนดปัจจุบัน. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | คืนอักขระเครื่องหมายอัญประกาศที่ใช้คลุมค่าของแอตทริบิวต์โหนด. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | คืนค่า [XmlReader](../xmlreader/) ที่ใช้สร้าง [XmlValidatingReader](./) นี้. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | คืนสถานะของตัวอ่าน. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | คืนข้อมูลสคีมาที่ถูกกำหนดให้กับโหนดปัจจุบันจากผลของการตรวจสอบสคีมา. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | คืน XmlSchemaCollection เพื่อใช้สำหรับการตรวจสอบ. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | คืนอ็อบเจ็กต์ประเภทสคีม่า. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | คืนอ็อบเจ็กต์ [XmlReaderSettings](../xmlreadersettings/) ที่ใช้สร้างอินสแตนซ์ [XmlReader](../xmlreader/) นี้. |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | คืนค่าที่บ่งบอกประเภทของการตรวจสอบที่จะทำ. |
| [String](../../system/string/) [get_Value](./get_value/)() override | คืนค่าข้อความของโหนดปัจจุบัน. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | คืนประเภทของโหนดปัจจุบัน. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | คืนขอบเขต **xml:lang** ปัจจุบัน. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | คืนขอบเขต **xml:space** ปัจจุบัน. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | คืนค่าของแอตทริบิวต์ที่มีชื่อที่ระบุ. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | คืนค่าของแอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ของเนมส페ซที่ระบุ. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | คืนค่าของแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [HasLineInfo](./haslineinfo/)() override | คืนค่าแสดงว่าคลาสสามารถคืนข้อมูลบรรทัดได้หรือไม่. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | เมื่อถูกโอเวอร์ไรด์ในคลาสที่สืบทอด จะได้รับค่าของแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | เมื่อถูกโอเวอร์ไรด์ในคลาสที่สืบทอด จะได้รับค่าของแอตทริบิวต์ที่มีค่า [XmlReader::get_Name](../xmlreader/get_name/) ที่ระบุ. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | เมื่อถูกโอเวอร์ไรด์ในคลาสที่สืบทอด จะได้รับค่าของแอตทริบิวต์ที่มีค่า [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | คืนค่าแสดงว่าอาร์กิวเมนต์สตริงเป็นชื่อ XML ที่ถูกต้องหรือไม่. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | คืนค่าแสดงว่าอาร์กิวเมนต์สตริงเป็นโทเคนชื่อ XML ที่ถูกต้องหรือไม่. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | เรียก [XmlReader::MoveToContent](../xmlreader/movetocontent/) และทดสอบว่าโหนดเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กองค์ประกอบว่าง. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | เรียก [XmlReader::MoveToContent](../xmlreader/movetocontent/) และทดสอบว่าโหนดเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กองค์ประกอบว่างและค่า [XmlReader::get_Name](../xmlreader/get_name/) ขององค์ประกอบที่พบตรงกับอาร์กิวเมนต์ที่ให้. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | เรียก [XmlReader::MoveToContent](../xmlreader/movetocontent/) และทดสอบว่าโหนดเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กองค์ประกอบว่างและค่า [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ขององค์ประกอบที่พบตรงกับสตริงที่ให้. |
| void [Lock](../../system/object/lock/)() | ใช้การล็อกตามคำสั่ง C# lock() ทำการล็อกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | แก้ไขพรีฟิกซ์ของเนมส페ซในขอบเขตขององค์ประกอบปัจจุบัน. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคล cloning ประเภทที่กำหนดเองได้. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | ย้ายไปยังแอตทริบิวต์ที่มีชื่อที่ระบุ. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | ย้ายไปยังแอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ของเนมส페ซที่ระบุ. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | ย้ายไปยังแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | ตรวจสอบว่าโหนดปัจจุบันเป็นโหนดเนื้อหา (ข้อความที่ไม่เป็น whitespace, **CDATA**, **Element**, **EndElement**, **EntityReference**, หรือ **EndEntity**) หรือไม่ หากไม่เป็นโหนดเนื้อหา ตัวอ่านจะข้ามไปยังโหนดเนื้อถัดไปหรือจบไฟล์ มันจะข้ามโหนดประเภทต่อไปนี้: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, หรือ **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | ย้ายไปยังองค์ประกอบที่มีแอตทริบิวต์ปัจจุบัน. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | ย้ายไปยังแอตทริบิวต์แรก. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | ย้ายไปยังแอตทริบิวต์ถัดไป. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ในคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ในคลาสย่อย. |
| **bool** [Read](./read/)() override | อ่านโหนดถัดไปจากสตรีม. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | แยกค่าแอตทริบิวต์เป็นหนึ่งหรือหลาย **[Text](../../system.text/)**, **EntityReference**, หรือ **EndEntity** โหนด. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | อ่านเนื้อหาเป็นอ็อบเจ็กต์ของประเภทที่ระบุ. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็น [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนจริงแบบจุดลอยตัวแบบความแม่นยำคู่. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนจริงแบบจุดลอยตัวแบบความแม่นยำเดี่ยว. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนเต็มซายน์ 32 บิต. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนเต็มซายน์ 64 บิต. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็น [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | อ่านเนื้อหาองค์ประกอบเป็นประเภทที่ต้องการ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่, แล้วอ่านเนื้อหาองค์ประกอบเป็นประเภทที่ต้องการ. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านองค์ประกอบและถอดรหัสเนื้อหา Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านองค์ประกอบและถอดรหัสเนื้อหา BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | อ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นอ็อบเจ็กต์ [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่, แล้วอ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นอ็อบเจ็กต์ [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | อ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นอ็อบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่, แล้วอ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นอ็อบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | อ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นอ็อบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่, แล้วอ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นอ็อบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | อ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นจำนวนจริงแบบจุดลอยตัวแบบความแม่นยำคู่. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่, แล้วอ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นจำนวนจริงแบบจุดลอยตัวแบบความแม่นยำคู่. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | อ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นจำนวนจริงแบบจุดลอยตัวแบบความแม่นยำเดี่ยว. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่, แล้วอ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นจำนวนจริงแบบจุดลอยตัวแบบความแม่นยำเดี่ยว. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | อ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นจำนวนเต็มซายน์ 32 บิต. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่, แล้วอ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นจำนวนเต็มซายน์ 32 บิต. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | อ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นจำนวนเต็มซายน์ 64 บิต. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่, แล้วอ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นจำนวนเต็มซายน์ 64 บิต. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | อ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็น [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่, แล้วอ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็น [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | อ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นอ็อบเจ็กต์ [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันหรือไม่, แล้วอ่านองค์ประกอบปัจจุบันและส่งคืนเนื้อหาเป็นอ็อบเจ็กต์ [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | อ่านองค์ประกอบที่มีข้อความเท่านั้น อย่างไรก็ตาม แนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) แทน เนื่องจากให้วิธีที่ตรงไปตรงมามากกว่าในการจัดการปฏิบัติการนี้. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | ตรวจสอบว่าค่าของ [XmlReader::get_Name](../xmlreader/get_name/) ขององค์ประกอบที่พบตรงกับสตริงที่กำหนดก่อนอ่านองค์ประกอบที่มีข้อความเท่านั้น อย่างไรก็ตาม แนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) แทน เนื่องจากให้วิธีที่ตรงไปตรงมามากกว่าในการจัดการปฏิบัติการนี้. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าค่า [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ขององค์ประกอบที่พบตรงกับสตริงที่กำหนดก่อนอ่านองค์ประกอบที่มีข้อความเท่านั้น อย่างไรก็ตาม แนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) แทน เนื่องจากให้วิธีที่ตรงไปตรงมามากกว่าในการจัดการปฏิบัติการนี้. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | ตรวจสอบว่าโหนดเนื้อหาในปัจจุบันเป็นแท็กปิดและเลื่อนตัวอ่านไปยังโหนดต่อไป. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | เมื่อถูกเขียนทับในคลาสที่สืบทอด จะอ่านเนื้อหาทั้งหมดรวมถึงมาร์กอัปเป็นสตริง. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | เมื่อถูกเขียนทับในคลาสที่สืบทอด จะอ่านเนื้อหารวมถึงมาร์กอัปที่แสดงโหนดนี้และบุตรทั้งหมด. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | ตรวจสอบว่าโหนดปัจจุบันเป็นองค์ประกอบและเลื่อนตัวอ่านไปยังโหนดต่อไป. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | ตรวจสอบว่าโหนดเนื้อหาในปัจจุบันเป็นองค์ประกอบที่มีค่า [XmlReader::get_Name](../xmlreader/get_name/) ที่ระบุและเลื่อนตัวอ่านไปยังโหนดต่อไป. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าโหนดเนื้อหาในปัจจุบันเป็นองค์ประกอบที่มีค่า [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ที่ระบุและเลื่อนตัวอ่านไปยังโหนดต่อไป. |
| [String](../../system/string/) [ReadString](./readstring/)() override | อ่านเนื้อหาขององค์ประกอบหรือโหนดข้อความเป็นสตริง. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | คืนค่าอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่ที่สามารถใช้เพื่ออ่านโหนดปัจจุบันและลูกทั้งหมดของมัน. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบลูกถัดไปที่มีชื่อคุณสมบัติที่ระบุ. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบลูกถัดไปที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | อ่านจนกว่าจะพบองค์ประกอบที่มีชื่อคุณสมบัติที่ระบุ. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | อ่านจนกว่าจะพบองค์ประกอบที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบพี่น้องถัดไปที่มีชื่อคุณสมบัติที่ระบุ. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบพี่น้องถัดไปที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | คืนค่าชนิดรันไทม์สำหรับประเภทภาษา นิยาม XML [Schema](../../system.xml.schema/) (XSD) ที่ระบุ. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | อ่านสตรีมข้อความขนาดใหญ่ที่ฝังในเอกสาร XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงร่วมตามค่าที่ระบุ. |
| void [ResolveEntity](./resolveentity/)() override | แก้ไขการอ้างอิงเอนทิตีสำหรับโหนด **EntityReference**. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | กำหนดค่าที่ระบุว่าตัวอ่านจัดการเอนทิตีอย่างไร. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | กำหนดค่าที่บ่งชี้ว่าจะทำการสนับสนุนนามสเปซหรือไม่. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | กำหนดค่าที่บ่งชี้ประเภทการตรวจสอบที่ต้องทำ. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | ตั้งค่า [XmlResolver](../xmlresolver/) ที่ใช้สำหรับการแก้ไขการอ้างอิงนิยามประเภทเอกสารภายนอก (DTD) และตำแหน่งสกีม่า [XmlResolver](../xmlresolver/) ยังใช้เพื่อจัดการกับอิลิเมนต์ import หรือ include ที่พบในสกีม่า XML [Schema](../../system.xml.schema/) (XSD). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงร่วม ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงร่วมและคืนค่า ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual void [Skip](../xmlreader/skip/)() | ข้ามลูกของโหนดปัจจุบัน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อคของคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | เพิ่มอีเวนต์แฮนด์เลอร์สำหรับรับข้อมูลเกี่ยวกับข้อผิดพลาดการตรวจสอบสกีม่า document type definition (DTD), XML-Data Reduced (XDR) และ XML [Schema](../../system.xml.schema/) (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | ลบอีเวนต์แฮนด์เลอร์สำหรับรับข้อมูลเกี่ยวกับข้อผิดพลาดการตรวจสอบสกีม่า document type definition (DTD), XML-Data Reduced (XDR) และ XML [Schema](../../system.xml.schema/) (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิง weak ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิง weak ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlValidatingReader](./) ที่ตรวจสอบความถูกต้องของเนื้อหาที่ส่งคืนจาก [XmlReader](../xmlreader/) ที่ระบุ. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlValidatingReader](./) ด้วยค่าที่ระบุ. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlValidatingReader](./) ด้วยค่าที่ระบุ. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## การกำหนดชนิด

| การกำหนดชนิด | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |
## หมายเหตุ


เลิกใช้
:   คลาสนี้ล้าสมัย แนะนำให้ใช้คลาส [XmlReaderSettings](../xmlreadersettings/) และเมธอด [XmlReader::Create](../xmlreader/create/) เพื่อสร้างตัวอ่าน XML ที่ตรวจสอบความถูกต้อง.
Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## ดูเพิ่มเติม

* คลาส [XmlReader](../xmlreader/)
* คลาส [IXmlLineInfo](../ixmllineinfo/)
* คลาส [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)