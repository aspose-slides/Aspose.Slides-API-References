---
title: XmlSchemaMinLengthFacet
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงองค์ประกอบ minLength จาก XML Schema ตามที่กำหนดโดย World Wide Web Consortium (W3C). คลาสนี้สามารถใช้เพื่อกำหนดข้อจำกัดความยาวขั้นต่ำของค่าข้อมูลขององค์ประกอบ simpleType. ความยาวต้องมากกว่าค่าขององค์ประกอบ minLength.
type: docs
weight: 638
url: /th/system.xml.schema/xmlschemaminlengthfacet/
---
## XmlSchemaMinLengthFacet คลาส


แสดงถึงองค์ประกอบ **minLength** จาก XML [Schema](../) ตามที่ระบุโดย World Wide [Web](../../system.web/) Consortium (W3C). คลาสนี้สามารถใช้เพื่อระบุข้อจำกัดของความยาวขั้นต่ำของค่าข้อมูลขององค์ประกอบ **simpleType**. ความยาวต้องมากกว่าค่าขององค์ประกอบ **minLength**.

```cpp
class XmlSchemaMinLengthFacet : public System::Xml::Schema::XmlSchemaNumericFacet
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ชนิดอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ชนิดค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point ในสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าที่ใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point ในสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าที่ใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | คืนค่า property **annotation** |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | คืนค่า string id |
| virtual **bool** [get_IsFixed](../xmlschemafacet/get_isfixed/)() | คืนข้อมูลที่บ่งชี้ว่า facet นี้เป็นค่าตายตัว |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | คืนค่าเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | คืนค่าตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | คืนค่า XmlSerializerNamespaces ที่ใช้กับวัตถุ schema นี้ |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | คืนค่าพาเรนท์ของ [XmlSchemaObject](../xmlschemaobject/) นี้ |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | คืนค่าตำแหน่งที่มาของไฟล์ที่โหลด schema |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | คืนค่าแอตทริบิวต์ที่ qualified และไม่อยู่ใน target namespace ของ schema ปัจจุบัน |
| [String](../../system/string/) [get_Value](../xmlschemafacet/get_value/)() | คืนค่าแอตทริบิวต์ **value** ของ facet |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเวอร์ชันของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจกต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นเวอร์ชันของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นเวอร์ชันของออปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเวอร์ชันของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนของประเภทที่กำหนดเอง |
| [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดการคัดลอกสำหรับซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดการคัดลอกสำหรับซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ชนิดค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | ตั้งค่า property **annotation** |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | ตั้งค่า string id |
| virtual void [set_IsFixed](../xmlschemafacet/set_isfixed/)(**bool**) | ตั้งค่าข้อมูลที่บ่งชี้ว่า facet นี้เป็นค่าตายตัว |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | ตั้งค่าเลขบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | ตั้งค่าตำแหน่งบรรทัดในไฟล์ที่องค์ประกอบ **schema** อ้างอิง |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | ตั้งค่า XmlSerializerNamespaces ที่ใช้กับวัตถุ schema นี้ |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | ตั้งค่าพาเรนท์ของ [XmlSchemaObject](../xmlschemaobject/) นี้ |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | ตั้งค่าตำแหน่งที่มาของไฟล์ที่โหลด schema |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | ตั้งค่าแอตทริบิวต์ที่ qualified และไม่อยู่ใน target namespace ของ schema ปัจจุบัน |
| void [set_Value](../xmlschemafacet/set_value/)(const [String](../../system/string/)\&) | ตั้งค่าแอตทริบิวต์ **value** ของ facet |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเวอร์ชันของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็น string |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector |
| [XmlSchemaFacet](../xmlschemafacet/xmlschemafacet/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaFacet](../xmlschemafacet/) |
| [XmlSchemaMinLengthFacet](./xmlschemaminlengthfacet/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaMinLengthFacet](./) |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaObject](../xmlschemaobject/) |
| virtual [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## นิยามประเภท

| นิยามประเภท | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | ชื่อแทนของ shared pointer ไปยังอินสแตนซ์ของคลาสนี้ |

## หมายเหตุ



วัตถุของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดระหว่างรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นั้นเพื่อส่งไปยังฟังก์ชันเป็นอาร์กิวเมนต์. 

## ดูเพิ่มเติม

* คลาส [XmlSchemaNumericFacet](../xmlschemanumericfacet/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)