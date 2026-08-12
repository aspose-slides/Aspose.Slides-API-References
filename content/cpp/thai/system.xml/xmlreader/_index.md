---
title: XmlReader
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงตัวอ่านที่ให้การเข้าถึงข้อมูล XML อย่างรวดเร็ว ไม่ใช้แคช และแบบไปข้างหน้าเท่านั้น
type: docs
weight: 430
url: /th/system.xml/xmlreader/
---
## คลาส XmlReader


เป็นรีดเดอร์ที่ให้การเข้าถึงข้อมูล XML อย่างเร็ว ไม่ใช้แคช และแบบเดินหน้าต่อเนื่องเท่านั้น.

```cpp
class XmlReader : public System::IDisposable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [Close](./close/)() | เมื่อถูก override ในคลาสที่สืบทอด, เปลี่ยน [XmlReader::get_ReadState](./get_readstate/) เป็น [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้ URI ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้ URI และการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้ URI, การตั้งค่า และข้อมูลบริบทที่ระบุสำหรับการพาร์ส. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้สตรีมที่ระบุด้วยการตั้งค่าเริ่มต้น. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้สตรีมและการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้สตรีม, URI พื้นฐาน, และการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้สตรีม, การตั้งค่า, และข้อมูลบริบทที่ระบุสำหรับการพาร์ส. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้ text reader ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้ text reader ที่ระบุและการตั้งค่า. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้ text reader, การตั้งค่า, และ URI พื้นฐานที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้ text reader, การตั้งค่า, และข้อมูลบริบทที่ระบุสำหรับการพาร์ส. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | สร้างอินสแตนซ์ [XmlReader](./) ใหม่โดยใช้ XML reader ที่ระบุและการตั้งค่า. |
| void [Dispose](./dispose/)() override | ปลดปล่อยทรัพยากรทั้งหมดที่ใช้โดยอินสแตนซ์ปัจจุบันของคลาส [XmlReader](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# โดยที่ NaN สองค่าถือเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใดเลยรวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# โดยที่ NaN สองค่าถือเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใดเลยรวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับจำนวนแอตทริบิวต์บนโหนดปัจจุบัน. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับ URI พื้นฐานของโหนดปัจจุบัน. |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | คืนค่าที่บ่งบอกว่า [XmlReader](./) มีการทำงานอ่านเนื้อหาแบบไบนารีหรือไม่. |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | คืนค่าที่บ่งบอกว่า [XmlReader](./) มีเมธอด [XmlReader::ReadValueChunk](./readvaluechunk/) หรือไม่. |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | คืนค่าที่บ่งบอกว่ารีดเดอร์นี้สามารถพาร์สและแก้ไขเอนทิตีได้หรือไม่. |
| virtual **int32_t** [get_Depth](./get_depth/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับความลึกของโหนดปัจจุบันในเอกสาร XML. |
| virtual **bool** [get_EOF](./get_eof/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าที่บ่งบอกว่ารีเดอร์อยู่ที่ส่วนท้ายของสตรีมหรือไม่. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | คืนค่าที่บ่งบอกว่าโหนดปัจจุบันมีแอตทริบิวต์หรือไม่. |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าที่บ่งบอกว่าโหนดปัจจุบันสามารถมีค่า [XmlReader::get_Value](./get_value/) ได้หรือไม่. |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าที่บ่งบอกว่าโหนดปัจจุบันเป็นแอตทริบิวต์ที่สร้างจากค่าเริ่มต้นที่กำหนดใน DTD หรือ schema หรือไม่. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าที่บ่งบอกว่าโหนดปัจจุบันเป็นเอลีเมนต์ว่าง (เช่น **<MyElement/>**) หรือไม่. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับชื่อท้องถิ่นของโหนดปัจจุบัน. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับชื่อที่สมบูรณ์ของโหนดปัจจุบัน. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับ URI ของเนมสเปซ (ตามการกำหนดของ W3C Namespace) ของโหนดที่รีดเดอร์อยู่. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับ [XmlNameTable](../xmlnametable/) ที่เกี่ยวข้องกับการนำไปใช้นี้. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับประเภทของโหนดปัจจุบัน. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับคำนำหน้าเนมสเปซที่เชื่อมโยงกับโหนดปัจจุบัน. |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับอักขระเครื่องหมายคำพูดที่ใช้ปิดล้อมค่าของแอตทริบิวต์โหนด. |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับสถานะของรีดเดอร์. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | คืนข้อมูลสคีมาที่ถูกกำหนดให้กับโหนดปัจจุบันจากการตรวจสอบสคีม. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | คืนวัตถุ [XmlReaderSettings](../xmlreadersettings/) ที่ใช้สร้างอินสแตนซ์ [XmlReader](./) นี้. |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าข้อความของโหนดปัจจุบัน. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | คืนค่าประเภทของโหนดปัจจุบัน. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับขอบเขต **xml:lang** ปัจจุบัน. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | เมื่อถูก override ในคลาสที่สืบทอด, รับขอบเขต **xml:space** ปัจจุบัน. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าของแอตทริบิวต์ที่มีค่า [XmlReader::get_Name](./get_name/) ที่ระบุ. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าของแอตทริบิวต์ที่มีค่า [XmlReader::get_LocalName](./get_localname/) และ [XmlReader::get_NamespaceURI](./get_namespaceuri/) ที่ระบุ. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าของแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชวัตถุที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าของแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าของแอตทริบิวต์ที่มีค่า [XmlReader::get_Name](./get_name/) ที่ระบุ. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | เมื่อถูก override ในคลาสที่สืบทอด, รับค่าของแอตทริบิวต์ที่มีค่า [XmlReader::get_LocalName](./get_localname/) และ [XmlReader::get_NamespaceURI](./get_namespaceuri/) ที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่ targetType บรรยายหรือไม่. เป็นอเนกประสงค์ของตัวดำเนินการ C# 'is'. |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | คืนค่าที่บ่งบอกว่าพารามิเตอร์สตริงเป็น XML name ที่ถูกต้องหรือไม่. |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | คืนค่าที่บ่งบอกว่าพารามิเตอร์สตริงเป็น token ของ XML name ที่ถูกต้องหรือไม่. |
| virtual **bool** [IsStartElement](./isstartelement/)() | เรียก [XmlReader::MoveToContent](./movetocontent/) และตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กเเลement ว่างหรือไม่. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | เรียก [XmlReader::MoveToContent](./movetocontent/) และตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กเเลement ว่าง และค่าของ [XmlReader::get_Name](./get_name/) ของเอลีเมนต์ที่พบตรงกับอาร์กิวเมนต์ที่ให้. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | เรียก [XmlReader::MoveToContent](./movetocontent/) และตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กเเลement ว่าง และค่าของ [XmlReader::get_LocalName](./get_localname/) และ [XmlReader::get_NamespaceURI](./get_namespaceuri/) ของเอลีเมนต์ที่พบตรงกับสตริงที่ให้. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | เมื่อถูก override ในคลาสที่สืบทอด, แก้ไขคำนำหน้าเนมสเปซในขอบเขตของเอลีเมนต์ปัจจุบัน. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | เมื่อถูก override ในคลาสที่สืบทอด, ย้ายไปยังแอตทริบิวต์ที่มีค่า [XmlReader::get_Name](./get_name/) ที่ระบุ. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | เมื่อถูก override ในคลาสที่สืบทอด, ย้ายไปยังแอตทริบิวต์ที่มีค่า [XmlReader::get_LocalName](./get_localname/) และ [XmlReader::get_NamespaceURI](./get_namespaceuri/) ที่ระบุ. |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | เมื่อถูก override ในคลาสที่สืบทอด, ย้ายไปยังแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | ตรวจสอบว่าโหนดปัจจุบันเป็นโหนดเนื้อหา (ข้อความที่ไม่ใช่ whitespace, **CDATA**, **Element**, **EndElement**, **EntityReference**, หรือ **EndEntity**) หรือไม่ หากไม่ใช่โหนดเนื้อหา รีดเดอร์จะข้ามไปยังโหนดเนื้อถัดไปหรือจบไฟล์ โดยข้ามโหนดประเภทต่อไปนี้: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, หรือ **SignificantWhitespace**. |
| virtual **bool** [MoveToElement](./movetoelement/)() | เมื่อถูก override ในคลาสที่สืบทอด, ย้ายไปยังเอลีเมนต์ที่บรรจุแอตทริบิวต์โหนดปัจจุบัน. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | เมื่อถูก override ในคลาสที่สืบทอด, ย้ายไปยังแอตทริบิวต์แรก. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | เมื่อถูก override ในคลาสที่สืบทอด, ย้ายไปยังแอตทริบิวต์ถัดไป. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| virtual **bool** [Read](./read/)() | เมื่อถูก override ในคลาสที่สืบทอด, อ่านโหนดถัดไปจากสตรีม. |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | เมื่อถูก override ในคลาสที่สืบทอด, พาร์สค่าของแอตทริบิวต์เป็นหนึ่งหรือหลายโหนด **[Text](../../system.text/)**, **EntityReference**, หรือ **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | อ่านเนื้อหาเป็นอ็อบเจ็กต์ของประเภทที่ระบุ. |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัส Base64 แล้ว. |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัส **BinHex** แล้ว. |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็น [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนทศนิยมความละเอียดคู่. |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนทศนิยมความละเอียดเดี่ยว. |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนเต็มที่มีเครื่องหมาย 32 บิต. |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนเต็มที่มีเครื่องหมาย 64 บิต. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็น [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | อ่านเนื้อหาองค์ประกอบเป็นประเภทที่ร้องขอ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน แล้วอ่านเนื้อหาองค์ประกอบเป็นประเภทที่ร้องขอ. |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | อ่านองค์ประกอบและถอดรหัสเนื้อหา **Base64**. |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | อ่านองค์ประกอบและถอดรหัสเนื้อหา **BinHex**. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน แล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน แล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน แล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนทศนิยมความละเอียดคู่. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน แล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนทศนิยมความละเอียดคู่. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนทศนิยมความละเอียดเดี่ยว. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน แล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนทศนิยมความละเอียดเดี่ยว. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็มที่มีเครื่องหมาย 32 บิต. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน แล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็มที่มีเครื่องหมาย 32 บิต. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็มที่มีเครื่องหมาย 64 บิต. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน แล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็มที่มีเครื่องหมาย 64 บิต. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็น [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสปลกัที่ระบุตรงกับขององค์ประกอบปัจจุบัน แล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็น [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบัน แล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | อ่านองค์ประกอบที่มีข้อความเท่านั้น อย่างไรก็ตามแนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) แทน เนื่องจากให้วิธีที่ตรงไปตรงมามากกว่าในการจัดการการดำเนินการนี้. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | ตรวจสอบว่าค่า [XmlReader::get_Name](./get_name/) ขององค์ประกอบที่พบตรงกับสตริงที่ให้ก่อนอ่านองค์ประกอบที่มีข้อความเท่านั้น อย่างไรก็ตามแนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) แทน เนื่องจากให้วิธีที่ตรงไปตรงมามากกว่าในการจัดการการดำเนินการนี้. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าค่า [XmlReader::get_LocalName](./get_localname/) และ [XmlReader::get_NamespaceURI](./get_namespaceuri/) ขององค์ประกอบที่พบตรงกับสตริงที่ให้ก่อนอ่านองค์ประกอบที่มีข้อความเท่านั้น อย่างไรก็ตามแนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) แทน เนื่องจากให้วิธีที่ตรงไปตรงมามากกว่าในการจัดการการดำเนินการนี้. |
| virtual void [ReadEndElement](./readendelement/)() | ตรวจสอบว่าโหนดเนื้อหาแบบปัจจุบันเป็นแท็กปิดและเลื่อนผู้อ่านไปยังโหนดถัดไป. |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | เมื่อทำการแโอเวอร์ไรด์ในคลาสที่สืบทอด จะอ่านเนื้อหาทั้งหมด รวมถึงมาร์กอัป เป็นสตริง. |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | เมื่อทำการแโอเวอร์ไรด์ในคลาสที่สืบทอด จะอ่านเนื้อหา รวมถึงมาร์กอัป ที่เป็นตัวแทนของโหนดนี้และโหนดลูกทั้งหมด. |
| virtual void [ReadStartElement](./readstartelement/)() | ตรวจสอบว่าโหนดปัจจุบันเป็นองค์ประกอบและเลื่อนผู้อ่านไปยังโหนดถัดไป. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | ตรวจสอบว่าโหนดเนื้อหาแบบปัจจุบันเป็นองค์ประกอบที่มีค่า [XmlReader::get_Name](./get_name/) ที่กำหนดและเลื่อนผู้อ่านไปยังโหนดถัดไป. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าโหนดเนื้อหาแบบปัจจุบันเป็นองค์ประกอบที่มีค่า [XmlReader::get_LocalName](./get_localname/) และ [XmlReader::get_NamespaceURI](./get_namespaceuri/) ที่กำหนดและเลื่อนผู้อ่านไปยังโหนดถัดไป. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | เมื่อทำการแโอเวอร์ไรด์ในคลาสที่สืบทอด จะอ่านเนื้อหาขององค์ประกอบหรือโหนดข้อความเป็นสตริง อย่างไรก็ตามแนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) แทน เนื่องจากให้วิธีที่ตรงไปตรงมามากกว่าในการจัดการการดำเนินการนี้. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | ส่งคืนอินสแตนซ์ [XmlReader](./) ใหม่ที่สามารถใช้เพื่ออ่านโหนดปัจจุบันและโหนดลูกทั้งหมดของมัน. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | เลื่อน [XmlReader](./) ไปยังองค์ประกอบ descendant ถัดไปที่มีชื่อเชิงคุณลักษณะที่ระบุ. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | เลื่อน [XmlReader](./) ไปยังองค์ประกอบ descendant ถัดไปที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | อ่านต่อจนกว่าจะพบองค์ประกอบที่มีชื่อเชิงคุณลักษณะที่ระบุ. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | อ่านต่อจนกว่าจะพบองค์ประกอบที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | เลื่อน [XmlReader](./) ไปยังองค์ประกอบพี่น้องถัดไปที่มีชื่อเชิงคุณลักษณะที่ระบุ. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | เลื่อน [XmlReader](./) ไปยังองค์ประกอบพี่น้องถัดไปที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | อ่านสตรีมข้อความขนาดใหญ่ที่ฝังอยู่ในเอกสาร XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| virtual void [ResolveEntity](./resolveentity/)() | เมื่อทำการแโอเวอร์ไรด์ในคลาสที่สืบทอด จะ resolve การอ้างอิงเอนทิตี้สำหรับโหนด **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) ซึ่งทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม ควรไม่เรียกโดยตรง; แทนนั้นให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและคืนค่า ควรไม่เรียกโดยตรง; แทนนั้นให้ใช้ smart pointers หรือ ThisProtector. |
| virtual void [Skip](./skip/)() | ข้ามลูกของโหนดปัจจุบัน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นออนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น construct typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกของคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิง weak ควรไม่เรียกโดยตรง; แทนนั้นให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิง weak ควรไม่เรียกโดยตรง; แทนนั้นให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## แบบกำหนดชื่อใหม่

| Typedef | รายละเอียด |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |
## ดูเพิ่มเติม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)