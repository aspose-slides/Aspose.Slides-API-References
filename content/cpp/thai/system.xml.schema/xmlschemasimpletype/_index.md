---
title: XmlSchemaSimpleType
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นตัวแทนขององค์ประกอบ simpleType สำหรับเนื้อหาแบบง่ายจาก XML Schema ตามที่กำหนดโดย World Wide Web Consortium (W3C). คลาสนี้กำหนดประเภทแบบง่าย. ประเภทง่ายสามารถระบุข้อมูลและข้อจำกัดสำหรับค่าของแอตทริบิวต์หรือองค์ประกอบที่มีเนื้อหาเป็นข้อความเท่านั้น.
type: docs
weight: 833
url: /th/system.xml.schema/xmlschemasimpletype/
---
## XmlSchemaSimpleType คลาส


Represents the **simpleType** element for simple content from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class defines a simple type. Simple types can specify information and constraints for the value of attributes or elements with text-only content.

```cpp
class XmlSchemaSimpleType : public System::Xml::Schema::XmlSchemaType
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถูกพิจารณาเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถูกพิจารณาเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | คืนค่า property **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | คืนค่าชนิดอ็อบเจ็กต์หลังการคอมไพล์หรือชนิดข้อมูล XML [Schema](../) Definition Language (XSD) ในตัว, องค์ประกอบ simpleType หรือ complexType. นี่เป็นค่า Infoset หลังการคอมไพล์สคีมา. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | คืนค่าหลังการคอมไพล์สำหรับชนิดพื้นฐานของสคีมาชนิดนี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\> [get_Content](./get_content/)() | คืนค่าใดค่าหนึ่งจาก [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) หรือ [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | คืนค่าหลังการคอมไพล์สำหรับชนิดข้อมูลของประเภทซับซ้อน. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | คืนข้อมูลหลังการคอมไพล์ว่าตัวนี้ถูกสืบทอดจากชนิดพื้นฐานอย่างไร. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | คืนแอตทริบิวต์สุดท้ายของการสืบทอดชนิดที่บ่งบอกว่าจะอนุญาตการสืบทอดต่อหรือไม่. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | คืนการตีความหลังการคอมไพล์ของค่า [XmlSchemaType::get_Final](../xmlschematype/get_final/). |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | คืนค่า id เป็นสตริง. |
| virtual **bool** [get_IsMixed](../xmlschematype/get_ismixed/)() | คืนค่าที่บ่งชี้ว่าชนิดนี้มีโมเดลเนื้อหาแบบผสมหรือไม่. คำเรียกนี้ใช้ได้เฉพาะในประเภทซับซ้อน. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | คืนหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | คืนตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | คืนชื่อของชนิด. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | คืนค่า XmlSerializerNamespaces ที่ใช้กับวัตถุสคีมานี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | คืนผู้ปกครองของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | คืนชื่อที่มีคุณสมบัติของชนิดที่สร้างจากแอตทริบิวต์ **Name** ของชนิดนี้. นี่คือค่าหลังการคอมไพล์สคีมา. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | คืนตำแหน่งแหล่งที่มาของไฟล์ที่โหลดสคีมา. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | คืนค่า XmlTypeCode ของชนิด. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | คืนแอตทริบิวต์ที่มีคุณสมบัติแต่ไม่ได้เป็นของเนมสเปซเป้าหมายของสคีมาปัจจุบัน. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | คืนค่า [XmlSchemaComplexType](../xmlschemacomplextype/) ที่แสดงถึงประเภทซับซ้อนในตัวของประเภทซับซ้อนที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | คืนค่า [XmlSchemaComplexType](../xmlschemacomplextype/) ที่แสดงถึงประเภทซับซ้อนในตัวของประเภทซับซ้อนที่ระบุโดยชื่อที่มีคุณสมบัติ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | คืนค่า [XmlSchemaSimpleType](./) ที่แสดงถึงประเภทง่ายในตัวของประเภทง่ายที่ระบุโดยชื่อที่มีคุณสมบัติ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](./)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | คืนค่า [XmlSchemaSimpleType](./) ที่แสดงถึงประเภทง่ายในตัวของประเภทง่ายที่ระบุ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเทียบเท่ากับเมท็อด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถทำฮาชของอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. เป็นเทียบเท่ากับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. เทียบเท่ากับโอเปอเรเตอร์ 'is' ของ C#. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | คืนค่าที่บ่งชี้ว่าชนิดสคีมาที่สืบทอดระบุเป็นสกีมาชนิดฐานที่ระบุหรือไม่. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อคตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุเฝ้าระวัง [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเทียบเท่ากับเมท็อด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่าเทียบกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | กำหนดค่า property **annotation**. |
| void [set_Content](./set_content/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)\>\&) | กำหนดค่าเป็นหนึ่งใน [XmlSchemaSimpleTypeUnion](../xmlschemasimpletypeunion/), [XmlSchemaSimpleTypeList](../xmlschemasimpletypelist/) หรือ [XmlSchemaSimpleTypeRestriction](../xmlschemasimpletyperestriction/). |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | กำหนดแอตทริบิวต์สุดท้ายของการสืบทอดชนิดที่บ่งบอกว่าจะอนุญาตการสืบทอดต่อหรือไม่. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | กำหนดค่า id เป็นสตริง. |
| virtual void [set_IsMixed](../xmlschematype/set_ismixed/)(**bool**) | กำหนดค่าที่บ่งชี้ว่าชนิดนี้มีโมเดลเนื้อหาแบบผสมหรือไม่. คำเรียกนี้ใช้ได้เฉพาะในประเภทซับซ้อน. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | กำหนดหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | กำหนดตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | กำหนดชื่อของชนิด. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | กำหนดค่า XmlSerializerNamespaces ที่ใช้กับวัตถุสคีมานี้. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | กำหนดผู้ปกครองของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | กำหนดตำแหน่งแหล่งที่มาของไฟล์ที่โหลดสคีมา. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | กำหนดแอตทริบิวต์ที่มีคุณสมบัติแต่ไม่ได้เป็นของเนมสเปซเป้าหมายของสคีมาปัจจุบัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ขึ้น. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์ลงและคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเทียบเท่ากับเมท็อด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุเฝ้าระวัง [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaSimpleType](./xmlschemasimpletype/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaSimpleType](./). |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaType](../xmlschematype/). |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## การนิยามประเภท

| ชื่อ typedef | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## ดูเพิ่มเติม

* คลาส [XmlSchemaType](../xmlschematype/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)