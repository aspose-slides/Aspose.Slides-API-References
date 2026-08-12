---
title: XPathNavigator
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้โมเดลเคอร์เซอร์สำหรับการนำทางและแก้ไขข้อมูล XML
type: docs
weight: 66
url: /th/system.xml.xpath/xpathnavigator/
---
## XPathNavigator คลาส

Provides a cursor model for navigating and editing XML data.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | ส่งกลับวัตถุ [XmlWriter](../../system.xml/xmlwriter/) ที่ใช้เพื่อสร้างหนึ่งหรือหลายโหนดลูกใหม่ที่ส่วนท้ายของรายการโหนดลูกของโหนดปัจจุบัน |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | สร้างโหนดลูกใหม่ที่ส่วนท้ายของรายการโหนดลูกของโหนดปัจจุบันโดยใช้สตริงข้อมูล XML ที่ระบุ |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | สร้างโหนดลูกใหม่ที่ส่วนท้ายของรายการโหนดลูกของโหนดปัจจุบันโดยใช้เนื้อหา XML ของวัตถุ [XmlReader](../../system.xml/xmlreader/) ที่ระบุ |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | สร้างโหนดลูกใหม่ที่ส่วนท้ายของรายการโหนดลูกของโหนดปัจจุบันโดยใช้โหนดใน [XPathNavigator](./) ที่ระบุ |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | สร้างโหนดองค์ประกอบลูกใหม่ที่ส่วนท้ายของรายการโหนดลูกของโหนดปัจจุบันโดยใช้คำนำหน้าช่วงชื่อ, ชื่อท้องถิ่นและ URI ของช่วงชื่อที่ระบุพร้อมค่าที่ระบุ |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | ตรวจสอบว่าข้อมูล XML ใน [XPathNavigator](./) สอดคล้องกับสคีมาภาษา [Schema](../../system.xml.schema/) (XSD) ที่ให้ไว้ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะสร้าง [XPathNavigator](./) ใหม่ที่อยู่ตำแหน่งเดียวกับ [XPathNavigator](./) นี้ |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | เปรียบเทียบตำแหน่งของ [XPathNavigator](./) ปัจจุบันกับตำแหน่งของ [XPathNavigator](./) ที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | คอมไพล์สตริงที่เป็นตัวแทนของนิพจน์ [XPath](../) แล้วส่งกลับวัตถุ [XPathExpression](../xpathexpression/) |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | สร้างโหนดแอตทริบิวต์บนโหนดอีลีเมนต์ปัจจุบันโดยใช้คำนำหน้าช่วงชื่อ, ชื่อท้องถิ่นและ URI ของช่วงชื่อที่ระบุพร้อมค่าที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | ส่งกลับวัตถุ [XmlWriter](../../system.xml/xmlwriter/) ที่ใช้เพื่อสร้างแอตทริบิวต์ใหม่บนอีลีเมนต์ปัจจุบัน |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | ส่งกลับสำเนาของ [XPathNavigator](./) |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | ลบช่วงของโหนดพี่น้องตั้งแต่โหนดปัจจุบันจนถึงโหนดที่ระบุ |
| virtual void [DeleteSelf](./deleteself/)() | ลบโหนดปัจจุบันและโหนดลูกของมัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. เปิดใช้งานการทำแฮชของวัตถุที่กำหนดเอง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. เปิดใช้งานการทำแฮชของวัตถุที่กำหนดเอง |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตามสไตล์ C# ซึ่ง NaN สองค่าเป็นศูนย์เดียวกันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ double ตามสไตล์ C# ซึ่ง NaN สองค่าเป็นศูนย์เดียวกันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | ประเมินนิพจน์ [XPath](../) ที่ระบุและส่งกลับผลลัพธ์ที่มีประเภท |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | ประเมินนิพจน์ [XPath](../) ที่ระบุและส่งกลับผลลัพธ์ที่มีประเภท โดยใช้วัตถุ [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) ที่ระบุเพื่อแก้ไขคำนำหน้าช่วงชื่อในนิพจน์ [XPath](../) |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | ประเมิน [XPathExpression](../xpathexpression/) แล้วส่งกลับผลลัพธ์ที่มีประเภท |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | ใช้บริบทที่ได้รับเพื่อประเมิน [XPathExpression](../xpathexpression/) และส่งกลับผลลัพธ์ที่มีประเภท |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะรับ URI พื้นฐานของโหนดปัจจุบัน |
| virtual **bool** [get_CanEdit](./get_canedit/)() | ส่งคืนค่าที่บ่งบอกว่า [XPathNavigator](./) สามารถแก้ไขข้อมูล XML พื้นฐานได้หรือไม่ |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | ส่งคืนค่าที่บ่งบอกว่าโหนดปัจจุบันมีแอตทริบิวต์หรือไม่ |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | ส่งคืนค่าที่บ่งบอกว่าโหนดปัจจุบันมีโหนดลูกหรือไม่ |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | ส่งคืนมาร์คอัปที่แสดงโหนดลูกของโหนดปัจจุบัน |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะรับค่าที่บ่งบอกว่าโหนดปัจจุบันเป็นองค์ประกอบว่างที่ไม่มีแท็กปิดหรือไม่ |
| **bool** [get_IsNode](./get_isnode/)() override | ส่งคืนค่าที่บ่งบอกว่าโหนดปัจจุบันเป็นโหนด [XPath](../) หรือไม่ |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะรับ [XPathNavigator::get_Name](./get_name/) ของโหนดปัจจุบันโดยไม่มีคำนำหน้าช่วงชื่อ |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะรับชื่อที่สมบูรณ์ของโหนดปัจจุบัน |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะรับ URI ของช่วงชื่อของโหนดปัจจุบัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะรับ [XmlNameTable](../../system.xml/xmlnametable/) ของ [XPathNavigator](./) |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | ส่งคืน [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) ที่ใช้สำหรับการเปรียบเทียบความเท่าเทียมของวัตถุ [XPathNavigator](./) |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะรับ XPathNodeType ของโหนดปัจจุบัน |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | ส่งคืนมาร์คอัปที่แสดงแท็กเปิดและปิดของโหนดปัจจุบันและโหนดลูกของมัน |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะรับคำนำหน้าช่วงชื่อที่เชื่อมโยงกับโหนดปัจจุบัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | ส่งคืนข้อมูลสคีมาที่ได้รับการกำหนดให้กับโหนดปัจจุบันเป็นผลจากการตรวจสอบสคีมา |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | ส่งคืนโหนดปัจจุบันในรูปแบบอ็อบเจ็กต์บ็อกซ์ของประเภทที่เหมาะสมที่สุด |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | ใช้โดย [XPathNavigator](./) implementations which provide a \"virtualized\" XML view over a store, to provide access to underlying objects |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะรับค่า **string** ของรายการ |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | ส่งคืนค่าของโหนดปัจจุบันในรูปแบบ [Boolean](../../system/boolean/) |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | ส่งคืนค่าของโหนดปัจจุบันในรูปแบบ [DateTime](../../system/datetime/) |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | ส่งคืนค่าของโหนดปัจจุบันในรูปแบบ [Double](../../system/double/) |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | ส่งคืนค่ของโหนดปัจจุบันในรูปแบบ [Int32](../../system/int32/) |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | ส่งคืนค่าของโหนดปัจจุบันในรูปแบบ [Int64](../../system/int64/) |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | ส่งคืนประเภทของโหนดปัจจุบัน |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | ส่งคืน **xml:lang** scope ของโหนดปัจจุบัน |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | ส่งคืนข้อมูล XmlSchemaType ของโหนดปัจจุบัน |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | ส่งคืนค่าของแอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ของช่วงชื่อที่ระบุ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการทำแฮชของวัตถุที่กำหนดเอง |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | ส่งคืนค่าของโหนดช่วงชื่อที่สอดคล้องกับชื่อท้องที่ที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | ส่งคืนช่วงชื่อที่อยู่ในขอบเขตของโหนดปัจจุบัน |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | ส่งคืนวัตถุ [XmlWriter](../../system.xml/xmlwriter/) ที่ใช้เพื่อสร้างโหนดพี่น้องใหม่หลังจากโหนดที่เลือกอยู่ |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | สร้างโหนดพี่น้องใหม่หลังจากโหนดที่เลือกอยู่โดยใช้สตริง XML ที่ระบุ |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | สร้างโหนดพี่น้องใหม่หลังจากโหนดที่เลือกอยู่โดยใช้เนื้อหา XML ของวัตถุ [XmlReader](../../system.xml/xmlreader/) ที่ระบุ |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | สร้างโหนดพี่น้องใหม่หลังจากโหนดที่เลือกอยู่โดยใช้โหนดในวัตถุ [XPathNavigator](./) ที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | ส่งคืนวัตถุ [XmlWriter](../../system.xml/xmlwriter/) ที่ใช้เพื่อสร้างโหนดพี่น้องใหม่ก่อนโหนดที่เลือกอยู่ |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | สร้างโหนดพี่น้องใหม่ก่อนโหนดที่เลือกอยู่โดยใช้สตริง XML ที่ระบุ |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | สร้างโหนดพี่น้องใหม่ก่อนโหนดที่เลือกอยู่โดยใช้เนื้อหา XML ของวัตถุ [XmlReader](../../system.xml/xmlreader/) ที่ระบุ |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | สร้างโหนดพี่น้องใหม่ก่อนโหนดที่เลือกอยู่โดยใช้โหนดใน [XPathNavigator](./) ที่ระบุ |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | สร้างองค์ประกอบพี่น้องใหม่หลังจากโหนดปัจจุบันโดยใช้คำนำหน้าช่วงชื่อ, ชื่อท้องถิ่นและ URI ของช่วงชื่อที่ระบุ พร้อมค่าที่ระบุ |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | สร้างองค์ประกอบพี่น้องใหม่ก่อนโหนดปัจจุบันโดยใช้คำนำหน้าช่วงชื่อ, ชื่อท้องถิ่นและ URI ของช่วงชื่อที่ระบุ พร้อมค่าที่ระบุ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่ามีอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นอนาล็อกของตัวดำเนินการ 'is' ของ C# |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | กำหนดว่าที่ระบุ [XPathNavigator](./) เป็นทายาทของ [XPathNavigator](./) ปัจจุบันหรือไม่ |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะกำหนดว่า [XPathNavigator](./) ปัจจุบันอยู่ตำแหน่งเดียวกับ [XPathNavigator](./) ที่ระบุหรือไม่ |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | ส่งคืน URI ของช่วงชื่อสำหรับคำนำหน้าที่ระบุ |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | ส่งคืนคำนำหน้าที่ประกาศสำหรับ URI ของช่วงชื่อที่ระบุ |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | กำหนดว่าโหนดปัจจุบันตรงกับ [XPathExpression](../xpathexpression/) ที่ระบุหรือไม่ |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | กำหนดว่าโหนดปัจจุบันตรงกับนิพจน์ [XPath](../) ที่ระบุหรือไม่ |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะย้าย [XPathNavigator](./) ไปยังตำแหน่งเดียวกับ [XPathNavigator](./) ที่ระบุ |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | ย้าย [XPathNavigator](./) ไปยังแอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ของช่วงชื่อที่ตรงกัน |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | ย้าย [XPathNavigator](./) ไปยังโหนดลูกที่มีชื่อท้องถิ่นและ URI ของช่วงชื่อที่ระบุ |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | ย้าย [XPathNavigator](./) ไปยังโหนดลูกของ XPathNodeType ที่ระบุ |
| virtual **bool** [MoveToFirst](./movetofirst/)() | ย้าย [XPathNavigator](./) ไปยังโหนดพี่น้องแรกของโหนดปัจจุบัน |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะย้าย [XPathNavigator](./) ไปยังแอตทริบิวต์แรกของโหนดปัจจุบัน |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะย้าย [XPathNavigator](./) ไปยังโหนดลูกแรกของโหนดปัจจุบัน |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | เมื่อถูกแทนที่ในคลาสที่สืบทอด, จะย้าย [XPathNavigator](./) ไปยังโหนดช่วงชื่อแรกที่ตรงกับ XPathNamespaceScope ที่ระบุ |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | ย้าย [XPathNavigator](./) ไปยังโหนดเนมสเปซแรกของโหนดปัจจุบัน |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | ย้าย [XPathNavigator](./) ไปยังเอลีเมนต์ที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุตามลำดับเอกสาร |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | ย้าย [XPathNavigator](./) ไปยังเอลีเมนต์ที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ, ไปยังขอบเขตที่ระบุ, ตามลำดับเอกสาร |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | ย้าย [XPathNavigator](./) ไปยังเอลีเมนต์ถัดไปของ XPathNodeType ที่ระบุตามลำดับเอกสาร |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | ย้าย [XPathNavigator](./) ไปยังเอลีเมนต์ถัดไปของ XPathNodeType ที่ระบุ, ไปยังขอบเขตที่ระบุ, ตามลำดับเอกสาร |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | เมื่อเขียนทับในคลาสที่สืบทอด, จะย้ายไปยังโหนดที่มีแอตทริบิวต์ประเภท **ID** ที่ค่าตรงกับ [String](../../system/string/) ที่ระบุ |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | ย้าย [XPathNavigator](./) ไปยังโหนดเนมสเปซที่มีคำนำหน้าเนมสเปซที่ระบุ |
| virtual **bool** [MoveToNext](./movetonext/)() | เมื่อเขียนทับในคลาสที่สืบทอด, จะย้าย [XPathNavigator](./) ไปยังโหนดพี่น้องถัดไปของโหนดปัจจุบัน |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | ย้าย [XPathNavigator](./) ไปยังโหนดพี่น้องถัดไปที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | ย้าย [XPathNavigator](./) ไปยังโหนดพี่น้องถัดไปของโหนดปัจจุบันที่ตรงกับ XPathNodeType ที่ระบุ |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | เมื่อเขียนทับในคลาสที่สืบทอด, จะย้าย [XPathNavigator](./) ไปยังแอตทริบิวต์ถัดไป |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | เมื่อเขียนทับในคลาสที่สืบทอด, จะย้าย [XPathNavigator](./) ไปยังโหนดเนมสเปซถัดไปที่ตรงกับ XPathNamespaceScope ที่ระบุ |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | ย้าย [XPathNavigator](./) ไปยังโหนดเนมสเปซถัดไป |
| virtual **bool** [MoveToParent](./movetoparent/)() | เมื่อเขียนทับในคลาสที่สืบทอด, จะย้าย [XPathNavigator](./) ไปยังโหนดแม่ของโหนดปัจจุบัน |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | เมื่อเขียนทับในคลาสที่สืบทอด, จะย้าย [XPathNavigator](./) ไปยังโหนดพี่น้องก่อนหน้าของโหนดปัจจุบัน |
| virtual void [MoveToRoot](./movetoroot/)() | ย้าย [XPathNavigator](./) ไปยังโหนดรากที่โหนดปัจจุบันเป็นสมาชิกของมัน |
| [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างคัดลอกของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างคัดลอกของคลาสย่อย |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | คืนค่าอ็อบเจ็กต์ [XmlWriter](../../system.xml/xmlwriter/) ที่ใช้สร้างโหนดลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบัน |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | สร้างโหนดลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบันโดยใช้สตริง XML ที่ระบุ |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | สร้างโหนดลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบันโดยใช้เนื้อหา XML ของอ็อบเจกต์ [XmlReader](../../system.xml/xmlreader/) ที่ระบุ |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | สร้างโหนดลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบันโดยใช้โหนดในอ็อบเจกต์ [XPathNavigator](./) ที่ระบุ |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | สร้างเอลีเมนต์ลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบันโดยใช้คำนำหน้าเนมสเปซ, ชื่อท้องถิ่น, และ URI ของเนมสเปซที่ระบุพร้อมค่าที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | คืนค่าอ็อบเจ็กต์ [XmlReader](../../system.xml/xmlreader/) ที่ประกอบด้วยโหนดปัจจุบันและโหนดลูกของมัน |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดค่าพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดค่าพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | แทนที่ช่วงของโหนดพี่น้องจากโหนดปัจจุบันถึงโหนดที่ระบุ |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | แทนที่โหนดปัจจุบันด้วยเนื้อหาของสตริงที่ระบุ |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | แทนที่โหนดปัจจุบันด้วยเนื้อหาของอ็อบเจกต์ [XmlReader](../../system.xml/xmlreader/) ที่ระบุ |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | แทนที่โหนดปัจจุบันด้วยเนื้อหาของอ็อบเจกต์ [XPathNavigator](./) ที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | เลือกชุดโหนดโดยใช้นิพจน์ [XPath](../) ที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | เลือกชุดโหนดโดยใช้นิพจน์ [XPath](../) ที่ระบุพร้อมอ็อบเจ็กต์ [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) ที่ใช้แก้ไขคำนำหน้าเนมสเปซ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | เลือกชุดโหนดโดยใช้ [XPathExpression](../xpathexpression/) ที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | เลือกโหนดบรรพบุรุษทั้งหมดของโหนดปัจจุบันที่มี XPathNodeType ตรงกัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | เลือกโหนดบรรพบุรุษทั้งหมดของโหนดปัจจุบันที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | เลือกโหนดลูกทั้งหมดของโหนดปัจจุบันที่มี XPathNodeType ตรงกัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | เลือกโหนดลูกทั้งหมดของโหนดปัจจุบันที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | เลือกโหนดบุตรหลานทั้งหมดของโหนดปัจจุบันที่มี XPathNodeType ตรงกัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | เลือกโหนดบุตรหลานทั้งหมดของโหนดปัจจุบันที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | เลือกโหนดเดียวใน [XPathNavigator](./) โดยใช้คิวรี [XPath](../) ที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | เลือกโหนดเดียวในอ็อบเจ็กต์ [XPathNavigator](./) โดยใช้คิวรี [XPath](../) ที่ระบุพร้อมอ็อบเจ็กต์ [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) ที่ใช้แก้ไขคำนำหน้าเนมสเปซ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | เลือกโหนดเดียวใน [XPathNavigator](./) โดยใช้อ็อบเจ็กต์ [XPathExpression](../xpathexpression/) ที่ระบุ |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | ตั้งค่า markup ที่แสดงโหนดลูกของโหนดปัจจุบัน |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | ตั้งค่า markup ที่แสดงแท็กเปิดและปิดของโหนดปัจจุบันและโหนดลูกของมัน |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) เพื่อให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | ตั้งค่าประเภทของค่าให้โหนดปัจจุบัน |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | ตั้งค่าค่าให้โหนดปัจจุบัน |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์การอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มเคาน์เตอร์การอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าเคาน์เตอร์การอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| [String](../../system/string/) [ToString](./tostring/)() const override | คืนค่าข้อความของโหนดปัจจุบัน |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อก C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | คืนค่าของโหนดปัจจุบันเป็น Type ที่ระบุโดยใช้อ็อบเจ็กต์ [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) ที่ระบุเพื่อแก้ไขคำนำหน้าเนมสเปซ |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | คืนค่าของไอเท็มในรูปแบบชนิดที่ระบุ |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มเคาน์เตอร์การอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดเคาน์เตอร์การอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | สตรีมโหนดปัจจุบันและโหนดลูกของมันไปยังอ็อบเจ็กต์ [XmlWriter](../../system.xml/xmlwriter/) ที่ระบุ |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## การกำหนดประเภท

| การกำหนดประเภท | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้ |

## ดูเพิ่มเติม

* คลาส [XPathItem](../xpathitem/)
* คลาส [IXPathNavigable](../ixpathnavigable/)
* คลาส [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* เนมสเปซ [System::Xml::XPath](../)
* ไลบรารี [Aspose.Slides](../../)