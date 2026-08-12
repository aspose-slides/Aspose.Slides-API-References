---
title: XmlSchemaInclude
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนขององค์ประกอบ include จาก XML Schema ตามที่กำหนดโดย World Wide Web Consortium (W3C) คลาสนี้ใช้เพื่อรวมการประกาศและคำนิยามจากสกีมานอก ซึ่งการประกาศและคำนิยามที่ถูกรวมจะพร้อมสำหรับการประมวลผลในสกีมาที่บรรจุอยู่
type: docs
weight: 495
url: /th/system.xml.schema/xmlschemainclude/
---
## XmlSchemaInclude คลาส

Represents the **include** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This class is used to include declarations and definitions from an external schema. The included declarations and definitions are then available for processing in the containing schema.

```cpp
class XmlSchemaInclude : public System::Xml::Schema::XmlSchemaExternal
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](./get_annotation/)() | คืนค่าคุณลักษณะ **annotation**. |
| [String](../../system/string/) [get_Id](../xmlschemaexternal/get_id/)() | คืนค่า id ของสตริง. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | คืนค่าหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | คืนค่าตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | คืนค่า XmlSerializerNamespaces เพื่อใช้กับอ็อบเจ็กต์ schema นี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | คืนค่าพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [get_Schema](../xmlschemaexternal/get_schema/)() | คืนค่า [XmlSchema](../xmlschema/) สำหรับ schema ที่อ้างอิง. |
| [String](../../system/string/) [get_SchemaLocation](../xmlschemaexternal/get_schemalocation/)() | คืนค่า Uniform Resource Identifier (URI) ของ schema ซึ่งบอกตัวประมวลผลว่า schema อยู่ที่ใด. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | คืนค่าตำแหน่งแหล่งที่มาของไฟล์ที่โหลด schema. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaexternal/get_unhandledattributes/)() | คืนค่าแอททริบิวต์ที่มีคุณสมบัติ qualified ที่ไม่อยู่ในเนมสเปซเป้าหมายของ schema. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และให้สามารถสร้างสำเนาของซับคลาสได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และให้สามารถสร้างสำเนาของซับคลาสได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Annotation](./set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | ตั้งค่าคุณลักษณะ **annotation**. |
| void [set_Id](../xmlschemaexternal/set_id/)(const [String](../../system/string/)\&) | ตั้งค่า id ของสตริง. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | ตั้งค่าหมายเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | ตั้งค่าตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | ตั้งค่า XmlSerializerNamespaces เพื่อใช้กับอ็อบเจ็กต์ schema นี้. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | ตั้งค่าพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้. |
| void [set_Schema](../xmlschemaexternal/set_schema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | ตั้งค่า [XmlSchema](../xmlschema/) สำหรับ schema ที่อ้างอิง. |
| void [set_SchemaLocation](../xmlschemaexternal/set_schemalocation/)(const [String](../../system/string/)\&) | ตั้งค่า Uniform Resource Identifier (URI) ของ schema ซึ่งบอกตัวประมวลผลว่า schema อยู่ที่ใด. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | ตั้งค่าตำแหน่งแหล่งที่มาของไฟล์ที่โหลด schema. |
| void [set_UnhandledAttributes](../xmlschemaexternal/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ตั้งค่าแอททริบิวต์ที่มีคุณสมบัติ qualified ที่ไม่อยู่ในเนมสเปซเป้าหมายของ schema. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). ช่วยให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
|  [XmlSchemaExternal](../xmlschemaexternal/xmlschemaexternal/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaExternal](../xmlschemaexternal/). |
|  [XmlSchemaInclude](./xmlschemainclude/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaInclude](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/). |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## การนิยามประเภท

| การนิยามประเภท | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงของ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## ดูเพิ่มเติม

* คลาส [XmlSchemaExternal](../xmlschemaexternal/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)