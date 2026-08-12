---
title: XmlSchemaGroupRef
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงถึงองค์ประกอบ group ที่มีแอตทริบิวต์ ref จาก XML Schema ตามที่ระบุโดย World Wide Web Consortium (W3C). คลาสนี้ถูกใช้ภายในชนิดซับซ้อนที่อ้างอิงกลุ่มที่กำหนดในระดับ schema.
type: docs
weight: 456
url: /th/system.xml.schema/xmlschemagroupref/
---
## XmlSchemaGroupRef คลาส


Represents the **group** element with **ref** attribute from the XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is used within complex types that reference a **group** defined at the **schema** level.

```cpp
class XmlSchemaGroupRef : public System::Xml::Schema::XmlSchemaParticle
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้การทำงานตามเชิงปฏิบัติของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# โดยถือว่า NaN สองค่ามีค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# โดยถือว่า NaN สองค่ามีค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | คืนค่า property **annotation**. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | คืนค่า id ของสตริง. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | คืนค่าเลขบรรทัดในไฟล์ที่ **schema** อ้างถึง. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | คืนค่าเลขตำแหน่งบรรทัดในไฟล์ที่ **schema** อ้างถึง. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | คืนค่าจำนวนสูงสุดที่พาร์ติเคิลสามารถเกิดขึ้นได้. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | ตั้งค่าตัวเลขเป็นสตริง จำนวนสูงสุดที่พาร์ติเคิลสามารถเกิดขึ้นได้. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | คืนค่าจำนวนต่ำสุดที่พาร์ติเคิลสามารถเกิดขึ้นได้. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | ตั้งค่าตัวเลขเป็นสตริง จำนวนต่ำสุดที่พาร์ติเคิลสามารถเกิดขึ้นได้. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | คืนค่า XmlSerializerNamespaces ที่ใช้กับอ็อบเจ็กต์ schema นี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | คืนค่าพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaGroupBase](../xmlschemagroupbase/)\> [get_Particle](./get_particle/)() | คืนค่าเป็นหนึ่งในคลาส [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) หรือ [XmlSchemaSequence](../xmlschemasequence/) ซึ่งเก็บผลการตีความค่าของ **Particle** หลังการคอมไพล์. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | คืนค่าชื่อของกลุ่มที่กำหนดใน schema นี้ (หรือ schema อื่นที่ระบุโดยเนมสเปซที่กำหนด). |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | คืนค่าตำแหน่งแหล่งที่มาของไฟล์ที่โหลด schema. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | คืนค่าแอตทริบิวต์ที่มีคุณลักษณะครบถ้วนซึ่งไม่เป็นของเนมสเปซเป้าหมายของ schema ปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรเลย, เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรเลย, เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์แบบค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์โดยค่าที่ระบุ. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | ตั้งค่า property **annotation**. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | ตั้งค่า id ของสตริง. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | ตั้งค่าเลขบรรทัดในไฟล์ที่ **schema** อ้างถึง. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | ตั้งค่าเลขตำแหน่งบรรทัดในไฟล์ที่ **schema** อ้างถึง. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | ตั้งค่าจำนวนสูงสุดที่พาร์ติเคิลสามารถเกิดขึ้นได้. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | ตั้งค่าตัวเลขเป็นสตริง จำนวนสูงสุดที่พาร์ติเคิลสามารถเกิดขึ้นได้. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | ตั้งค่าจำนวนต่ำสุดที่พาร์ติเคิลสามารถเกิดขึ้นได้. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | ตั้งค่าตัวเลขเป็นสตริง จำนวนต่ำสุดที่พาร์ติเคิลสามารถเกิดขึ้นได้. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | ตั้งค่า XmlSerializerNamespaces ที่ใช้กับอ็อบเจ็กต์ schema นี้. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | ตั้งค่าพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | ตั้งค่าชื่อของกลุ่มที่กำหนดใน schema นี้ (หรือ schema อื่นที่ระบุโดยเนมสเปซที่กำหนด). |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | ตั้งค่าตำแหน่งแหล่งที่มาของไฟล์ที่โหลด schema. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ตั้งค่าแอตทริบิวต์ที่มีคุณลักษณะครบถ้วนซึ่งไม่เป็นของเนมสเปซเป้าหมายของ schema ปัจจุบัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับการอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
|  [XmlSchemaGroupRef](./xmlschemagroupref/)() | สร้างอินสแตนซ์ใหม่ของคลาส [XmlSchemaGroupRef](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | สร้างอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | สร้างอินสแตนซ์ใหม่ของคลาส [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ประเภทนิยาม

| ประเภทนิยาม | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |
## หมายเหตุ



อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการอ้างอิงที่ล้มเหลว. ควรห่อคลาสนี้ด้วย pointer [System::SmartPtr](../../system/smartptr/) และใช้ pointer นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

## ดูเพิ่มเติม

* คลาส [XmlSchemaParticle](../xmlschemaparticle/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)