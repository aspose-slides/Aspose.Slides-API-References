---
title: XmlSchemaAttribute
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึงองค์ประกอบ attribute จาก XML Schema ตามที่กำหนดโดย World Wide Web Consortium (W3C). แอตทริบิวต์ให้ข้อมูลเพิ่มเติมสำหรับองค์ประกอบเอกสารอื่น ๆ. แท็ก attribute จะซ่อนอยู่ระหว่างแท็กขององค์ประกอบเอกสารสำหรับสคีมา. เอกสาร XML แสดงแอตทริบิวต์เป็นรายการที่มีชื่อในแท็กเปิดขององค์ประกอบ.
type: docs
weight: 170
url: /th/system.xml.schema/xmlschemaattribute/
---
## XmlSchemaAttribute คลาส


Represents the **attribute** element from the XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). **แอตทริบิวต์** provide additional information for other document elements. The **attribute** tag is nested between the tags of a document's element for the schema. The XML document displays **แอตทริบิวต์** as named items in the opening tag of an element.

```cpp
class XmlSchemaAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## วิธีการ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | คืนค่า property **annotation** |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_AttributeSchemaType](./get_attributeschematype/)() | คืนค่าอ็อบเจ็กต์ [XmlSchemaSimpleType](../xmlschemasimpletype/) ที่แสดงประเภทของแอตทริบิวต์ตามค่า [XmlSchemaAttribute::get_SchemaType](./get_schematype/) หรือ [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) ของแอตทริบิวต์ |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_AttributeType](./get_attributetype/)() | คืนค่าอ็อบเจ็กต์โดยอ้างอิงค่ [XmlSchemaAttribute::get_SchemaType](./get_schematype/) หรือ [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) ของแอตทริบิวต์ซึ่งเก็บการตีความหลังการคอมไพล์ของค่า **AttributeType** |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | คืนค่าตั้งต้นของแอตทริบิวต์ |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | คืนค่าแบบคงที่ของแอตทริบิวต์ |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | คืนค่ารูปแบบของแอตทริบิวต์ |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | คืนค่า ID เป็นสตริง |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | คืนหมายเลขบรรทัดในไฟล์ที่ส่วน **schema** อ้างอิง |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | คืนตำแหน่งบรรทัดในไฟล์ที่ส่วน **schema** อ้างอิง |
| [String](../../system/string/) [get_Name](./get_name/)() | คืนชื่อของแอตทริบิวต์ |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | คืนค่า XmlSerializerNamespaces ที่ใช้กับอ็อบเจ็กต์สคีมานี้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | คืนพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | คืนชื่อที่มีคุณลักษณะของแอตทริบิวต์ |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | คืนชื่อของแอตทริบิวต์ที่ประกาศในสคีมานี้ (หรือสคีม่าอื่นที่กำหนดโดยเนมสเปซที่ระบุ) |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_SchemaType](./get_schematype/)() | คืนประเภทแอตทริบิวต์เป็นชนิดพื้นฐาน |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | คืนชื่อของชนิดพื้นฐานที่กำหนดในสคีมานี้ (หรือสคีม่าอื่นที่ระบุโดยเนมสเปซ) |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | คืนตำแหน่งที่มาของไฟล์ที่โหลดสคีม่า |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | คืนแอตทริบิวต์ที่มีคุณลักษณะซึ่งไม่อยู่ในเนมสเปซเป้าหมายของสคีม่าในปัจจุบัน |
| [XmlSchemaUse](../xmlschemause/) [get_Use](./get_use/)() | คืนข้อมูลเกี่ยวกับการใช้แอตทริบิวต์ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ออนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์แบบกำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. ออนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. ออนาล็อกของตัวดำเนินการ C# 'is' |
| void [Lock](../../system/object/lock/)() | ดำเนินการตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ออนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอ่งานใด ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาคอนสตรัคเตอร์ของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอ่งานใด ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาคอนสตรัคเตอร์ของซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับการอ้างอิงร่วมตามค่าที่ระบุ |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | ตั้งค่า property **annotation** |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | ตั้งค่าตั้งต้นของแอตทริบิวต์ |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | ตั้งค่าค่าแบบคงที่ของแอตทริบิวต์ |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | ตั้งค่ารูปแบบของแอตทริบิวต์ |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | ตั้งค่า ID เป็นสตริง |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | ตั้งหมายเลขบรรทัดในไฟล์ที่ส่วน **schema** อ้างอิง |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | ตั้งตำแหน่งบรรทัดในไฟล์ที่ส่วน **schema** อ้างอิง |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | ตั้งค่าชื่อของแอตทริบิวต์ |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | ตั้งค่า XmlSerializerNamespaces ที่ใช้กับอ็อบเจ็กต์สคีม่านี้ |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | ตั้งค่าพาเรนต์ของ [XmlSchemaObject](../xmlschemaobject/) นี้ |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | ตั้งค่าชื่อของแอตทริบิวต์ที่ประกาศในสคีมานี้ (หรือสคีม่าอื่นที่ระบุโดยเนมสเปซ) |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | ตั้งค่าประเภทแอตทริบิวต์เป็นชนิดพื้นฐาน |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | ตั้งค่าชื่อของชนิดพื้นฐานที่กำหนดในสคีมานี้ (หรือสคีม่าอื่นที่ระบุโดยเนมสเปซ) |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | ตั้งค่าตำแหน่งที่มาของไฟล์ที่โหลดสคีม่า |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ตั้งค่าแอตทริบิวต์ที่มีคุณลักษณะซึ่งไม่อยู่ในเนมสเปซเป้าหมายของสคีม่าในปัจจุบัน |
| void [set_Use](./set_use/)([XmlSchemaUse](../xmlschemause/)) | ตั้งค่าข้อมูลเกี่ยวกับการใช้แอตทริบิวต์ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ออนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
|  [XmlSchemaAttribute](./xmlschemaattribute/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaAttribute](./) |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/) |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## การกำหนดประเภท

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | ชื่อแทนสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้ |
## หมายเหตุ



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

## ดูเพิ่มเติม

* คลาส [XmlSchemaAnnotated](../xmlschemaannotated/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)