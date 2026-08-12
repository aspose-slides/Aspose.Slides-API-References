---
title: XmlSchemaValidator
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นเอนจิ้นการตรวจสอบสกีม XML Schema Definition Language (XSD) Schema. คลาส XmlSchemaValidator ไม่สามารถสืบทอดได้.
type: docs
weight: 937
url: /th/system.xml.schema/xmlschemavalidator/
---
## XmlSchemaValidator คลาส

Represents an XML [Schema](../) Definition Language (XSD) [Schema](../) validation engine. The [XmlSchemaValidator](./) class cannot be inherited.

```cpp
class XmlSchemaValidator : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| void [AddSchema](./addschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | เพิ่มสกีม XML [Schema](../) Definition Language (XSD) ไปยังชุดสกีมที่ใช้สำหรับการตรวจสอบ |
| void [EndValidation](./endvalidation/)() | สิ้นสุดการตรวจสอบและตรวจสอบข้อจำกัดเอกลักษณ์สำหรับเอกสาร XML ทั้งหมด |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่พิจารณา NaN สองค่าว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่พิจารณา NaN สองค่าว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\> [get_LineInfoProvider](./get_lineinfoprovider/)() | ส่งคืนข้อมูลหมายเลขบรรทัดของโหนด XML ที่กำลังตรวจสอบ |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_SourceUri](./get_sourceuri/)() | ส่งคืน URI แหล่งที่มาของโหนด XML ที่กำลังตรวจสอบ |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ValidationEventSender](./get_validationeventsender/)() | ส่งคืนอ็อบเจ็กต์ที่ส่งเป็นอ็อบเจ็กต์ผู้ส่งของเหตุการณ์การตรวจสอบ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\> [GetExpectedAttributes](./getexpectedattributes/)() | ส่งคืนแอตทริบิวต์ที่คาดหวังสำหรับบริบทขององค์ประกอบปัจจุบัน |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\> [GetExpectedParticles](./getexpectedparticles/)() | ส่งคืนพาร์ติเคิลที่คาดหวังในบริบทขององค์ประกอบปัจจุบัน |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) สนับสนุนการสร้างแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นคล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| void [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\>\&) | ตรวจสอบข้อจำกัดเอกลักษณ์ของแอตทริบิวต์เริ่มต้นและเติมรายการที่ระบุด้วยอ็อบเจ็กต์ [XmlSchemaAttribute](../xmlschemaattribute/) สำหรับแอตทริบิวต์ที่มีค่าตั้งต้นซึ่งยังไม่ได้รับการตรวจสอบโดยใช้เมธอด [XmlSchemaValidator::ValidateAttribute](./validateattribute/) ในบริบทขององค์ประกอบ |
| void [Initialize](./initialize/)() | เริ่มต้นสถานะของอ็อบเจ็กต์ [XmlSchemaValidator](./) |
| void [Initialize](./initialize/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | เริ่มต้นสถานะของอ็อบเจ็กต์ [XmlSchemaValidator](./) โดยใช้ [XmlSchemaObject](../xmlschemaobject/) ที่ระบุสำหรับการตรวจสอบบางส่วน |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นคล้ายกับโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้ประโยค [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นคล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์และเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไร จริง ๆ แล้วเพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_LineInfoProvider](./set_lineinfoprovider/)(const [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\>\&) | ตั้งค่าข้อมูลหมายเลขบรรทัดของโหนด XML ที่กำลังตรวจสอบ |
| void [set_SourceUri](./set_sourceuri/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | ตั้งค่า URI แหล่งที่มาของโหนด XML ที่กำลังตรวจสอบ |
| void [set_ValidationEventSender](./set_validationeventsender/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | ตั้งค่าอ็อบเจ็กต์ที่ส่งเป็นอ็อบเจ็กต์ผู้ส่งของเหตุการณ์การตรวจสอบ |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | ตั้งค่าอ็อบเจ็กต์ [XmlResolver](../../system.xml/xmlresolver/) ที่ใช้แก้ไของค์ประกอบ **xs:import** และ **xs:include** รวมถึงแอตtribut **xsi:schemaLocation** และ **xsi:noNamespaceSchemaLocation** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (ไม่ใช่ shared) เพื่อให้สามารถเปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [SkipToEndElement](./skiptoendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | ข้ามการตรวจสอบเนื้อหาองค์ประกอบปัจจุบันและเตรียมอ็อบเจ็กต์ [XmlSchemaValidator](./) เพื่อตรวจสอบเนื้อหาในบริบทขององค์ประกอบแม่ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นคล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้ประโยค [LockContext](../../system/lockcontext/) |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | ตรวจสอบชื่อแอตทริบิวต์, URI ของเนมสเปซ, และค่าในบริบทขององค์ประกอบปัจจุบัน |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [XmlValueGetter](../xmlvaluegetter/), const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | ตรวจสอบชื่อแอตทริบิวต์, URI ของเนมสเปซ, และค่าในบริบทขององค์ประกอบปัจจุบัน |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | ตรวจสอบองค์ประกอบในบริบทปัจจุบัน |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ตรวจสอบองค์ประกอบในบริบทปัจจุบันพร้อมค่าของแอตทริบิวต์ **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation**, และ **xsi:NoNamespaceSchemaLocation** ที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | ตรวจสอบว่าข้อความขององค์ประกอบเป็นไปตามประเภทข้อมูลสำหรับองค์ประกอบที่มีเนื้อหาง่าย และตรวจสอบว่าข้อความขององค์ประกอบปัจจุบันสมบูรณ์สำหรับองค์ประกอบที่มีเนื้อหาซับซ้อน |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | ตรวจสอบว่าข้อความขององค์ประกอบที่ระบุเป็นไปตามประเภทข้อมูลของมัน |
| void [ValidateEndOfAttributes](./validateendofattributes/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | ตรวจสอบว่ามีแอตทริบิวต์ที่จำเป็นทั้งหมดในบริบทขององค์ประกอบหรือไม่และเตรียมอ็อบเจ็กต์ [XmlSchemaValidator](./) เพื่อตรวจสอบเนื้อหาเด็กขององค์ประกอบ |
| void [ValidateText](./validatetext/)(const [String](../../system/string/)\&) | ตรวจสอบว่าข้อความ **string** ที่ระบุอนุญาตในบริบทขององค์ประกอบหรือไม่และเก็บข้อความเพื่อการตรวจสอบหากองค์ประกอบมีเนื้อหาง่าย |
| void [ValidateText](./validatetext/)([XmlValueGetter](../xmlvaluegetter/)) | ตรวจสอบว่าข้อความที่คืนจากอ็อบเจ็กต์ XmlValueGetter ที่ระบุอนุญาตในบริบทขององค์ประกอบหรือไม่และเก็บข้อความเพื่อการตรวจสอบหากองค์ประกอบมีเนื้อหาง่าย |
| void [ValidateWhitespace](./validatewhitespace/)(const [String](../../system/string/)\&) | ตรวจสอบว่าช่องว่างใน **string** ที่ระบุนั้นอนุญาตในบริบทขององค์ประกอบหรือไม่และเก็บช่องว่างเพื่อการตรวจสอบหากองค์ประกอบมีเนื้อหาง่าย |
| void [ValidateWhitespace](./validatewhitespace/)([XmlValueGetter](../xmlvaluegetter/)) | ตรวจสอบว่าช่องว่างที่คืนจากอ็อบเจ็กต์ XmlValueGetter ที่ระบุอนุญาตในบริบทขององค์ประกอบหรือไม่และเก็บช่องว่างเพื่อการตรวจสอบหากองค์ประกอบมีเนื้อหาง่าย |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
|  [XmlSchemaValidator](./xmlschemavalidator/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>\&, [XmlSchemaValidationFlags](../xmlschemavalidationflags/)) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaValidator](./) |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์และปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## การกำหนดชนิด

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้ |

## หมายเหตุ

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)