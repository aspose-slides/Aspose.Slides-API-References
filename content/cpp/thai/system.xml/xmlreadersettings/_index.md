---
title: XmlReaderSettings
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "ระบุชุดคุณสมบัติเพื่อสนับสนุนบนอ็อบเจกต์ XmlReader ที่สร้างโดยเมธอด XmlReader::Create."
type: docs
weight: 443
url: /th/system.xml/xmlreadersettings/
---
## XmlReaderSettings คลาส

ระบุชุดคุณสมบัติที่สนับสนุนบนอ็อบเจกต์ [XmlReader](../xmlreader/) ที่สร้างโดยเมธอด [XmlReader::Create](../xmlreader/create/).

```cpp
class XmlReaderSettings : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | สร้างสำเนาของอินสแตนซ์ [XmlReaderSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ลักษณะของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าจะถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ double ในสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | คืนค่าแสดงว่าควรทำการตรวจสอบอักขระหรือไม่. |
| **bool** [get_CloseInput](./get_closeinput/)() | คืนค่าแสดงว่าควรปิดสตรีมพื้นฐานหรือ TextReader เมื่อปิดรีดเดอร์หรือไม่. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | คืนค่าระดับการปฏิบัติตามที่ [XmlReader](../xmlreader/) จะสอดคล้อง. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | คืนค่าที่กำหนดการประมวลผลของ DTDs. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | คืนค่าแสดงว่าจะละเว้นคอมเมนต์หรือไม่. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | คืนค่าแสดงว่าจะละเว้นคำสั่งการประมวลผลหรือไม่. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | คืนค่าแสดงว่าจะละเว้นช่องว่างที่ไม่มีความสำคัญหรือไม่. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | คืนค่าออฟเซ็ตหมายเลขบรรทัดของอ็อบเจกต์ [XmlReader](../xmlreader/). |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | คืนค่าออฟเซ็ตตำแหน่งบรรทัดของอ็อบเจกต์ [XmlReader](../xmlreader/). |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | คืนค่าที่ระบุจำนวนอักขระสูงสุดที่อนุญาตในเอกสารที่เกิดจากการขยายเอนทิตี้. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | คืนค่าที่ระบุจำนวนอักขระสูงสุดที่อนุญาตในเอกสาร XML ค่า 0 หมายถึงไม่มีขีดจำกัดขนาดของเอกสาร XML ค่าไม่เป็นศูนย์จะระบุขนาดสูงสุดเป็นอักขระ. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | คืนค่า [XmlNameTable](../xmlnametable/) ที่ใช้สำหรับการเปรียบเทียบสตริงที่ถูกอะตอม. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | คืนค่าแสดงว่าจะห้ามการประมวลผลกำหนดประเภทเอกสาร (DTD) หรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | คืนค่า XmlSchemaSet ที่ใช้เมื่อทำการตรวจสอบสกีม่า. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | คืนค่าที่ระบุการตั้งค่าการตรวจสอบสกีม่า การตั้งค่านี้ใช้กับอ็อบเจกต์ [XmlReader](../xmlreader/) ที่ตรวจสอบสกีม่า (ค่า [XmlReaderSettings::get_ValidationType](./get_validationtype/) คือ [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | คืนค่าแสดงว่า [XmlReader](../xmlreader/) จะทำการตรวจสอบหรือกำหนดประเภทเมื่ออ่านหรือไม่. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงร่วมตามค่าที่ระบุ. |
| void [Reset](./reset/)() | รีเซ็ตสมาชิกของคลาสการตั้งค่าให้เป็นค่าเริ่มต้น. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าจะทำการตรวจสอบอักขระหรือไม่. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าต้องปิดสตรีมพื้นฐานหรือ TextReader เมื่อรีดเดอร์ถูกปิดหรือไม่. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | ตั้งค่าระดับการปฏิบัติตามที่ [XmlReader](../xmlreader/) จะสอดคล้อง. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | ตั้งค่าที่กำหนดการประมวลผลของ DTDs. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าจะละเว้นคอมเมนต์หรือไม่. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าจะละเว้นคำสั่งการประมวลผลหรือไม่. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าจะละเว้นช่องว่างที่ไม่มีความสำคัญหรือไม่. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | ตั้งค่าออฟเซ็ตหมายเลขบรรทัดของอ็อบเจกต์ [XmlReader](../xmlreader/). |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | ตั้งค่าออฟเซ็ตตำแหน่งบรรทัดของอ็อบเจกต์ [XmlReader](../xmlreader/). |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | ตั้งค่าที่ระบุจำนวนอักขระสูงสุดที่อนุญาตในเอกสารที่เกิดจากการขยายเอนทิตี้. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | ตั้งค่าที่ระบุจำนวนอักขระสูงสุดที่อนุญาตในเอกสาร XML ค่า 0 หมายถึงไม่มีขีดจำกัดขนาดของเอกสาร XML ค่าไม่เป็นศูนย์จะระบุขนาดสูงสุดเป็นอักขระ. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | ตั้งค่า [XmlNameTable](../xmlnametable/) ที่ใช้สำหรับการเปรียบเทียบสตริงที่ถูกอะตอม. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าจะห้ามการประมวลผลกำหนดประเภทเอกสาร (DTD) หรือไม่. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | ตั้งค่า XmlSchemaSet ที่ใช้เมื่อทำการตรวจสอบสกีม่า. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | ตั้งค่าที่บ่งชี้การตั้งค่าการตรวจสอบสกีม่า การตั้งค่านี้ใช้กับอ็อบเจกต์ [XmlReader](../xmlreader/) ที่ตรวจสอบสกีม่า (ค่า [XmlReaderSettings::get_ValidationType](./get_validationtype/) คือ [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | ตั้งค่าที่บ่งชี้ว่า [XmlReader](../xmlreader/) จะทำการตรวจสอบหรือกำหนดประเภทเมื่ออ่านหรือไม่. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | ตั้งค่า [XmlResolver](../xmlresolver/) ที่ใช้เข้าถึงเอกสารภายนอก. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) อนุญาตการสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | เพิ่ม event handler ที่เกิดขึ้นเมื่อรีดเดอร์พบข้อผิดพลาดการตรวจสอบ. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | ลบ event handler ที่เกิดขึ้นเมื่อรีดเดอร์พบข้อผิดพลาดการตรวจสอบ. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlReaderSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## นิยามประเภท

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ

ออบเจ็กต์ของคลาสนี้ควรสร้างขึ้นเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์.

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)