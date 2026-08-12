---
title: XmlEntityReference
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นตัวแทนของโหนดอ้างอิงเอนทิตี้
type: docs
weight: 248
url: /th/system.xml/xmlentityreference/
---
## XmlEntityReference คลาส

เป็นตัวแทนของโหนดอ้างอิงเอนทิตี้

```cpp
class XmlEntityReference : public System::Xml::XmlLinkedNode
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | เพิ่มโหนดที่ระบุไปยังส่วนท้ายของรายการโหนดลูกของโหนดนี้ |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | รับ iterator ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของคอลเลกชัน ตัว iterator นี้ไม่สามารถใช้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าออบเจ็กต์สำเนาของ T |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | รับ iterator ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของอินสแตนซ์คอนสท์ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | รับ iterator ที่ชี้ไปยังองค์ประกอบคอนสท์แรก (ถ้ามี) ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | รับ iterator ที่ชี้หลังจากองค์ประกอบคอนสท์สุดท้าย (ถ้ามี) ของคอลเลกชัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | สร้างสำเนาของโหนดนี้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | สร้างสำเนาของโหนดนี้ |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | สร้าง XPathNavigator เพื่อการนำทางออบเจ็กต์นี้ |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | รับ iterator ที่ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของคอลเลกชัน ตัว iterator นี้ไม่สามารถใช้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าออบเจ็กต์สำเนาของ T |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | รับ iterator ที่ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของอินสแตนซ์คอนสท์ของคอลเลกชัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | คืนค่า [XmlAttributeCollection](../xmlattributecollection/) ที่มีแอตทริบิวต์ของโหนดนี้ |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | คืนค่า Uniform Resource Identifier (URI) พื้นฐานของโหนดปัจจุบัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | คืนค่าโหนดลูกทั้งหมดของโหนดนี้ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | คืนค่าโหนดลูกแรกของโหนดนี้ |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | คืนค่าที่ระบุว่าโหนดนี้มีโหนดลูกหรือไม่ |
| virtual [String](../../system/string/) [get_InnerText](../xmlnode/get_innertext/)() | คืนค่าที่ต่อเนื่องของโหนดและโหนดลูกทั้งหมดของโหนดนี้ |
| virtual [String](../../system/string/) [get_InnerXml](../xmlnode/get_innerxml/)() | คืนค่า markup ที่แสดงเฉพาะโหนดลูกของโหนดนี้ |
| **bool** [get_IsReadOnly](./get_isreadonly/)() override | คืนค่าที่ระบุว่าโหนดเป็นแบบอ่านอย่างเดียวหรือไม่ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | คืนค่าโหนดลูกสุดท้ายของโหนดนี้ |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | คืนค่าชื่อท้องถิ่นของโหนด |
| [String](../../system/string/) [get_Name](./get_name/)() override | คืนค่าชื่อของโหนด |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | คืนค่า namespace URI ของโหนดนี้ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | คืนค่าโหนดที่ตามมาทันทีหลังจากโหนดนี้ |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | คืนค่าประเภทของโหนด |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | คืนค่า markup ที่บรรจุโหนดนี้และโหนดลูกทั้งหมดของมัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](../xmlnode/get_ownerdocument/)() | คืนค่า [XmlDocument](../xmldocument/) ที่โหนดนี้เป็นสมาชิก |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | คืนค่าโหนดพ่อแม่ของโหนดนี้ (สำหรับโหนดที่สามารถมีพ่อแม่ได้) |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | คืนค่าพรีฟิกซ์ของ namespace ของโหนดนี้ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | คืนค่าโหนดที่มาก่อนโหนดนี้ทันที |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | คืนค่าโหนดข้อความที่มาก่อนโหนดนี้ทันที |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlnode/get_schemainfo/)() | คืนค่า post schema validation infoset ที่ถูกกำหนดให้กับโหนดนี้เป็นผลมาจากการตรวจสอบสคีม่า |
| [String](../../system/string/) [get_Value](./get_value/)() override | คืนค่าของโหนด |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | คืนค่า enumerator ที่วนรอบโหนดลูกในโหนดปัจจุบัน |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอะแนโลกของเมธด์ C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถทำแฮชของออบเจ็กต์ที่กำหนดเอง |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | ค้นหาการประกาศ **xmlns** ที่ใกล้ที่สุดสำหรับพรีฟิกซ์ที่กำหนดซึ่งอยู่ในสโคปของโหนดปัจจุบันและคืนค่า namespace URI ในการประกาศนั้น |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | ค้นหาการประกาศ **xmlns** ที่ใกล้ที่สุดสำหรับ namespace URI ที่กำหนดซึ่งอยู่ในสโคปของโหนดปัจจุบันและคืนค่าพรีฟิกซ์ที่กำหนดในการประกาศนั้น |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์ เป็นอะแนโลกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | คืนค่าองค์ประกอบลูกแรกที่มี [XmlNode::get_Name](../xmlnode/get_name/) ที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | คืนค่าองค์ประกอบลูกแรกที่มีค่า [XmlNode::get_LocalName](../xmlnode/get_localname/) และ [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) ที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | แทรกโหนดที่ระบุทันทีหลังจากโหนดอ้างอิงที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | แทรกโหนดที่ระบุทันทีก่อนโหนดอ้างอิงที่ระบุ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นอะแนโลกของตัวดำเนินการ 'is' ของ C# |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับลำดับ |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกองค์ประกอบในลำดับทำตามเงื่อนไขหรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใดหรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับที่มีอยู่หรือทำตามเงื่อนไขหรือไม่ |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับค่าตัวเลข |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับค่าที่ได้โดยเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แคสต์องค์ประกอบเป็นประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อเนื่องสองลำดับ |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่ |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนค่าจำนวนองค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง) |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนค่าจำนวนองค์ประกอบในลำดับที่ทำตามเงื่อนไขที่ระบุ |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนค่าองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนค่าองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนค่าองค์ประกอบแรกของลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนค่าองค์ประกอบแรกของลำดับที่ทำตามเงื่อนไขที่ระบุ |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนค่าองค์ประกอบแรกของลำดับ หรือค่าดีฟอลต์หากลำดับว่าง |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนค่าองค์ประกอบแรกของลำดับที่ทำตามเงื่อนไข หรือค่าดีฟอลต์หากไม่พบ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนค่าองค์ประกอบสุดท้ายของลำดับ |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนค่าองค์ประกอบสุดท้ายของลำดับ หรือค่าดีฟอลต์หากลำดับว่าง |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าผลลัพธ์สูงสุด |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าผลลัพธ์ต่ำสุด |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงองค์ประกอบของลำดับในลำดับจากน้อยไปมากตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงองค์ประกอบของลำดับในลำดับจากมากไปน้อยตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | กลับลำดับขององค์ประกอบในลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | โปรเจคต์แต่ละองค์ประกอบของลำดับและรวมลำดับผลลัพธ์เป็นลำดับเดียว |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาร์เรย์จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อคของคำสั่ง C# lock() เรียกใช้โดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอะแนโลกของเมธด์ C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเอง |
| virtual void [Normalize](../xmlnode/normalize/)() | ใส่โหนด [XmlText](../xmltext/) ทั้งหมดในความลึกเต็มของ subtree ใต้ [XmlNode](../xmlnode/) นี้เป็นรูปแบบ "ปกติ" ที่มีเพียง markup (เช่น แท็ก, ความคิดเห็น, คำสั่งประมวลผล, ส่วน CDATA, และการอ้างอิงเอนทิตี้) แยกโหนด [XmlText](../xmltext/) ซึ่งหมายความว่าไม่มีโหนด [XmlText](../xmltext/) ที่อยู่ติดกัน |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์สำเนา ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของซับคลาส |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | เพิ่มโหนดที่ระบุไปยังจุดเริ่มต้นของรายการโหนดลูกของโหนดนี้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| virtual void [RemoveAll](../xmlnode/removeall/)() | ลบโหนดลูกและ/หรือแอตทริบิวต์ทั้งหมดของโหนดปัจจุบัน |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | ลบโหนดลูกที่ระบุ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | แทนที่โหนดลูก **oldChild** ด้วยโหนด **newChild** |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | เลือกรายการโหนดที่ตรงกับนิพจน์ [XPath](../../system.xml.xpath/) |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | เลือกรายการโหนดที่ตรงกับนิพจน์ [XPath](../../system.xml.xpath/) คำคำนำที่พบในนิพจน์ [XPath](../../system.xml.xpath/) จะถูกแก้ไขโดยใช้ [XmlNamespaceManager](../xmlnamespacemanager/) ที่จัดหา |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | เลือก [XmlNode](../xmlnode/) แรกที่ตรงกับนิพจน์ [XPath](../../system.xml.xpath/) |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | เลือก [XmlNode](../xmlnode/) แรกที่ตรงกับนิพจน์ [XPath](../../system.xml.xpath/) คำคำนำที่พบในนิพจน์ [XPath](../../system.xml.xpath/) จะถูกแก้ไขโดยใช้ [XmlNamespaceManager](../xmlnamespacemanager/) ที่จัดหา |
| virtual void [set_InnerText](../xmlnode/set_innertext/)([String](../../system/string/)) | ตั้งค่าที่ต่อเนื่องของโหนดและโหนดลูกทั้งหมด |
| virtual void [set_InnerXml](../xmlnode/set_innerxml/)([String](../../system/string/)) | ตั้งค่า markup ที่แสดงเฉพาะโหนดลูกของโหนดนี้ |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | ตั้งค่าพรีฟิกซ์ของ namespace ของโหนดนี้ |
| void [set_Value](./set_value/)([String](../../system/string/)) override | ตั้งค่าของโหนด |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าอ้างอิงที่แชร์ในขณะนี้ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | ทดสอบว่า DOM implementation รองรับฟีเจอร์เฉพาะหรือไม่ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอะแนโลกของเมธด์ C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อคของคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | รับการดำเนินการของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | รับการดำเนินการของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | รับการดำเนินการของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | รับการดำเนินการของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | บันทึกโหนดลูกทั้งหมดของโหนดไปยัง [XmlWriter](../xmlwriter/) ที่ระบุ |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | บันทึกโหนดไปยัง [XmlWriter](../xmlwriter/) ที่ระบุ |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## การนิยามประเภท

| ประเภทนิยาม | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้ |

## หมายเหตุ

อ็อบเจ็กต์ของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการตรวจสอบล้มเหลว ควรห่อหุ้มคลาสนี้ในพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

## ดูเพิ่มเติม

* คลาส [XmlLinkedNode](../xmllinkednode/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)