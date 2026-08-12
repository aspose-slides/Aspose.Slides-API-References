---
title: XmlSchemaComplexContentRestriction
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงองค์ประกอบ restriction จาก XML Schema ตามที่กำหนดโดย World Wide Web Consortium (W3C) คลาสนี้ใช้สำหรับประเภทเชิงซับซ้อนที่มีโมเดลเนื้อหาเชิงซับซ้อนที่ได้มาผ่านการจำกัด มันจำกัดเนื้อหาของประเภทเชิงซับซ้อนให้เป็นส่วนย่อยของประเภทเชิงซับซ้อนที่สืบทอดมา
type: docs
weight: 287
url: /th/system.xml.schema/xmlschemacomplexcontentrestriction/
---
## XmlSchemaComplexContentRestriction คลาส


Represents the **restriction** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is for complex types with a complex content model derived by restriction. It restricts the contents of the complex type to a subset of the inherited complex type.

```cpp
class XmlSchemaComplexContentRestriction : public System::Xml::Schema::XmlSchemaContent
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยของ C#-style ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยของ C#-style ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | ส่งคืนคุณสมบัติ **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AnyAttribute](./get_anyattribute/)() | ส่งคืนคอมโพเนนต์ [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) ของแบบจำลองเนื้อหาเชิงซับซ้อน. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Attributes](./get_attributes/)() | ส่งคืนคอลเลกชันของแอตทริบิวต์สำหรับประเภทเชิงซับซ้อน ซึ่งมีองค์ประกอบ [XmlSchemaAttribute](../xmlschemaattribute/) และ [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_BaseTypeName](./get_basetypename/)() | ส่งคืนชื่อของประเภทเชิงซับซ้อนที่ประเภทนี้สืบทอดมาด้วยการจำกัด. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | ส่งคืนรหัสสตริง. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | ส่งคืนหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิงถึง. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | ส่งคืนตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิงถึง. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | ส่งคืน XmlSerializerNamespaces ที่จะใช้กับอ็อบเจกต์สคีมานี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | ส่งคืนพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_Particle](./get_particle/)() | ส่งคืนหนึ่งในคลาส [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) หรือ [XmlSchemaSequence](../xmlschemasequence/) |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | ส่งคืนตำแหน่งที่มาของไฟล์ที่โหลดสคีมา. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | ส่งคืนแอตทริบิวต์ที่มีคุณสมบัติครบถ้วนซึ่งไม่เป็นส่วนหนึ่งของเนมสเปซเป้าหมายของสคีมาปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ ซึ่งคล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์และเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย จริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้การสร้างสำเนาของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้การสร้างสำเนาของคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงแบบ shared ตามค่าที่ระบุ |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | ตั้งค่าคุณสมบัติ **annotation** |
| void [set_AnyAttribute](./set_anyattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\>\&) | ตั้งค่าองค์ประกอบ [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) ของแบบจำลองเนื้อหาเชิงซับซ้อน. |
| void [set_BaseTypeName](./set_basetypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | ตั้งค่าชื่อของประเภทเชิงซับซ้อนที่ประเภทนี้สืบทอดมาด้วยการจำกัด. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | ตั้งค่ารหัสสตริง. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | ตั้งค่าหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิงถึง. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | ตั้งค่าตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิงถึง. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | ตั้งค่า XmlSerializerNamespaces ที่จะใช้กับอ็อบเจกต์สคีมานี้. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | ตั้งค่าพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| void [set_Particle](./set_particle/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\&) | ตั้งค่าเป็นหนึ่งในคลาส [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) หรือ [XmlSchemaSequence](../xmlschemasequence/) |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | ตั้งค่าตำแหน่งที่มาของไฟล์ที่โหลดสคีมา |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ตั้งค่าแอตทริบิวต์ที่มีคุณสมบัติครบถ้วนซึ่งไม่เป็นส่วนหนึ่งของเนมสเปซเป้าหมายของสคีมาปัจจุบัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนท์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared) ทำให้สามารถสลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบ shared. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ shared ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงแบบ shared และคืนค่า ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการจำลองโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
|  [XmlSchemaComplexContentRestriction](./xmlschemacomplexcontentrestriction/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaComplexContentRestriction](./) |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/) |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์และปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ชนิดนิยาม

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ

วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาด runtime และ/หรือข้อผิดพลาด assertion ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน

## อ้างอิงเพิ่มเติม

* คลาส [XmlSchemaContent](../xmlschemacontent/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)