---
title: XmlSchemaAny
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แทน any element ของ World Wide Web Consortium (W3C).
type: docs
weight: 131
url: /th/system.xml.schema/xmlschemaany/
---
## XmlSchemaAny คลาส


แสดงถึง World Wide [Web](../../system.web/) Consortium (W3C) **any** element.

```cpp
class XmlSchemaAny : public System::Xml::Schema::XmlSchemaParticle
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิด C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | คืนค่า property **annotation**. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | คืนค่า ID ของสตริง. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | คืนค่าเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | คืนค่าตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | คืนค่าจำนวนสูงสุดที่ particle สามารถเกิดขึ้นได้. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | คืนค่าตัวเลขเป็นสตริง จำนวนสูงสุดที่ particle สามารถเกิดขึ้นได้. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | คืนค่าจำนวนต่ำสุดที่ particle สามารถเกิดขึ้นได้. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | คืนค่าตัวเลขเป็นสตริง จำนวนต่ำสุดที่ particle สามารถเกิดขึ้นได้. |
| [String](../../system/string/) [get_Namespace](./get_namespace/)() | คืนค่า namespace ที่มีองค์ประกอบที่สามารถใช้ได้. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | คืนค่า XmlSerializerNamespaces ที่ใช้กับวัตถุ schema นี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | คืนค่าพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| [XmlSchemaContentProcessing](../xmlschemacontentprocessing/) [get_ProcessContents](./get_processcontents/)() | คืนข้อมูลว่าการประยุกต์หรือโปรเซสเซอร์ XML ควรจัดการการตรวจสอบความถูกต้องของเอกสาร XML สำหรับองค์ประกอบที่ระบุโดย **any** อย่างไร. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | คืนตำแหน่งที่มาของไฟล์ที่โหลด schema. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | คืนค่าแอตทริบิวต์ที่ผ่านการกำหนดคุณสมบัติที่ไม่อยู่ใน target namespace ของ schema ปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่ targetType ระบุ คล้ายตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เหมือนคำสั่ง lock() ของ C# ใช้โดยเรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning ชนิดที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สับคลาสย่อยสามารถคัดลอกสร้างได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สับคลาสย่อยสามารถคัดลอกสร้างได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงกับอ็อบเจ็กต์ประเภทค่าโดยใช้ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | กำหนดค่า property **annotation**. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | กำหนดค่า ID ของสตริง. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | กำหนดเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | กำหนดตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | กำหนดจำนวนสูงสุดที่ particle สามารถเกิดขึ้นได้. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | กำหนดเลขเป็นสตริง จำนวนสูงสุดที่ particle สามารถเกิดขึ้นได้. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | กำหนดจำนวนต่ำสุดที่ particle สามารถเกิดขึ้นได้. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | กำหนดเลขเป็นสตริง จำนวนต่ำสุดที่ particle สามารถเกิดขึ้นได้. |
| void [set_Namespace](./set_namespace/)(const [String](../../system/string/)\&) | กำหนด namespace ที่มีองค์ประกอบที่สามารถใช้ได้. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | กำหนด XmlSerializerNamespaces ที่ใช้กับวัตถุ schema นี้. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | กำหนดพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| void [set_ProcessContents](./set_processcontents/)([XmlSchemaContentProcessing](../xmlschemacontentprocessing/)) | กำหนดข้อมูลว่าการประยุกต์หรือโปรเซสเซอร์ XML ควรจัดการการตรวจสอบความถูกต้องของเอกสาร XML สำหรับองค์ประกอบที่ระบุโดย **any** อย่างไร. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | กำหนดตำแหน่งที่มาของไฟล์ที่โหลด schema. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | กำหนดแอตทริบิวต์ที่ผ่านการกำหนดคุณสมบัติที่ไม่อยู่ใน target namespace ของ schema ปัจจุบัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n เป็น weak pointer (แทน shared) ทำให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่แชร์ ควรใช้ smart pointers หรือ ThisProtector แทนการเรียกโดยตรง. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่แชร์ ควรใช้ smart pointers หรือ ThisProtector แทนการเรียกโดยตรง. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่คล้าย C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่คล้าย C# lock() statement การปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak ควรใช้ smart pointers หรือ ThisProtector แทนการเรียกโดยตรง. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak ควรใช้ smart pointers หรือ ThisProtector แทนการเรียกโดยตรง. |
|  [XmlSchemaAny](./xmlschemaany/)() | สร้างอินสแตนซ์ใหม่ของคลาส [XmlSchemaAny](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | สร้างอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | สร้างอินสแตนซ์ใหม่ของคลาส [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ชนิดอ้างอิง

| ชนิดอ้างอิง | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ



อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) ไม่ควรสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือใช้โอเปอเรเตอร์ new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้งานและ/หรือการตรวจสอบความถูกต้อง ควรห่อคลาสนี้ด้วย pointer [System::SmartPtr](../../system/smartptr/) เสมอและใช้ pointer นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

## ดูเพิ่มเติม

* คลาส [XmlSchemaParticle](../xmlschemaparticle/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)