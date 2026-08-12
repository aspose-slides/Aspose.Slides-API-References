---
title: XmlSchema
second_title: Aspose.Slides for C++ เอกสารอ้างอิง API
description: การแสดงผลในหน่วยความจำของ XML Schema ตามที่กำหนดใน World Wide Web Consortium (W3C) และ .
type: docs
weight: 79
url: /th/system.xml.schema/xmlschema/
---
## คลาส XmlSchema


การแสดงผลในหน่วยความจำของ XML [Schema](../) ตามที่กำหนดใน World Wide [Web](../../system.web/) Consortium (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) และ [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/).

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## เมธอด

| Method | Description |
| --- | --- |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/)) | ทำการคอมไพล์ XML [Schema](../)[Object](../../system/object/) Model (SOM) เป็นข้อมูลสกีมาสสำหรับการตรวจสอบความถูกต้อง ใช้เพื่อตรวจสอบโครงสร้างเชิงไวยากรณ์และเชิงความหมายของ SOM ที่สร้างโดยโปรแกรม การตรวจสอบความหมายจะดำเนินการในระหว่างการคอมไพล์ |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | ทำการคอมไพล์ XML [Schema](../)[Object](../../system/object/) Model (SOM) เป็นข้อมูลสกีมาสสำหรับการตรวจสอบความถูกต้อง ใช้เพื่อตรวจสอบโครงสร้างเชิงไวยากรณ์และเชิงความหมายของ SOM ที่สร้างโดยโปรแกรม การตรวจสอบความหมายจะดำเนินการในระหว่างการคอมไพล์ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่า ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่า ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการภายในเท่านั้น |
| [XmlSchemaForm](../xmlschemaform/) [get_AttributeFormDefault](./get_attributeformdefault/)() | คืนค่าแบบฟอร์มสำหรับแอตทริบิวท์ที่ประกาศในเนมสเปซเป้าหมายของสกีม่า |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | คืนค่าผลลัพธ์หลังการคอมไพล์สกีม่าสำหรับกลุ่มแอตทริบิวท์ทั่วโลกทั้งหมดในสกีม่า |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Attributes](./get_attributes/)() | คืนค่าผลลัพธ์หลังการคอมไพล์สกีม่าสำหรับแอตทริบิวท์ทั้งหมดในสกีม่า |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockDefault](./get_blockdefault/)() | คืนค่าแอตทริบิวท์ **blockDefault** ซึ่งกำหนดค่าปริยายของแอตทริบิวท์ **block** บนเอลิเมนต์และประเภทซับซ้อนใน **targetNamespace** ของสกีม่า |
| [XmlSchemaForm](../xmlschemaform/) [get_ElementFormDefault](./get_elementformdefault/)() | คืนค่าแบบฟอร์มสำหรับเอลิเมนต์ที่ประกาศในเนมสเปซเป้าหมายของสกีม่า |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Elements](./get_elements/)() | คืนค่าผลลัพธ์หลังการคอมไพล์สกีม่าสำหรับเอลิเมนต์ทั้งหมดในสกีม่า |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalDefault](./get_finaldefault/)() | คืนค่าแอตทริบิวท์ **finalDefault** ซึ่งกำหนดค่าปริยายของแอตทริบิวท์ **final** บนเอลิเมนต์และประเภทซับซ้อนในเนมสเปซเป้าหมายของสกีม่า |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | คืนค่าผลลัพธ์หลังการคอมไพล์สกีม่าสำหรับกลุ่มทั้งหมดในสกีม่า |
| [String](../../system/string/) [get_Id](./get_id/)() | คืนค่า ID ของสตริง |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Includes](./get_includes/)() | คืนคอลเลกชันของสกีม่าที่รวมและนำเข้า |
| **bool** [get_IsCompiled](./get_iscompiled/)() | ระบุว่ารูปแบบสกีม่าได้รับการคอมไพล์หรือไม่ |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | คืนคอลเลกชันขององค์ประกอบสกีม่าในสกีม่าและใช้สำหรับเพิ่มประเภทเอลิเมนต์ใหม่ในระดับเอลิเมนต์ **schema** |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | คืนหมายเลขบรรทัดในไฟล์ที่เอลิเมนต์ **schema** อ้างอิงอยู่ |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | คืนตำแหน่งบรรทัดในไฟล์ที่เอลิเมนต์ **schema** อ้างอิงอยู่ |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | คืนค่า XmlSerializerNamespaces ที่จะใช้กับอ็อบเจ็กต์สกีม่านี้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Notations](./get_notations/)() | คืนค่าผลลัพธ์หลังการคอมไพล์สกีม่าสำหรับโนเทชั่นทั้งหมดในสกีม่า |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | คืนค่าพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | คืนค่าผลลัพธ์หลังการคอมไพล์สกีม่าสำหรับประเภทสกีม่าทั้งหมดในสกีม่า |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | คืนตำแหน่งต้นทางของไฟล์ที่โหลดสกีม่า |
| [String](../../system/string/) [get_TargetNamespace](./get_targetnamespace/)() | คืน Uniform Resource Identifier (URI) ของเนมสเปซเป้าหมายของสกีม่า |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](./get_unhandledattributes/)() | คืนแอตทริบิวท์ที่มีคุณสมบัติครบถ้วนซึ่งไม่อยู่ในเนมสเปซเป้าหมายของสกีม่า |
| [String](../../system/string/) [get_Version](./get_version/)() | คืนเวอร์ชันของสกีม่า |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ช่วยให้สามารถทำแฮชสำหรับอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจ็กต์ เป็นคล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นคล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อคตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นคล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ช่วยให้สามารถคัดลอกประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์และเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริงๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | อ่าน XML [Schema](../) จาก [IO::TextReader](../../system.io/textreader/) ที่ให้มา |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | อ่าน XML [Schema](../) จากสตรีมที่ให้มา |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | อ่าน XML [Schema](../) จาก [XmlReader](../../system.xml/xmlreader/) ที่ให้มา |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เป็นการเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เป็นการเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_AttributeFormDefault](./set_attributeformdefault/)([XmlSchemaForm](../xmlschemaform/)) | ตั้งค่าแบบฟอร์มสำหรับแอตทริบิวท์ที่ประกาศในเนมสเปซเป้าหมายของสกีม่า |
| void [set_BlockDefault](./set_blockdefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | ตั้งค่าแอตทริบิวท์ **blockDefault** ซึ่งกำหนดค่าปริยายของแอตทริบิวท์ **block** บนเอลิเมนต์และประเภทซับซ้อนใน **targetNamespace** ของสกีม่า |
| void [set_ElementFormDefault](./set_elementformdefault/)([XmlSchemaForm](../xmlschemaform/)) | ตั้งค่าแบบฟอร์มสำหรับเอลิเมนต์ที่ประกาศในเนมสเปซเป้าหมายของสกีม่า |
| void [set_FinalDefault](./set_finaldefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | ตั้งค่าแอตทริบิวท์ **finalDefault** ซึ่งกำหนดค่าปริยายของแอตทริบิวท์ **final** บนเอลิเมนต์และประเภทซับซ้อนในเนมสเปซของสกีม่า |
| void [set_Id](./set_id/)(const [String](../../system/string/)\&) | ตั้งค่า ID ของสตริง |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | ตั้งค่าหมายเลขบรรทัดในไฟล์ที่เอลิเมนต์ **schema** อ้างอิง |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | ตั้งค่าตำแหน่งบรรทัดในไฟล์ที่เอลิเมนต์ **schema** อ้างอิง |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | ตั้งค่า XmlSerializerNamespaces ที่จะใช้กับอ็อบเจ็กต์สกีม่านี้ |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | ตั้งค่าพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้ |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | ตั้งค่าตำแหน่งต้นทางของไฟล์ที่โหลดสกีม่า |
| void [set_TargetNamespace](./set_targetnamespace/)(const [String](../../system/string/)\&) | ตั้งค่า Uniform Resource Identifier (URI) ของเนมสเปซเป้าหมายของสกีม่า |
| void [set_UnhandledAttributes](./set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ตั้งค่าแอตทริบิวท์ที่มีคุณสมบัติครบถ้วนซึ่งไม่อยู่ในเนมสเปซของสกีม่า |
| void [set_Version](./set_version/)(const [String](../../system/string/)\&) | ตั้งค่าเวอร์ชันของสกีม่า |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดตัวนับอ้างอิงที่แชร์และคืนค่า ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นคล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ช่วยให้แปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อคตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | เขียน XML [Schema](../) ไปยังสตรีมข้อมูลที่ให้มา |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | เขียน XML [Schema](../) ไปยังสตรีมที่ให้โดยใช้ [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) ที่ระบุ |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | เขียน XML [Schema](../) ไปยัง [IO::TextWriter](../../system.io/textwriter/) ที่ให้ |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | เขียน XML [Schema](../) ไปยัง TextWriter ที่ให้ |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | เขียน XML [Schema](../) ไปยัง [XmlWriter](../../system.xml/xmlwriter/) ที่ให้ |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | เขียน XML [Schema](../) ไปยัง [XmlWriter](../../system.xml/xmlwriter/) ที่ให้ |
|  [XmlSchema](./xmlschema/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchema](./) |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/) |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์และคืนโครงสร้างข้อมูลภายในทั้งหมด |

## ฟิลด์

| Field | Description |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | เนมสเปซของอินสแตนซ์ XML schema. ฟิลด์นี้เป็นค่าคงที่ |
| static [Namespace](./namespace/) | เนมสเปซของ XML schema. ฟิลด์นี้เป็นค่าคงที่ |

## การนิยามประเภท

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | อัลิอาสสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้ |

## หมายเหตุ



อ็อบเจ็กต์ของคลาสนี้ควรถูกจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้โอเปอร์เรเตอร์ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการแจ้งเตือนการอ้างอิง ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

## ดูเพิ่มเติม

* คลาส [XmlSchemaObject](../xmlschemaobject/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)