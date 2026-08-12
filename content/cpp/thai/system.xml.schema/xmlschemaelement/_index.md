---
title: XmlSchemaElement
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แสดงถึง element จาก XML Schema ตามที่กำหนดโดย World Wide Web Consortium (W3C). คลาสนี้เป็นคลาสฐานสำหรับทุกประเภทของ particle และใช้ในการอธิบาย element ในเอกสาร XML.
type: docs
weight: 365
url: /th/system.xml.schema/xmlschemaelement/
---
## คลาส XmlSchemaElement

Represents the **element** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is the base class for all particle types and is used to describe an element in an XML document.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้สถาปัตยกรรม C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจุดลอยตามสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจุดลอยตามสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | คืนค่า property **annotation**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | คืนค่า derivation **Block**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | คืนค่าการตีความหลังการคอมไพล์ของค่า **Block**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | คืนค่าชุดของข้อจำกัดบน element. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | คืนค่าดีฟอลท์ของ element หากเนื้อหาเป็นประเภทง่ายหรือเนื้อหาของ element เป็น **textOnly**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | คืนค่าอ็อบเจ็กต์ [XmlSchemaType](../xmlschematype/) ที่แสดงประเภทของ element ตามค่า [XmlSchemaElement::get_SchemaType](./get_schematype/) หรือ [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) ของ element. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | คืนค่าอ็อบเจ็กต์ตาม [XmlSchemaElement](./) หรือ [XmlSchemaElement](./) ของ element ซึ่งบรรจุตีความหลังการคอมไพล์ของค่า **ElementType**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | คืนค่า **Final** เพื่อบ่งชี้ว่าไม่อนุญาตให้มี derivations เพิ่มเติม. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | คืนค่าการตีความหลังการคอมไพล์ของค่า **Final**. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | คืนค่าคงที่. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | คืนค่าแบบฟอร์มของ element. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | คืนค่า id แบบสตริง. |
| **bool** [get_IsAbstract](./get_isabstract/)() | คืนข้อมูลเพื่อบ่งชี้ว่า element สามารถใช้ในเอกสาร instance ได้หรือไม่. |
| **bool** [get_IsNillable](./get_isnillable/)() | คืนข้อมูลที่บ่งชี้ว่า **xsi:nil** สามารถเกิดในข้อมูล instance ได้หรือไม่. แสดงว่าค่า nil ที่กำหนดโดยตรงสามารถกำหนดให้กับ element ได้หรือไม่. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | คืนค่าเลขบรรทัดในไฟล์ที่ element **schema** อ้างอิงอยู่. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | คืนค่าตำแหน่งบรรทัดในไฟล์ที่ element **schema** อ้างอิงอยู่. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | คืนค่าจำนวนสูงสุดที่ particle สามารถเกิดได้. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | คืนค่าตัวเลขเป็นสตริง. จำนวนสูงสุดที่ particle สามารถเกิดได้. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | คืนค่าจำนวนต่ำสุดที่ particle สามารถเกิดได้. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | คืนค่าตัวเลขเป็นสตริง. จำนวนต่ำสุดที่ particle สามารถเกิดได้. |
| [String](../../system/string/) [get_Name](./get_name/)() | คืนค่าชื่อของ element. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | คืนค่า XmlSerializerNamespaces ที่ใช้กับอ็อบเจ็กต์ schema นี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | คืนค่า parent ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | คืนค่าชื่อที่ครบถ้วนของ element ที่กำหนด. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | คืนค่าชื่ออ้างอิงของ element ที่ประกาศใน schema นี้ (หรือ schema อื่นที่ระบุโดยเนมสเปซที่กำหนด). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | คืนค่าประเภทของ element. สามารถเป็นประเภทซับซ้อนหรือประเภทง่ายได้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | คืนค่าชื่อของประเภทข้อมูล built-in ที่กำหนดใน schema นี้หรือ schema อื่นที่ระบุโดยเนมสเปซที่กำหนด. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | คืนค่าตำแหน่งแหล่งที่มาของไฟล์ที่โหลด schema. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | คืนค่าชื่อของ element ที่ถูกแทนที่โดย element นี้. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | คืนค่าคุณลักษณะที่ครบถ้วนซึ่งไม่เป็นส่วนหนึ่งของเนมสเปซเป้าหมายของ schema ปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการทำงานคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นการทำงานคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับออปเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการทำงานคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำคล cloning ประเภทแบบกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงแต่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงแต่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแยกประเภทของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแยกประเภทของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมตามค่าที่ระบุ. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | ตั้งค่า property **annotation**. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | ตั้งค่า derivation **Block**. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | ตั้งค่าค่าดีฟอลท์ของ element หากเนื้อหาเป็นประเภทง่ายหรือเนื้อหาของ element เป็น **textOnly**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | ตั้งค่า **Final** เพื่อบ่งชี้ว่าไม่อนุญาตให้มี derivations เพิ่มเติม. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | ตั้งค่าค่าคงที่. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | ตั้งค่าแบบฟอร์มของ element. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | ตั้งค่า id แบบสตริง. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | ตั้งค่าข้อมูลเพื่อบ่งชี้ว่า element สามารถใช้ในเอกสาร instance ได้หรือไม่. |
| void [set_IsNillable](./set_isnillable/)(**bool**) | ตั้งค่าข้อมูลที่บ่งชี้ว่า **xsi:nil** สามารถเกิดในข้อมูล instance ได้หรือไม่. แสดงว่าค่า nil ที่กำหนดโดยตรงสามารถกำหนดให้กับ element ได้หรือไม่. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | ตั้งค่าเลขบรรทัดในไฟล์ที่ element **schema** อ้างอิง. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | ตั้งค่าตำแหน่งบรรทัดในไฟล์ที่ element **schema** อ้างอิง. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | ตั้งค่าจำนวนสูงสุดที่ particle สามารถเกิดได้. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | ตั้งค่าตัวเลขเป็นสตริง. จำนวนสูงสุดที่ particle สามารถเกิดได้. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | ตั้งค่าจำนวนต่ำสุดที่ particle สามารถเกิดได้. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | ตั้งค่าตัวเลขเป็นสตริง. จำนวนต่ำสุดที่ particle สามารถเกิดได้. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | ตั้งค่าชื่อของ element. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | ตั้งค่า XmlSerializerNamespaces ที่ใช้กับอ็อบเจ็กต์ schema นี้. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | ตั้งค่า parent ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | ตั้งค่าชื่ออ้างอิงของ element ที่ประกาศใน schema นี้ (หรือ schema อื่นที่ระบุโดยเนมสเปซที่กำหนด). |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | ตั้งค่าประเภทของ element. สามารถเป็นประเภทซับซ้อนหรือประเภทง่ายได้. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | ตั้งค่าชื่อของประเภทข้อมูล built-in ที่กำหนดใน schema นี้หรือ schema อื่นที่ระบุโดยเนมสเปซที่กำหนด. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | ตั้งค่าตำแหน่งแหล่งที่มาของไฟล์ที่โหลด schema. |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | ตั้งค่าชื่อของ element ที่ถูกแทนที่โดย element นี้. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ตั้งค่าคุณลักษณะที่ครบถ้วนซึ่งไม่เป็นส่วนหนึ่งของเนมสเปซเป้าหมายของ schema ปัจจุบัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นการทำงานคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
|  [XmlSchemaElement](./xmlschemaelement/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaElement](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## นิยามประเภท

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## ดูเพิ่มเติม

* คลาส [XmlSchemaParticle](../xmlschemaparticle/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)