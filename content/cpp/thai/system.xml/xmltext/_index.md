---
title: XmlText
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แสดงถึงเนื้อหาข้อความขององค์ประกอบหรือแอตทริบิวต์.
type: docs
weight: 495
url: /th/system.xml/xmltext/
---
## XmlText คลาส

Represents the text content of an element or attribute.

```cpp
class XmlText : public System::Xml::XmlCharacterData
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | เพิ่มโหนดที่ระบุไปยังตำแหน่งสุดท้ายของรายการโหนดลูกของโหนดนี้ |
| virtual void [AppendData](../xmlcharacterdata/appenddata/)([String](../../system/string/)) | เพิ่มสตริงที่ระบุต่อท้ายข้อมูลอักขระของโหนด |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | รับอิเทเรเตอร์ที่ชี้ไปยังองค์ประกอบแรก (หากมี) ของคอลเลกชันนี้. อิเทเรเตอร์นี้ไม่สามารถใช้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้ เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าอ็อบเจกต์สำเนาของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | รับอิเทเรเตอร์ที่ชี้ไปยังองค์ประกอบแรก (หากมี) ของอินสแตนซ์ที่มี const ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | รับอิเทเรเตอร์ที่ชี้ไปยังองค์ประกอบแรกที่มี const (หากมี) ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | รับอิเทเรเตอร์ที่ชี้หลังองค์ประกอบสุดท้ายที่มี const (หากมี) ของคอลเลกชัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | สร้างสำเนาของโหนดนี้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | สร้างสำเนาของโหนดนี้ |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | สร้าง XPathNavigator เพื่อใช้ในการนำทางออบเจกต์นี้ |
| virtual void [DeleteData](../xmlcharacterdata/deletedata/)(**int32_t**, **int32_t**) | ลบช่วงของอักขระจากโหนด |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | รับอิเทเรเตอร์ที่ชี้หลังองค์ประกอบสุดท้าย (หากมี) ของคอลเลกชันนี้. อิเทเรเตอร์นี้ไม่สามารถใช้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้ เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าอ็อบเจกต์สำเนาของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | รับอิเทเรเตอร์ที่ชี้หลังองค์ประกอบสุดท้าย (หากมี) ของอินสแตนซ์ที่มี const ของคอลเลกชัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทค่าตามสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | เลียนแบบการเปรียบเทียบแบบจุดลอยของ C# ที่ NaN ทั้งสองถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | เลียนแบบการเปรียบเทียบแบบจุดลอยของ C# ที่ NaN ทั้งสองถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | คืนค่า [XmlAttributeCollection](../xmlattributecollection/) ที่ประกอบด้วยแอตทริบิวต์ของโหนดนี้ |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | คืนค่า URI พื้นฐานของโหนดปัจจุบัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | คืนค่าโหนดลูกทั้งหมดของโหนดนี้ |
| virtual [String](../../system/string/) [get_Data](../xmlcharacterdata/get_data/)() | คืนค่าข้อมูลของโหนด |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | คืนค่าโหนดลูกแรกของโหนด |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | คืนค่าที่บ่งชี้ว่าโหนดนี้มีโหนดลูกหรือไม่ |
| [String](../../system/string/) [get_InnerText](../xmlcharacterdata/get_innertext/)() override | คืนค่าที่เชื่อมต่อของโหนดและโหนดลูกทั้งหมดของโหนด |
| virtual [String](../../system/string/) [get_InnerXml](../xmlnode/get_innerxml/)() | คืนค่า markup ที่แสดงเฉพาะโหนดลูกของโหนดนี้ |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | คืนค่าที่บ่งชี้ว่าโหนดเป็นแบบอ่านอย่างเดียวหรือไม่ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | คืนค่าโหนดลูกสุดท้ายของโหนด |
| virtual **int32_t** [get_Length](../xmlcharacterdata/get_length/)() | คืนความยาวของข้อมูลในหน่วยอักขระ |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | รับชื่อท้องถิ่นของโหนด |
| [String](../../system/string/) [get_Name](./get_name/)() override | รับชื่อที่เต็มรูปแบบของโหนด |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | คืนค่า URI ของเนมสเปซของโหนดนี้ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | คืนค่าโหนดที่ตามมาทันทีหลังจากโหนดนี้ |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | คืนค่าชนิดของโหนดปัจจุบัน |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | คืนค่า markup ที่ประกอบด้วยโหนดนี้และโหนดลูกทั้งหมดของมัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](../xmlnode/get_ownerdocument/)() | คืนค่า [XmlDocument](../xmldocument/) ที่โหนดนี้เป็นสมาชิก |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | คืนค่าโหนดแม่ของโหนดนี้ (สำหรับโหนดที่สามารถมีพาเรนท์ได้) |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | คืนค่าพรีฟิกซ์ของเนมสเปซของโหนดนี้ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | คืนค่าโหนดที่อยู่ก่อนหน้าทันทีของโหนดนี้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](./get_previoustext/)() override | คืนค่าโหนดข้อความที่อยู่ก่อนโหนดนี้โดยตรง |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlnode/get_schemainfo/)() | คืนค่า post schema validation infoset ที่ได้กำหนดให้กับโหนดนี้เป็นผลมาจากการตรวจสอบสคีม่า |
| [String](../../system/string/) [get_Value](./get_value/)() override | คืนค่าของโหนด |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจกต์ |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | คืนค่า enumerator ที่วนซ้ำโหนดลูกในโหนดปัจจุบัน |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชออบเจกต์ที่กำหนดเองได้ |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | ค้นหาการประกาศ **xmlns** ที่ใกล้ที่สุดสำหรับพรีฟิกซ์ที่กำหนดซึ่งอยู่ในสโคปของโหนดปัจจุบันและคืนค่า namespace URI ในประกาศนั้น |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | ค้นหาการประกาศ **xmlns** ที่ใกล้ที่สุดสำหรับ namespace URI ที่กำหนดซึ่งอยู่ในสโคปของโหนดปัจจุบันและคืนค่าพรีฟิกซ์ที่กำหนดในประกาศนั้น |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของออบเจกต์ คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | คืนค่าองค์ประกอบลูกแรกที่มี [XmlNode::get_Name](../xmlnode/get_name/) ที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | คืนค่าองค์ประกอบลูกแรกที่มีค่า [XmlNode::get_LocalName](../xmlnode/get_localname/) และ [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) ที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | แทรกโหนดที่ระบุติดหลังโหนดอ้างอิงที่ระบุทันที |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | แทรกโหนดที่ระบุติดหน้าก่อนโหนดอ้างอิงที่ระบุทันที |
| virtual void [InsertData](../xmlcharacterdata/insertdata/)(**int32_t**, [String](../../system/string/)) | แทรกสตริงที่ระบุที่ตำแหน่งออฟเซ็ตอักขระที่ระบุ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจกต์เป็นอินสแตนซ์ของชนิดที่ targetType อธิบายหรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C# |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | นำฟังก์ชัน accumulator ไปใช้กับลำดับ |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทั้งหมดขององค์ประกอบในลำดับตรงตามเงื่อนไขหรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใด ๆ หรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับที่มีอยู่หรือสอดคล้องกับเงื่อนไขหรือไม่ |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แคสต์องค์ประกอบเป็นชนิดที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อกันสองลำดับ |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่ |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนจำนวนองค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง) |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนจำนวนองค์ประกอบในลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนองค์ประกอบแรกของลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนองค์ประกอบแรกของลำดับ, หรือค่าดีฟอลต์หากลำดับว่าง |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไข หรือค่าดีฟอลต์หากไม่พบ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนองค์ประกอบสุดท้ายของลำดับ |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนองค์ประกอบสุดท้ายของลำดับ, หรือค่าดีฟอลต์หากลำดับว่าง |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่ามากที่สุดที่ได้ |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าต่ำสุดที่ได้ |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามชนิดที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงองค์ประกอบของลำดับตามลำดับจากน้อยไปมากตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงองค์ประกอบของลำดับตามลำดับจากมากไปน้อยตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | กลับลำดับขององค์ประกอบในลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | โปรเจกต์แต่ละองค์ประกอบของลำดับและรวมลำดับที่ได้เป็นลำดับเดียว |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามพรีดิเกตที่ระบุ |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
| virtual void [Normalize](../xmlnode/normalize/)() | ใส่โหนด [XmlText](./) ทั้งหมดในความลึกเต็มของซับทรีภายใต้ [XmlNode](../xmlnode/) นี้ให้เป็นรูปแบบ "ปกติ" ที่มีเฉพาะ markup (เช่น แท็ก, คอมเมนต์, คำสั่งประมวลผล, ส่วน CDATA, และการอ้างอิงเอนทิตี) แยกโหนด [XmlText](./) ซึ่งหมายความว่าไม่มีโหนด [XmlText](./) ที่ติดกัน |
|  [Object](../../system/object/object/)() | สร้างออบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | เพิ่มโหนดที่ระบุไปยังตำแหน่งเริ่มต้นของรายการโหนดลูกของโหนดนี้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| virtual void [RemoveAll](../xmlnode/removeall/)() | ลบโหนดลูกและ/หรือแอตทริบิวต์ทั้งหมดของโหนดปัจจุบัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | ลบโหนดลูกที่ระบุ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงร่วมลงตามค่าที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | แทนที่โหนดลูก **oldChild** ด้วยโหนด **newChild** |
| virtual void [ReplaceData](../xmlcharacterdata/replacedata/)(**int32_t**, **int32_t**, [String](../../system/string/)) | แทนที่จำนวนอักขระที่ระบุเริ่มจากออฟเซ็ตที่ระบุด้วยสตริงที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | เลือกรายการโหนดที่ตรงกับนิพจน์ [XPath](../../system.xml.xpath/) |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | เลือกรายการโหนดที่ตรงกับนิพจน์ [XPath](../../system.xml.xpath/). พรีฟิกซ์ใด ๆ ที่พบในนิพจน์ [XPath](../../system.xml.xpath/) จะถูกแก้ไขโดยใช้ [XmlNamespaceManager](../xmlnamespacemanager/) ที่จัดให้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | เลือก [XmlNode](../xmlnode/) แรกที่ตรงกับนิพจน์ [XPath](../../system.xml.xpath/) |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | เลือก [XmlNode](../xmlnode/) แรกที่ตรงกับนิพจน์ [XPath](../../system.xml.xpath/). พรีฟิกซ์ใด ๆ ที่พบในนิพจน์ [XPath](../../system.xml.xpath/) จะถูกแก้ไขโดยใช้ [XmlNamespaceManager](../xmlnamespacemanager/) ที่จัดให้ |
| virtual void [set_Data](../xmlcharacterdata/set_data/)([String](../../system/string/)) | ตั้งค่าข้อมูลของโหนด |
| void [set_InnerText](../xmlcharacterdata/set_innertext/)([String](../../system/string/)) override | ตั้งค่าค่าที่เชื่อมต่อของโหนดและโหนดลูกทั้งหมดของโหนด |
| virtual void [set_InnerXml](../xmlnode/set_innerxml/)([String](../../system/string/)) | ตั้งค่า markup ที่แสดงเฉพาะโหนดลูกของโหนดนี้ |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | ตั้งค่าพรีฟิกซ์ของเนมสเปซของโหนดนี้ |
| void [set_Value](./set_value/)([String](../../system/string/)) override | ตั้งค่าของโหนด |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงร่วมขึ้น ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlText](./)\> [SplitText](./splittext/)(**int32_t**) | แยกโหนดออกเป็นสองโหนดที่ออฟเซ็ตที่ระบุ โดยคงทั้งสองเป็นโหนดพี่น้องในต้นไม้ |
| virtual [String](../../system/string/) [Substring](../xmlcharacterdata/substring/)(**int32_t**, **int32_t**) | ดึงส่วนย่อยของสตริงเต็มจากช่วงที่ระบุ |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | ทดสอบว่า implementation ของ DOM รองรับฟีเจอร์เฉพาะหรือไม่ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้แปลงออบเจกต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิง weak ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิง weak ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | บันทึกโหนดลูกทั้งหมดของโหนดไปยัง [XmlWriter](../xmlwriter/) ที่ระบุ โหนด [XmlText](./) ไม่มีโหนดลูกจึงไม่มีผลใด ๆ |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | บันทึกโหนดไปยัง [XmlWriter](../xmlwriter/) ที่ระบุ |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ประเภทนิยาม

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้ |

## หมายเหตุ

ออบเจกต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการตรวจสอบข้อผิดพลาด ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) แล้วใช้พอยน์เตอร์นี้ส่งผ่านเป็นอาร์กิวเมนต์ให้ฟังก์ชัน

## ดูเพิ่มเติม

* คลาส [XmlCharacterData](../xmlcharacterdata/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)