---
title: XmlSchemaComplexType
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนขององค์ประกอบ complexType จาก XML Schema ตามที่กำหนดโดย World Wide Web Consortium (W3C). คลาสนี้กำหนดประเภทเชิงซ้อนที่ระบุชุดของแอตทริบิวต์และเนื้อหาขององค์ประกอบหนึ่ง.
type: docs
weight: 300
url: /th/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType คลาส


เป็นตัวแทนขององค์ประกอบ **complexType** จาก XML [Schema](../) ตามที่กำหนดโดย World Wide [Web](../../system.web/) Consortium (W3C). คลาสนี้กำหนดประเภทเชิงซ้อนที่ระบุชุดของแอตทริบิวต์และเนื้อหาขององค์ประกอบหนึ่ง.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมทั้ง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมทั้ง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | คืนค่า property **annotation** |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AnyAttribute](./get_anyattribute/)() | คืนค่าคอมโพเนนท์ [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) ของประเภทเชิงซ้อน |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Attributes](./get_attributes/)() | คืนค่าชุดแอตทริบิวต์ของประเภทเชิงซ้อน |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeUses](./get_attributeuses/)() | คืนค่าชุดแอตทริบิวต์ทั้งหมดที่สอดคล้องของประเภทเชิงซ้อนนี้และประเภทฐานของมัน |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AttributeWildcard](./get_attributewildcard/)() | คืนค่า post-compilation ของ **anyAttribute** สำหรับประเภทเชิงซ้อนนี้และประเภทฐานของมัน |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | คืนค่า post-compilation ของชนิดออบเจ็กต์หรือชนิดข้อมูล XML [Schema](../) Definition Language (XSD) ที่เป็น simpleType หรือ complexType นี่เป็นค่า infoset หลังการคอมไพล์สคีมา |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | คืนค่า post-compilation ของประเภทฐานของสคีมานี้ |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | คืนค่า attribute **block** |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | คืนค่าหลังจากประเภทถูกคอมไพล์เป็นข้อมูลชุด infoset หลังการตรวจสอบสคีมา (infoset) ค่าที่บ่งบอกว่าประเภทถูกบังคับใช้เมื่อใช้ **xsi:type** ในเอกสารอินสแตนซ์ |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\> [get_ContentModel](./get_contentmodel/)() | คืนค่า post-compilation [XmlSchemaContentModel](../xmlschemacontentmodel/) ของประเภทเชิงซ้อนนี้ |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | คืนค่าโมเดลเนื้อหาของประเภทเชิงซ้อนซึ่งถือค่า post-compilation |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_ContentTypeParticle](./get_contenttypeparticle/)() | คืนค่า particle ที่ถือค่า post-compilation ของ particle [XmlSchemaComplexType::get_ContentType](./get_contenttype/) |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | คืนค่า post-compilation ของชนิดข้อมูลของประเภทเชิงซ้อน |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | คืนข้อมูล post-compilation ว่าองค์ประกอบนี้ได้ถูกสืบทอดจากประเภทฐานอย่างไร |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | คืนค่า attribute สุดท้ายของการสืบทอดประเภทที่บ่งบอกว่าการสืบทอดต่อไปได้หรือไม่ได้ |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | คืนค่า post-compilation ของค่าตัวแปร [XmlSchemaType::get_Final](../xmlschematype/get_final/) |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | คืนค่า string id |
| **bool** [get_IsAbstract](./get_isabstract/)() | คืนข้อมูลที่กำหนดว่าองค์ประกอบ **complexType** สามารถใช้ในเอกสารอินสแตนซ์ได้หรือไม่ |
| **bool** [get_IsMixed](./get_ismixed/)() override | คืนข้อมูลที่กำหนดว่าประเภทเชิงซ้อนมีโมเดลเนื้อหาผสม (markup ภายในเนื้อหา) หรือไม่ |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | คืนหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | คืนตำแหน่งคอลัมน์ในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | คืนชื่อของประเภท |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | คืน XmlSerializerNamespaces ที่ใช้กับออบเจ็กต์สคีมานี้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | คืนพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_Particle](./get_particle/)() | คืนชนิด compositor หนึ่งในคลาส [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) หรือ [XmlSchemaSequence](../xmlschemasequence/) |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | คืน qualified name ของประเภทที่สร้างจาก attribute **Name** ของประเภทนี้ นี่เป็นค่า post-compilation |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | คืนตำแหน่งแหล่งที่มาของไฟล์ที่โหลดสคีมา |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | คืน XmlTypeCode ของประเภท |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | คืนแอตทริบิวต์ที่มีคุณสมบัติ qualified แต่ไม่อยู่ใน target namespace ของสคีมาปัจจุบัน |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | คืน [XmlSchemaComplexType](./) ที่เป็นตัวแทนของประเภทเชิงซ้อนที่มีอยู่ในระบบ |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | คืน [XmlSchemaComplexType](./) ที่เป็นตัวแทนของประเภทเชิงซ้อนที่มีอยู่ในระบบโดยใช้ qualified name |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | คืน [XmlSchemaSimpleType](../xmlschemasimpletype/) ที่เป็นตัวแทนของ simple type ที่กำหนดโดย qualified name |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | คืน [XmlSchemaSimpleType](../xmlschemasimpletype/) ที่เป็นตัวแทนของ simple type ที่กำหนด |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ตัวเทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชออบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์ ตัวเทียบเท่ากับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ ตัวเทียบเท่ากับตัวดำเนินการ C# 'is' |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | คืนค่าที่บ่งบอกว่าประเภทสคีมาที่สืบทอดมานั้นเป็นประเภทฐานที่ระบุหรือไม่ |
| void [Lock](../../system/object/lock/)() | ทำงานเช่นคำสั่ง C# lock() เพื่อล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ตัวเทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning ประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา ไม่คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | ตั้งค่า property **annotation** |
| void [set_AnyAttribute](./set_anyattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\>\&) | ตั้งค่าคอมโพเนนท์ [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) ของประเภทเชิงซ้อน |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | ตั้งค่า attribute **block** |
| void [set_ContentModel](./set_contentmodel/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\>\&) | ตั้งค่า post-compilation [XmlSchemaContentModel](../xmlschemacontentmodel/) ของประเภทเชิงซ้อนนี้ |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | ตั้งค่า attribute สุดท้ายของการสืบทอดประเภทที่บ่งบอกว่าการสืบทอดต่อไปได้หรือไม่ |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | ตั้งค่า string id |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | ตั้งค่าข้อมูลที่กำหนดว่าองค์ประกอบ **complexType** สามารถใช้ในเอกสารอินสแตนซ์ได้หรือไม่ |
| void [set_IsMixed](./set_ismixed/)(**bool**) override | ตั้งค่าข้อมูลที่กำหนดว่าประเภทเชิงซ้อนมีโมเดลเนื้อหาผสม (markup ภายในเนื้อหา) หรือไม่ |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | ตั้งค่าหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | ตั้งค่าตำแหน่งคอลัมน์ในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | ตั้งค่าชื่อของประเภท |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | ตั้งค่า XmlSerializerNamespaces ที่ใช้กับออบเจ็กต์สคีมานี้ |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | ตั้งค่าพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้ |
| void [set_Particle](./set_particle/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\&) | ตั้งค่าชนิด compositor หนึ่งใน [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) หรือ [XmlSchemaSequence](../xmlschemasequence/) |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | ตั้งค่าตำแหน่งแหล่งที่มาของไฟล์ที่โหลดสคีมา |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ตั้งค่าแอตทริบิวต์ที่มีคุณสมบัติ qualified แต่ไม่อยู่ใน target namespace ของสคีมาปัจจุบัน |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n ให้เป็น weak pointer (แทน shared) ทำให้สามารถสลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ตัวเทียบเท่ากับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้แปลงออบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานเช่น C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานเช่นคำสั่ง C# lock() เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
|  [XmlSchemaComplexType](./xmlschemacomplextype/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaComplexType](./) |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/) |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaType](../xmlschematype/) |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## การนิยามประเภท

| นิยามประเภท | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ที่ชี้ไปยังอินสแตนซ์ของคลาสนี้ |

## หมายเหตุ



วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้และ/หรือข้อขัดแย้งของการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยเตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

## ดูเพิ่มเติม

* คลาส [XmlSchemaType](../xmlschematype/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)