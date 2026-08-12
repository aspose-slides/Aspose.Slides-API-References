---
title: XmlParserContext
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ให้ข้อมูลบริบททั้งหมดที่จำเป็นสำหรับ XmlReader เพื่อแยกส่วน XML
type: docs
weight: 391
url: /th/system.xml/xmlparsercontext/
---
## XmlParserContext คลาส


ให้ข้อมูลบริบททั้งหมดที่จำเป็นสำหรับ [XmlReader](../xmlreader/) ในการแยกส่วน XML fragment

```cpp
class XmlParserContext : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | คืนค่า URI พพื้นฐาน. |
| [String](../../system/string/) [get_DocTypeName](./get_doctypename/)() | คืนค่าชื่อของการประกาศประเภทเอกสาร. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | คืนค่าแบบเข้ารหัส. |
| [String](../../system/string/) [get_InternalSubset](./get_internalsubset/)() | คืนค่าชุดย่อย DTD ภายใน. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\> [get_NamespaceManager](./get_namespacemanager/)() | คืนค่า [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | คืนค่า [XmlNameTable](../xmlnametable/) ที่ใช้เพื่อทำให้สตริงเป็นอะตอม สำหรับข้อมูลเพิ่มเติมเกี่ยวกับสตริงที่ทำให้เป็นอะตอม ดูที่ [XmlNameTable](../xmlnametable/). |
| [String](../../system/string/) [get_PublicId](./get_publicid/)() | คืนค่าตัวระบุสาธารณะ. |
| [String](../../system/string/) [get_SystemId](./get_systemid/)() | คืนค่าตัวระบุระบบ. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | คืนค่าช่วง **xml:lang** ปัจจุบัน. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | คืนค่าช่วง **xml:space** ปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการทำงานที่คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ที่ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ เป็นการทำงานที่คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นการทำงานที่คล้ายกับออปเจรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการทำงานที่คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ที่ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr ด้วยการอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_BaseURI](./set_baseuri/)(const [String](../../system/string/)\&) | กำหนดค่า base URI. |
| void [set_DocTypeName](./set_doctypename/)(const [String](../../system/string/)\&) | กำหนดชื่อของการประกาศประเภทเอกสาร. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | กำหนดแบบเข้ารหัส. |
| void [set_InternalSubset](./set_internalsubset/)(const [String](../../system/string/)\&) | กำหนดชุดย่อย DTD ภายใน. |
| void [set_NamespaceManager](./set_namespacemanager/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | กำหนดค่า [XmlNamespaceManager](../xmlnamespacemanager/). |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | กำหนดค่า [XmlNameTable](../xmlnametable/) ที่ใช้เพื่อทำให้สตริงเป็นอะตอม สำหรับข้อมูลเพิ่มเติมเกี่ยวกับสตริงที่ทำให้เป็นอะตอม ดูที่ [XmlNameTable](../xmlnametable/). |
| void [set_PublicId](./set_publicid/)(const [String](../../system/string/)\&) | กำหนดตัวระบุสาธารณะ. |
| void [set_SystemId](./set_systemid/)(const [String](../../system/string/)\&) | กำหนดตัวระบุระบบ. |
| void [set_XmlLang](./set_xmllang/)(const [String](../../system/string/)\&) | กำหนดช่วง **xml:lang** ปัจจุบัน. |
| void [set_XmlSpace](./set_xmlspace/)([System::Xml::XmlSpace](../xmlspace/)) | กำหนดช่วง **xml:space** ปัจจุบัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared) ทำให้สามารถสลับ pointer ในคอนเทนเนอร์ให้เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า ควรไม่เรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเมธอดที่คล้ายกับ C# [Object.ToString()](../../system/object/tostring/) ที่ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference ควรไม่เรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference ควรไม่เรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/)) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlParserContext](./) ด้วยค่า [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, และ **xml:space** ที่ระบุ. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/), const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlParserContext](./) ด้วยค่า [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, **xml:space**, และแบบเข้ารหัส. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/)) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlParserContext](./) ด้วยค่า [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, และค่าเอกสารประเภท. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/), const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [XmlParserContext](./) ด้วยค่า [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, แบบเข้ารหัส, และค่าเอกสารประเภท. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ลบโครงสร้างข้อมูลภายในทั้งหมด. |

## การกำหนดประเภท

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ



วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดระหว่างการทำงานและ/หรือการล้มเหลวของการอ้างอิง ควรห่อคลาสนี้ด้วย pointer [System::SmartPtr](../../system/smartptr/) และใช้ pointer นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)