---
title: XmlSchemaSet
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: มีแคชของสคีมาภาษา XML Schema definition language (XSD).
type: docs
weight: 781
url: /th/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet คลาส

Contains a cache of XML [Schema](../) definition language (XSD) schemas.

```cpp
class XmlSchemaSet : public System::Object
```

## เมธอด

| วิธีการ | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [String](../../system/string/)\&) | เพิ่มสคีมาภาษา XML [Schema](../) (XSD) ที่ URL ที่ระบุลงใน [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | เพิ่มสคีมาภาษา XML [Schema](../) (XSD) ที่บรรจุอยู่ใน [XmlReader](../../system.xml/xmlreader/) ไปยัง [XmlSchemaSet](./). |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](./)\>\&) | เพิ่มสคีมาภาษา XML [Schema](../) (XSD) ทั้งหมดใน [XmlSchemaSet](./) ที่กำหนดลงใน [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | เพิ่ม [XmlSchema](../xmlschema/) ที่กำหนดลงใน [XmlSchemaSet](./). |
| void [Compile](./compile/)() | คอมไพล์สคีมาภาษา XML [Schema](../) (XSD) ที่เพิ่มลงใน [XmlSchemaSet](./) ให้เป็นสคีมาลอจิกเดียว. |
| **bool** [Contains](./contains/)([String](../../system/string/)) | ระบุว่า XML [Schema](../) (XSD) ที่มี URI เนมสเปซเป้าหมายที่ระบุอยู่ใน [XmlSchemaSet](./) หรือไม่. |
| **bool** [Contains](./contains/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | ระบุว่าอ็อบเจกต์ [XmlSchema](../xmlschema/) ของ XML [Schema](../) (XSD) ที่ระบุอยู่ใน [XmlSchemaSet](./) หรือไม่. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\&, **int32_t**) | คัดลอกอ็อบเจกต์ [XmlSchema](../xmlschema/) ทั้งหมดจาก [XmlSchemaSet](./) ไปยังอาร์เรย์ที่กำหนด เริ่มจากดัชนีที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ชนิดอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ชนิดค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยในสไตล์ C# ที่ NaN สองค่า ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าชนิดใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยในสไตล์ C# ที่ NaN สองค่า ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าชนิดใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\> [get_CompilationSettings](./get_compilationsettings/)() | ส่งคืน [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) สำหรับ [XmlSchemaSet](./). |
| **int32_t** [get_Count](./get_count/)() | ส่งคืนจำนวนสคีมาภาษา XML [Schema](../) (XSD) เชิงลอจิกใน [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalAttributes](./get_globalattributes/)() | ส่งคืนแอตทริบิวต์ระดับโลกทั้งหมดในสคีมาภาษา XML [Schema](../) (XSD) ทั้งหมดใน [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalElements](./get_globalelements/)() | ส่งคืนองค์ประกอบระดับโลกทั้งหมดในสคีมาภาษา XML [Schema](../) (XSD) ทั้งหมดใน [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalTypes](./get_globaltypes/)() | ส่งคืนประเภทอย่างง่ายและซับซ้อนระดับโลกทั้งหมดในสคีมาภาษา XML [Schema](../) (XSD) ทั้งหมดใน [XmlSchemaSet](./). |
| **bool** [get_IsCompiled](./get_iscompiled/)() | ส่งคืนค่าที่ระบุว่า สคีมาภาษา XML [Schema](../) (XSD) ใน [XmlSchemaSet](./) ได้ถูกคอมไพล์หรือยัง. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | ส่งคืน [XmlNameTable](../../system.xml/xmlnametable/) เริ่มต้นที่ [XmlSchemaSet](./) ใช้เมื่อโหลดสคีมาภาษา XML [Schema](../) (XSD) ใหม่. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจกต์ คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของชนิดที่ targetType อธิบายหรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ชนิดค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | ลบสคีมาภาษา XML [Schema](../) (XSD) ที่ระบุออกจาก [XmlSchemaSet](./). |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงด้วยค่าที่ระบุ. |
| **bool** [RemoveRecursive](./removerecursive/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | ลบสคีมาภาษา XML [Schema](../) (XSD) ที่ระบุและสคีมาทั้งหมดที่มันนำเข้าจาก [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Reprocess](./reprocess/)([SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>) | ประมวลผลใหม่สคีมาภาษา XML [Schema](../) (XSD) ที่มีอยู่แล้วใน [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)() | ส่งคืนคอลเลกชันของสคีมาภาษา XML [Schema](../) (XSD) ทั้งหมดใน [XmlSchemaSet](./). |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)([String](../../system/string/)) | ส่งคืนคอลเลกชันของสคีมาภาษา XML [Schema](../) (XSD) ทั้งหมดใน [XmlSchemaSet](./) ที่เป็นของเนมสเปซที่กำหนด. |
| void [set_CompilationSettings](./set_compilationsettings/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\>\&) | ตั้งค่า [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) สำหรับ [XmlSchemaSet](./). |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | ตั้งค่า [XmlResolver](../../system.xml/xmlresolver/) ที่ใช้ในการแก้ไขเนมสเปซหรือที่ตั้งที่อ้างอิงในองค์ประกอบ include และ import ของสคีมา. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนท์เทมเพลตที่ n ให้เป็น weak pointer (แทนการแชร์) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนจำนวนอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | เพิ่มตัวจัดการเหตุการณ์เพื่อรับข้อมูลเกี่ยวกับข้อผิดพลาดการตรวจสอบสคีมาภาษา XML [Schema](../) (XSD). |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | ลบตัวจัดการเหตุการณ์สำหรับรับข้อมูลเกี่ยวกับข้อผิดพลาดการตรวจสอบสคีมาภาษา XML [Schema](../) (XSD). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
|  [XmlSchemaSet](./xmlschemaset/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaSet](./). |
|  [XmlSchemaSet](./xmlschemaset/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlSchemaSet](./) ด้วย [XmlNameTable](../../system.xml/xmlnametable/) ที่ระบุ. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## การกำหนดประเภท

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |

## หมายเหตุ

อ็อบเจกต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการขัดจังหวะการอ้างอิง ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้ฟังก์ชัน.

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Xml::Schema](../)
* ไลบรารี [Aspose.Slides](../../)