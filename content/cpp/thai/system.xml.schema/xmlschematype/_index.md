---
title: XmlSchemaType
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คลาสพื้นฐานสำหรับประเภทง่ายทั้งหมดและประเภทเชิงซับซ้อนทั้งหมด.
type: docs
weight: 911
url: /th/system.xml.schema/xmlschematype/
---
## XmlSchemaType คลาส

คลาสพื้นฐานสำหรับประเภทง่ายทั้งหมดและประเภทเชิงซับซ้อนทั้งหมด.

```cpp
class XmlSchemaType : public System::Xml::Schema::XmlSchemaAnnotated
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่า IEC 60559:1989 ระบุว่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่า IEC 60559:1989 ระบุว่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | คืนค่า property **annotation**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](./get_baseschematype/)() | คืนค่าชนิดของอ็อบเจ็กต์หลังการคอมไพล์หรือชนิดข้อมูล XML [Schema](../) Definition Language (XSD) ที่สร้างไว้, simpleType element หรือ complexType element. นี่เป็นค่าชุดข้อมูล (infoset) หลังการคอมไพล์สคีมา. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\> [get_BaseXmlSchemaType](./get_basexmlschematype/)() | คืนค่าที่ได้หลังการคอมไพล์สำหรับชนิดฐานของสคีมา type นี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](./get_datatype/)() | คืนค่าที่ได้หลังการคอมไพล์สำหรับชนิดข้อมูลของ complex type. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](./get_derivedby/)() | คืนข้อมูลหลังการคอมไพล์ว่าตัวองค์ประกอบนี้ถูกสืบทอดจากชนิดฐานอย่างไร. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | คืน attribute สุดท้ายของการสืบทอดชนิดที่บ่งชี้ว่าการสืบทอดต่อไปได้รับอนุญาตหรือไม่. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | คืนการตีความหลังการคอมไพล์ของค่า [XmlSchemaType::get_Final](./get_final/). |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | คืนค่า id ของสตริง. |
| virtual **bool** [get_IsMixed](./get_ismixed/)() | คืนค่าที่บ่งชี้ว่าชนิดนี้มีโมเดลเนื้อหาผสมหรือไม่ การเรียกนี้ใช้ได้เฉพาะในชนิดเชิงซับซ้อนเท่านั้น. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | คืนหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | คืนตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| [String](../../system/string/) [get_Name](./get_name/)() | คืนชื่อของชนิด. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | คืนค่า XmlSerializerNamespaces ที่จะใช้กับอ็อบเจ็กต์สคีมานี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | คืนพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | คืนชื่อที่ครบถ้วนของชนิดที่สร้างจาก attribute **Name** ของชนิดนี้ นี้เป็นค่าหลังการคอมไพล์สคีมา. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | คืนตำแหน่งแหล่งที่มาของไฟล์ที่โหลดสคีมา. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](./get_typecode/)() | คืนค่า XmlTypeCode ของชนิด. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | คืนค่า attribute ที่ครบถ้วนซึ่งไม่ได้เป็นของ target namespace ของสคีมาปัจจุบัน. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | คืนค่า [XmlSchemaComplexType](../xmlschemacomplextype/) ที่แสดงถึง complex type ในตัวที่สร้างมาโดยอัตโนมัติของ complex type ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](../xmlschemacomplextype/)\> [GetBuiltInComplexType](./getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | คืนค่า [XmlSchemaComplexType](../xmlschemacomplextype/) ที่แสดงถึง complex type ในตัวที่สร้างมาโดยอัตโนมัติของ complex type ที่ระบุด้วยชื่อครบถ้วน. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | คืนค่า [XmlSchemaSimpleType](../xmlschemasimpletype/) ที่แสดงถึง simple type ในตัวที่สร้างมาโดยอัตโนมัติของ simple type ที่ระบุด้วยชื่อครบถ้วน. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](./getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | คืนค่า [XmlSchemaSimpleType](../xmlschemasimpletype/) ที่แสดงถึง simple type ในตัวที่สร้างมาโดยอัตโนมัติของ simple type ที่ระบุ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| static **bool** [IsDerivedFrom](./isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](./)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | คืนค่าที่บ่งชี้ว่าชนิดสคีมาที่สืบทอดที่ระบุเป็นชนิดสคีมาฐานที่ระบุหรือไม่. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนชนิดที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแปรรูปของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแปรรูปของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | ตั้งค่า property **annotation**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | ตั้งค่า attribute สุดท้ายของการสืบทอดชนิดที่บ่งชี้ว่าการสืบทอดต่อไปได้รับอนุญาตหรือไม่. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | ตั้งค่า string id. |
| virtual void [set_IsMixed](./set_ismixed/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าชนิดนี้มีโมเดลเนื้อหาผสมหรือไม่ การเรียกนี้ใช้ได้เฉพาะในชนิดเชิงซับซ้อนเท่านั้น. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | ตั้งหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | ตั้งตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | ตั้งชื่อของชนิด. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | ตั้งค่า XmlSerializerNamespaces ที่จะใช้กับอ็อบเจ็กต์สคีมานี้. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | ตั้งพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | ตั้งตำแหน่งแหล่งที่มาของไฟล์ที่โหลดสคีมา. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ตั้งค่า attribute ที่ครบถ้วนซึ่งไม่ได้เป็นของ target namespace ของสคีมาปัจจุบัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | สร้างอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaType](./xmlschematype/)() | สร้างอินสแตนซ์ใหม่ของคลาส [XmlSchemaType](./). |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## Typedefs

| Typedef | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ

วัตถุของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการผิดพลาดของการตรวจสอบ. ควรห่อคลาสนี้ด้วย pointer [System::SmartPtr](../../system/smartptr/) เสมอและใช้ pointer นี้ในการส่งผ่านเป็นอาร์กูเมนต์ให้กับฟังก์ชัน.

## ดูเพิ่มเติม

* คลาส [XmlSchemaAnnotated](../xmlschemaannotated/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)