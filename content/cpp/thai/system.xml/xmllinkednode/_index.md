---
title: XmlLinkedNode
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คืนค่า node ที่อยู่ก่อนหรือถัดจาก node นี้โดยตรง.
type: docs
weight: 274
url: /th/system.xml/xmllinkednode/
---
## XmlLinkedNode คลาส


Returns the node immediately preceding or following this node.

```cpp
class XmlLinkedNode : public System::Xml::XmlNode
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | เพิ่ม node ที่ระบุลงในส่วนท้ายของรายการ child node ของ node นี้. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | รับ iterator ที่ชี้ไปยัง element แรก (หากมี) ของ collection. Iterator นี้ไม่สามารถใช้เพื่อเปลี่ยนแปลงวัตถุที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่า copy-object ของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | รับ iterator ที่ชี้ไปยัง element แรก (หากมี) ของอินสแตนซ์ที่กำหนด const ของ collection. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | รับ iterator ที่ชี้ไปยัง element ที่กำหนด const แรก (หากมี) ของ collection. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | รับ iterator ที่ชี้ทันทีหลัง element ที่กำหนด const ตัวสุดท้าย (หากมี) ของ collection. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | สร้างสำเนาของ node นี้. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](../xmlnode/clonenode/)(**bool**) | สร้างสำเนาของ node, เมื่อ overridden ในคลาสที่สืบทอด. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | สร้าง XPathNavigator สำหรับนำทางวัตถุนี้. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | รับ iterator ที่ชี้ทันทีหลัง element สุดท้าย (หากมี) ของ collection. Iterator นี้ไม่สามารถใช้เพื่อเปลี่ยนแปลงวัตถุที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่า copy-object ของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | รับ iterator ที่ชี้ทันทีหลัง element สุดท้าย (หากมี) ของอินสแตนซ์ที่กำหนด const ของ collection. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบ objects ด้วย semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบ objects ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบ objects ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมทั้ง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมทั้ง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับภายในเท่านั้น. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | คืนค่า [XmlAttributeCollection](../xmlattributecollection/) ที่บรรจุ attributes ของ node นี้. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | คืนค่า base URI ของ node ปัจจุบัน. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | คืนค่า child node ทั้งหมดของ node. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | คืนค่า child แรกของ node. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | คืนค่าที่บ่งชี้ว่า node นี้มี child node หรือไม่. |
| virtual [String](../../system/string/) [get_InnerText](../xmlnode/get_innertext/)() | คืนค่าที่ต่อกันของ node และ child node ทั้งหมดของมัน. |
| virtual [String](../../system/string/) [get_InnerXml](../xmlnode/get_innerxml/)() | คืนค่า markup ที่แสดงเฉพาะ child node ของ node นี้. |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | คืนค่าที่บ่งชี้ว่า node เป็นแบบอ่านอย่างเดียวหรือไม่. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | คืนค่า child สุดท้ายของ node. |
| virtual [String](../../system/string/) [get_LocalName](../xmlnode/get_localname/)() | คืนค่า local name ของ node เมื่อ overridden ในคลาสที่สืบทอด. |
| virtual [String](../../system/string/) [get_Name](../xmlnode/get_name/)() | คืนค่า qualified name ของ node เมื่อ overridden ในคลาสที่สืบทอด. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | คืนค่า namespace URI ของ node นี้. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | คืนค่า node ที่อยู่ถัดจาก node นี้โดยตรง. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](../xmlnode/get_nodetype/)() | คืนค่า type ของ node ปัจจุบันเมื่อ overridden ในคลาสที่สืบทอด. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | คืนค่า markup ที่บรรจุ node นี้และ child node ทั้งหมดของมัน. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](../xmlnode/get_ownerdocument/)() | คืนค่า [XmlDocument](../xmldocument/) ที่ node นี้เป็นส่วนหนึ่ง. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | คืนค่า parent ของ node นี้ (สำหรับ node ที่สามารถมี parent). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | คืนค่า namespace prefix ของ node นี้. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | คืนค่า node ที่ precede node นี้โดยตรง. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | คืนค่า text node ที่ precede node นี้โดยตรง. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlnode/get_schemainfo/)() | คืนค่า post schema validation infoset ที่ได้รับการกำหนดให้กับ node นี้เป็นผลมาจากการตรวจสอบ schema. |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | คืนค่าของ node. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับข้อมูลโครงสร้าง reference counter ที่เชื่อมโยงกับ object. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | คืนค่า enumerator ที่วนซ้ำ child node ใน node ปัจจุบัน. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็น analogue ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการ hash ของ custom objects. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | ค้นหา declaration **xmlns** ที่ใกล้ที่สุดสำหรับ prefix ที่กำหนดซึ่งอยู่ใน scope ของ node ปัจจุบันและคืนค่า namespace URI ใน declaration นั้น. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | ค้นหา declaration **xmlns** ที่ใกล้ที่สุดสำหรับ namespace URI ที่กำหนดซึ่งอยู่ใน scope ของ node ปัจจุบันและคืนค่า prefix ที่กำหนดไว้ใน declaration นั้น. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของ object. เป็น analogue ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | คืนค่า element child แรกที่มี [XmlNode::get_Name](../xmlnode/get_name/) ที่ระบุ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | คืนค่า element child แรกที่มีค่า [XmlNode::get_LocalName](../xmlnode/get_localname/) และ [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) ที่ระบุ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | แทรก node ที่ระบุทันทีหลัง node อ้างอิงที่ระบุ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | แทรก node ที่ระบุทันทีก่อน node อ้างอิงที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่า object แสดงถึง instance ของประเภทที่อธิบายโดย targetType. เป็น analogue ของ operator 'is' ของ C#. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับ sequence. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุก element ของ sequence ปฏิบัติตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่า sequence มี element ใด ๆ หรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่า element ใด ๆ ของ sequence มีอยู่หรือปฏิบัติตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของ sequence ของค่าตัวเลข. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของ sequence ของค่า ที่ได้จากการเรียกฟังก์ชัน transform กับแต่ละ element ของ sequence อินพุต. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แคสต์ element ไปยังประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อสอง sequence เข้าด้วยกัน. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่า sequence มีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนค่าจำนวน element ใน sequence (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนค่าจำนวน element ใน sequence ที่ปฏิบัติตามเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนค่า element ที่ตำแหน่งที่ระบุใน sequence. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนค่า element ที่ตำแหน่งที่ระบุใน sequence. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนค่า element แรกของ sequence. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนค่า element แรกของ sequence ที่ปฏิบัติตามเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนค่า element แรกของ sequence หรือค่าตั้งต้นหาก sequence ว่าง. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนค่า element แรกของ sequence ที่ปฏิบัติตามเงื่อนไข หรือค่าตั้งต้นหากไม่พบ element ที่ตรงเงื่อนไข. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่ม element ของ sequence. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่ม element ของ sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนค่า element สุดท้ายของ sequence. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนค่า element สุดท้ายของ sequence หรือค่าตั้งต้นหาก sequence ว่าง. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชัน transform กับแต่ละ element ของ generic sequence และคืนค่าผลลัพธ์สูงสุด. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชัน transform กับแต่ละ element ของ generic sequence และคืนค่าผลลัพธ์ต่ำสุด. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรอง element ของ sequence ตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียง element ของ sequence ในลำดับจากน้อยไปหามากตามค่า key ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียง element ของ sequence ในลำดับจากมากไปหาน้อยตามค่า key ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | กลับลำดับของ element ใน sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลง element ของ sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละ element ของ sequence ให้เป็นรูปแบบใหม่โดยรวมเอาดัชนีของ element เข้าไป. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | ทำ projection กับแต่ละ element ของ sequence และรวม sequence ที่ได้เป็นหนึ่ง sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวน element ติดกันที่ระบุจากจุดเริ่มต้นของ sequence และคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวน element ติดกันที่ระบุจากจุดเริ่มต้นของ sequence. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้าง array จาก sequence. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จาก sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรอง sequence ตาม predicate ที่ระบุ. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็น analogue ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคล cloning ของ custom types. |
| virtual void [Normalize](../xmlnode/normalize/)() | ใส่ node [XmlText](../xmltext/) ทั้งหมดในระดับความลึกทั้งหมดของ sub-tree ใต้ [XmlNode](../xmlnode/) นี้ให้อยู่ในรูปแบบ \"ปกติ\" ที่ซึ่งมีเพียง markup (เช่น tag, comment, processing instruction, CDATA section, และ entity reference) คั่นระหว่าง node [XmlText](../xmltext/) เท่านั้น, กล่าวคือ ไม่มี node [XmlText](../xmltext/) ที่ต่อกัน. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. ไม่ได้คัดลอกอะไรเลย, จริง ๆ แล้วเพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการ copy constructing ของ subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. ไม่ได้คัดลอกอะไรเลย, จริง ๆ แล้วเพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการ copy constructing ของ subclass. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | เพิ่ม node ที่ระบุไปยังจุดเริ่มต้นของรายการ child node ของ node นี้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบ objects โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบ objects โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิง value type object กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การสเปเชียลไลซ์ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การสเปเชียลไลซ์ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | ลบ child node ทั้งหมดและ/หรือ attributes ของ node ปัจจุบัน. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | ลบ child node ที่ระบุ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่า shared reference count ลงตามค่าที่ระบุ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | แทนที่ child node **oldChild** ด้วย node **newChild**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | เลือกรายการ node ที่ตรงกับ expression [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | เลือกรายการ node ที่ตรงกับ expression [XPath](../../system.xml.xpath/). คำ prefix ใด ๆ ที่พบใน expression [XPath](../../system.xml.xpath/) จะถูกแก้ไขโดยใช้ [XmlNamespaceManager](../xmlnamespacemanager/) ที่จัดเตรียม. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | เลือก [XmlNode](../xmlnode/) แรกที่ตรงกับ expression [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | เลือก [XmlNode](../xmlnode/) แรกที่ตรงกับ expression [XPath](../../system.xml.xpath/). คำ prefix ใด ๆ ที่พบใน expression [XPath](../../system.xml.xpath/) จะถูกแก้ไขโดยใช้ [XmlNamespaceManager](../xmlnamespacemanager/). |
| virtual void [set_InnerText](../xmlnode/set_innertext/)([String](../../system/string/)) | ตั้งค่าที่ต่อกันของ node และ child node ทั้งหมดของมัน. |
| virtual void [set_InnerXml](../xmlnode/set_innerxml/)([String](../../system/string/)) | ตั้งค่า markup ที่แสดงเฉพาะ child node ของ node นี้. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | ตั้งค่า namespace prefix ของ node นี้. |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | ตั้งค่าของ node. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลต argument ที่ n เป็น weak pointer (แทน shared). อนุญาตการสลับ pointer ใน container ไปเป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของ shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่า shared reference count. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่า shared reference count. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | ตรวจสอบว่า DOM implementation รองรับฟีเจอร์เฉพาะหรือไม่. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็น analogue ของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลง custom objects เป็น string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตาม construct typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | รับ implementation ของ begin const iterator สำหรับ container ปัจจุบัน. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | รับ implementation ของ begin iterator สำหรับ container ปัจจุบัน. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | รับ implementation ของ end const iterator สำหรับ container ปัจจุบัน. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | รับ implementation ของ end iterator สำหรับ container ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่า weak reference count. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่า weak reference count. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointers หรือ ThisProtector. |
| virtual void [WriteContentTo](../xmlnode/writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | บันทึก child node ทั้งหมดของ node ไปยัง [XmlWriter](../xmlwriter/) ที่ระบุ, เมื่อ overridden ในคลาสที่สืบทอด. |
| virtual void [WriteTo](../xmlnode/writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | บันทึก node ปัจจุบันไปยัง [XmlWriter](../xmlwriter/) ที่ระบุ, เมื่อ overridden ในคลาสที่สืบทอด. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ชนิดนิยาม

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## ดูเพิ่มเติม

* คลาส [XmlNode](../xmlnode/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)