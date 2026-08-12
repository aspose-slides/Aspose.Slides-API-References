---
title: XmlSchemaInfo
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นตัวแทนของชุดข้อมูลผลลัพธ์หลังการตรวจสอบสคีมาของโหนด XML ที่ผ่านการตรวจสอบแล้ว.
type: docs
weight: 521
url: /th/system.xml.schema/xmlschemainfo/
---
## XmlSchemaInfo คลาส

เป็นตัวแทนของชุดข้อมูลผลลัพธ์หลังการตรวจสอบสคีมาของโหนด XML ที่ผ่านการตรวจสอบแล้ว.

```cpp
class XmlSchemaInfo : public System::Xml::Schema::IXmlSchemaInfo
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบค่าประเภทในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | คืนค่าอ็อบเจกต์ XmlSchemaContentType ที่สอดคล้องกับประเภทเนื้อหาของโหนด XML ที่ตรวจสอบนี้. |
| **bool** [get_IsDefault](./get_isdefault/)() override | คืนค่าบ่งชี้ว่าโหนด XML ที่ตรวจสอบนี้ถูกตั้งค่าเป็นผลลัพธ์ของการใช้ค่าเริ่มต้นระหว่างการตรวจสอบสคีม่า XML [Schema](../) Definition Language (XSD) หรือไม่. |
| **bool** [get_IsNil](./get_isnil/)() override | คืนค่าบ่งชี้ว่าค่าสำหรับโหนด XML ที่ตรวจสอบนี้เป็น **nil** หรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_MemberType](./get_membertype/)() override | คืนประเภทสคีม่าแบบไดนามิกสำหรับโหนด XML ที่ตรวจสอบนี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\> [get_SchemaAttribute](./get_schemaattribute/)() override | คืนอ็อบเจกต์ [XmlSchemaAttribute](../xmlschemaattribute/) ที่คอมไพล์แล้วซึ่งสอดคล้องกับโหนด XML ที่ตรวจสอบนี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaElement](../xmlschemaelement/)\> [get_SchemaElement](./get_schemaelement/)() override | คืนอ็อบเจกต์ [XmlSchemaElement](../xmlschemaelement/) ที่คอมไพล์แล้วซึ่งสอดคล้องกับโหนด XML ที่ตรวจสอบนี้. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() override | คืนประเภทสคีม่า XML [Schema](../) Definition Language (XSD) แบบคงที่ของโหนด XML ที่ตรวจสอบนี้. |
| [XmlSchemaValidity](../xmlschemavalidity/) [get_Validity](./get_validity/)() override | คืนค่าความถูกต้อง XmlSchemaValidity ของโหนด XML ที่ตรวจสอบนี้. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการทำงานคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดการทำสำเนาประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกอะไร เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่คัดลอกอะไร เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [set_ContentType](./set_contenttype/)([XmlSchemaContentType](../xmlschemacontenttype/)) | ตั้งค่าอ็อบเจกต์ XmlSchemaContentType ที่สอดคล้องกับประเภทเนื้อหาของโหนด XML ที่ตรวจสอบนี้. |
| void [set_IsDefault](./set_isdefault/)(**bool**) | ตั้งค่าบ่งชี้ว่าโหนด XML ที่ตรวจสอบนี้ถูกตั้งค่าเป็นผลลัพธ์ของการใช้ค่าเริ่มต้นระหว่างการตรวจสอบสคีม่า XML [Schema](../) Definition Language (XSD) หรือไม่. |
| void [set_IsNil](./set_isnil/)(**bool**) | ตั้งค่าบ่งชี้ว่าค่าสำหรับโหนด XML ที่ตรวจสอบนี้เป็น **nil** หรือไม่. |
| void [set_MemberType](./set_membertype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | ตั้งค่าประเภทสคีม่าแบบไดนามิกสำหรับโหนด XML ที่ตรวจสอบนี้. |
| void [set_SchemaAttribute](./set_schemaattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\&) | ตั้งค่าอ็อบเจกต์ [XmlSchemaAttribute](../xmlschemaattribute/) ที่คอมไพล์แล้วซึ่งสอดคล้องกับโหนด XML ที่ตรวจสอบนี้. |
| void [set_SchemaElement](./set_schemaelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaElement](../xmlschemaelement/)\>\&) | ตั้งค่าอ็อบเจกต์ [XmlSchemaElement](../xmlschemaelement/) ที่คอมไพล์แล้วซึ่งสอดคล้องกับโหนด XML ที่ตรวจสอบนี้. |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | ตั้งค่าประเภทสคีม่า XML [Schema](../) Definition Language (XSD) แบบคงที่ของโหนด XML ที่ตรวจสอบนี้. |
| void [set_Validity](./set_validity/)([XmlSchemaValidity](../xmlschemavalidity/)) | ตั้งค่าความถูกต้อง XmlSchemaValidity ของโหนด XML ที่ตรวจสอบนี้. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference count. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference count. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
|  [XmlSchemaInfo](./xmlschemainfo/)() | เริ่มต้นอินสแตนซ์ใหม่ของ [XmlSchemaInfo](./) คลาส. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## การนิยามประเภท

| ประเภทนิยาม | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | เป็นนามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |
## หมายเหตุ

อ็อบเจกต์ของคลาสนี้ควรได้รับการจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ในพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

## ดูเพิ่มเติม

* คลาส [IXmlSchemaInfo](../ixmlschemainfo/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)