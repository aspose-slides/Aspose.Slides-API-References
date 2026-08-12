---
title: XmlNodeReader
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แสดงถึงผู้อ่านที่ให้การเข้าถึงข้อมูล XML ใน XmlNode อย่างรวดเร็วโดยไม่ใช้แคชและเข้าถึงได้แบบไปข้างหน้าเท่านั้น
type: docs
weight: 365
url: /th/system.xml/xmlnodereader/
---
## XmlNodeReader คลาส

แสดงถึงรีเดอร์ที่ให้การเข้าถึงข้อมูล XML อย่างรวดเร็ว ไม่ผ่านแคช และเดินหน้าอย่างเดียวใน [XmlNode](../xmlnode/).

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Methods

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | เปลี่ยน [XmlNodeReader::get_ReadState](./get_readstate/) เป็น [ReadState::Closed](../readstate/). |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) ด้วย URI ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้ URI และการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้ URI ที่ระบุ การตั้งค่า และข้อมูลบริบทสำหรับการพาร์ส. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้สตรีมที่ระบุพร้อมการตั้งค่าเริ่มต้น. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) ด้วยสตรีมและการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้สตรีมที่ระบุ URI ฐาน และการตั้งค่า. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) โดยใช้สตรีม การตั้งค่า และข้อมูลบริบทสำหรับการพาร์ส. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) ด้วยตัวอ่านข้อความที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) ด้วยตัวอ่านข้อความและการตั้งค่าที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) ด้วยตัวอ่านข้อความ การตั้งค่า และ URI ฐานที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) ด้วยตัวอ่านข้อความ การตั้งค่า และข้อมูลบริบทสำหรับการพาร์ส. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | สร้างอินสแตนซ์ใหม่ของ [XmlReader](../xmlreader/) ด้วยตัวอ่าน XML และการตั้งค่าที่ระบุ. |
| void [Dispose](../xmlreader/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอินสแตนซ์ปัจจุบันของคลาส [XmlReader](../xmlreader/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองตัวถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองตัวถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | คืนค่าจำนวนแอตทริบิวต์บนโหนดปัจจุบัน. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | คืนค่า base URI ของโหนดปัจจุบัน. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | คืนค่าที่บ่งบอกว่า [XmlNodeReader](./) รองรับเมธอดการอ่านเนื้อหาบินารีหรือไม่. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | คืนค่าที่บ่งบอกว่า [XmlReader](../xmlreader/) รองรับเมธอด [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) หรือไม่. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | คืนค่าที่บ่งบอกว่ารีเดอร์นี้สามารถพาร์สและแก้ไขเอนทิตี้ได้หรือไม่. |
| **int32_t** [get_Depth](./get_depth/)() override | คืนค่าความลึกของโหนดปัจจุบันในเอกสาร XML. |
| **bool** [get_EOF](./get_eof/)() override | คืนค่าที่บ่งบอกว่ารีเดอร์อยู่ที่ตำแหน่งสุดท้ายของสตรีมหรือไม่. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | คืนค่าที่บ่งบอกว่าโหนดปัจจุบันมีแอตทริบิวต์หรือไม่. |
| **bool** [get_HasValue](./get_hasvalue/)() override | คืนค่าที่บ่งบอกว่าโหนดปัจจุบันสามารถมีค่า [XmlNodeReader::get_Value](./get_value/) ได้หรือไม่. |
| **bool** [get_IsDefault](./get_isdefault/)() override | คืนค่าที่บ่งบอกว่าโหนดปัจจุบันเป็นแอตทริบิวต์ที่สร้างจากค่าเริ่มต้นที่กำหนดใน DTD หรือสคีมาหรือไม่. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | คืนค่าที่บ่งบอกว่าโหนดปัจจุบันเป็นเอลิเมนต์ว่าง (เช่น **<MyElement/>**) หรือไม่. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | คืนค่าชื่อโลคัลของโหนดปัจจุบัน. |
| [String](../../system/string/) [get_Name](./get_name/)() override | คืนค่าชื่อเต็ม (qualified name) ของโหนดปัจจุบัน. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | คืนค่า namespace URI (ตามที่กำหนดในสเปค W3C Namespace) ของโหนดที่รีเดอร์อยู่. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | คืนค่า [XmlNameTable](../xmlnametable/) ที่เกี่ยวข้องกับการทำงานนี้. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | คืนค่าประเภทของโหนดปัจจุบัน. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | คืนค่าพรีฟิกซ์ของ namespace ที่เกี่ยวข้องกับโหนดปัจจุบัน. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | เมื่อถูกโอเวอร์ไรด์ในคลาสย่อย จะได้รับอักขระเครื่องหมายอัญประกาศที่ใช้ล้อมค่าของโหนดแอตทริบิวต์. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | คืนค่าสถานะของรีเดอร์. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | คืนข้อมูลสกีมาที่ได้กำหนดให้กับโหนดปัจจุบัน. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | คืนอ็อบเจ็กต์ [XmlReaderSettings](../xmlreadersettings/) ที่ใช้สร้างอินสแตนซ์ [XmlReader](../xmlreader/) นี้. |
| [String](../../system/string/) [get_Value](./get_value/)() override | คืนค่าข้อความของโหนดปัจจุบัน. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | คืนค่าประเภทของโหนดปัจจุบัน. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | คืนค่า scope ของ **xml:lang** ปัจจุบัน. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | คืนค่า scope ของ **xml:space** ปัจจุบัน. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | คืนค่าของแอตทริบิวต์ที่มีชื่อที่ระบุ. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | คืนค่ของแอตทริบิวต์ที่มีชื่อโลคัลและ namespace URI ที่ระบุ. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | คืนค่าของแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อันาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. อันาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | เมื่อโอเวอร์ไรด์ในคลาสย่อย จะได้ค่าของแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | เมื่อโอเวอร์ไรด์ในคลาสย่อย จะได้ค่าของแอตทริบิวต์ที่มีค่า [XmlReader::get_Name](../xmlreader/get_name/) ที่ระบุ. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | เมื่อโอเวอร์ไรด์ในคลาสย่อย จะได้ค่าของแอตทริบิวต์ที่มีค่า [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ targetType อธิบายหรือไม่. อันาล็อกของออปะเรเตอร์ C# 'is'. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | คืนค่าที่บ่งบอกว่าสตริงที่ส่งมาคือชื่อ XML ที่ถูกต้องหรือไม่. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | คืนค่าที่บ่งบอกว่าสตริงที่ส่งมาคือ token ชื่อ XML ที่ถูกต้องหรือไม่. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | เรียก [XmlReader::MoveToContent](../xmlreader/movetocontent/) และตรวจสอบว่าโหนดคอนเทนท์ปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กเอลิเมนต์ว่างหรือไม่. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | เรียก [XmlReader::MoveToContent](../xmlreader/movetocontent/) และตรวจสอบว่าโหนดคอนเทนท์ปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กเอลิเมนต์ว่างและค่าของ [XmlReader::get_Name](../xmlreader/get_name/) ของเอลิเมนต์ที่พบตรงกับอาร์กิวเมนต์ที่ให้หรือไม่. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | เรียก [XmlReader::MoveToContent](../xmlreader/movetocontent/) และตรวจสอบว่าโหนดคอนเทนท์ปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กเอลิเมนต์ว่างและค่าของ [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ของเอลิเมนต์ที่พบตรงกับสตริงที่ให้หรือไม่. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | แก้ไข namespace prefix ในสโคปของเอลิเมนต์ปัจจุบัน. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อันาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดการคล cloning ประเภทที่กำหนดเอง. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | ย้ายไปยังแอตทริบิวต์ที่มีชื่อที่ระบุ. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | ย้ายไปยังแอตทริบิวต์ที่มีชื่อโลคัลและ namespace URI ที่ระบุ. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | ย้ายไปยังแอตทริบิวต์ที่มีดัชนีที่ระบุ. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | ตรวจสอบว่าโหนดปัจจุบันเป็นโหนดคอนเทนท์ (ข้อความที่ไม่เป็นช่องว่าง, **CDATA**, **Element**, **EndElement**, **EntityReference**, หรือ **EndEntity**) หรือไม่. หากไม่ใช่ โรีเดอร์จะข้ามไปยังโหนดคอนเทนท์ถัดไปหรือจนจบไฟล์. จะข้ามโหนดประเภทต่อไปนี้: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, หรือ **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | ย้ายไปยังเอลิเมนต์ที่บรรจุแอตทริบิวต์โหนดปัจจุบัน. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | ย้ายไปยังแอตทริบิวต์แรก. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | ย้ายไปยังแอตทริบิวต์ถัดไป. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์สำหรับซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์สำหรับซับคลาส. |
| **bool** [Read](./read/)() override | อ่านโหนดถัดไปจากสตรีม. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | พาร์สค่าของแอตทริบิวต์เป็นหนึ่งหรือหลายโหนด **[Text](../../system.text/)**, **EntityReference**, หรือ **EndEntity**. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | อ่านเนื้อหาเป็นอ็อบเจ็กต์ของประเภทที่ระบุ. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก Base64. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านเนื้อหาและคืนค่าไบต์ไบนารีที่ถอดรหัสจาก BinHex. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็น [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [DateTimeOffset](../../system/datetimeoffset/). |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นเลขจุดลอยทศนิยมความแม่นยำคู่. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นเลขจุดลอยทศนิยมความแม่นยำเดี่ยว. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนเต็ม 32-bit ที่มีเครื่องหมาย. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นจำนวนเต็ม 64-bit ที่มีเครื่องหมาย. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็น [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | อ่านเนื้อหาข้อความที่ตำแหน่งปัจจุบันเป็นอ็อบเจ็กต์ [String](../../system/string/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | อ่านเนื้อหาองค์ประกอบเป็นประเภทที่ร้องขอ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันแล้วอ่านเนื้อหาองค์ประกอบเป็นประเภทที่ร้องขอ. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านองค์ประกอบและถอดรหัสเนื้อหา Base64. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | อ่านองค์ประกอบและถอดรหัสเนื้อหา BinHex. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [Boolean](../../system/boolean/). |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันแล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันแล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [DateTime](../../system/datetime/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันแล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [Decimal](../../system/decimal/). |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นตัวเลขจำนวนจริงแบบ double-precision. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันแล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นตัวเลขจำนวนจริงแบบ double-precision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นตัวเลขจำนวนจริงแบบ single-precision. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันแล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นตัวเลขจำนวนจริงแบบ single-precision. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็ม 32-บิตที่มีเครื่องหมาย. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันแล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็ม 32-บิตที่มีเครื่องหมาย. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็ม 64-บิตที่มีเครื่องหมาย. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันแล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นจำนวนเต็ม 64-บิตที่มีเครื่องหมาย. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็น [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันแล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็น [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | อ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตรงกับขององค์ประกอบปัจจุบันแล้วอ่านองค์ประกอบปัจจุบันและคืนค่าเนื้อหาเป็นอ็อบเจ็กต์ [String](../../system/string/). |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | อ่านองค์ประกอบที่มีเฉพาะข้อความ อย่างไรก็ตามแนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) แทน เนื่องจากให้วิธีการที่ตรงไปตรงมามากกว่าในการดำเนินการนี้. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | ตรวจสอบว่า value [XmlReader::get_Name](../xmlreader/get_name/) ขององค์ประกอบที่พบตรงกับสตริงที่ให้ก่อนอ่านองค์ประกอบที่มีเฉพาะข้อความ อย่างไรก็ตามแนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) แทน เนื่องจากให้วิธีการที่ตรงไปตรงมามากกว่าในการดำเนินการนี้. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่า value [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ขององค์ประกอบที่พบตรงกับสตริงที่ให้ก่อนอ่านองค์ประกอบที่มีเฉพาะข้อความ อย่างไรก็ตามแนะนำให้ใช้เมธอด [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) แทน เนื่องจากให้วิธีการที่ตรงไปตรงมามากกว่าในการดำเนินการนี้. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | ตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นแท็กสิ้นสุดและเลื่อนตัวอ่านไปยังโหนดต่อไป. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | เมื่อถูกเขียนทับในคลาสที่สืบทอดแล้ว จะอ่านเนื้อหาทั้งหมดรวมถึง markup เป็นสตริง. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | เมื่อถูกเขียนทับในคลาสที่สืบทอดแล้ว จะอ่านเนื้อหา รวมถึง markup ที่เป็นตัวแทนของโหนดนี้และโหนดลูกทั้งหมด. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | ตรวจสอบว่าโหนดปัจจุบันเป็นองค์ประกอบและเลื่อนตัวอ่านไปยังโหนดต่อไป. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | ตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นองค์ประกอบที่มีค่า [XmlReader::get_Name](../xmlreader/get_name/) ตามที่ระบุและเลื่อนตัวอ่านไปยังโหนดต่อไป. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่าโหนดเนื้อหาปัจจุบันเป็นองค์ประกอบที่มีค่า [XmlReader::get_LocalName](../xmlreader/get_localname/) และ [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) ตามที่ระบุและเลื่อนตัวอ่านไปยังโหนดต่อไป. |
| [String](../../system/string/) [ReadString](./readstring/)() override | อ่านเนื้อหาขององค์ประกอบหรือโหนดข้อความเป็นสตริง. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | คืนค่าอินสแตนซ์ [XmlReader](../xmlreader/) ใหม่ที่สามารถใช้เพื่ออ่านโหนดปัจจุบันและโหนดลูกทั้งหมด. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบลูกต่อไปที่มีชื่อแบบเต็มที่ระบุ. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบลูกต่อไปที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | อ่านต่อจนกว่าจะพบองค์ประกอบที่มีชื่อแบบเต็มที่ระบุ. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | อ่านต่อจนกว่าจะพบองค์ประกอบที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบพี่น้องต่อไปที่มีชื่อแบบเต็มที่ระบุ. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | เลื่อน [XmlReader](../xmlreader/) ไปยังองค์ประกอบพี่น้องต่อไปที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | อ่านสตรีมข้อความขนาดใหญ่ที่ฝังอยู่ในเอกสาร XML. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ชนิดค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [ResolveEntity](./resolveentity/)() override | แก้ไขการอ้างอิงเอนทิตี้สำหรับโหนด **EntityReference**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [Skip](./skip/)() override | ข้ามโหนดลูกของโหนดปัจจุบัน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือน C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | สร้างอินสแตนซ์ของคลาส [XmlNodeReader](./) โดยใช้ [XmlNode](../xmlnode/) ที่ระบุ. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## การกำหนดประเภท

| Typedef | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## ดูเพิ่มเติม

* คลาส [XmlReader](../xmlreader/)
* คลาส [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)