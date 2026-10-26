---
title: XslCompiledTransform
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงข้อมูล XML ด้วยแผ่นสไตล์ XSLT.
type: docs
weight: 53
url: /th/system.xml.xsl/xslcompiledtransform/
---
## XslCompiledTransform คลาส


Transforms XML data using an XSLT style sheet.

```cpp
class XslCompiledTransform : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../../system.xml/xmlwritersettings/)\> [get_OutputSettings](./get_outputsettings/)() | คืนค่าอ็อบเจกต์ [XmlWriterSettings](../../system.xml/xmlwritersettings/) ที่บรรจุข้อมูลผลลัพธ์ที่ได้จากองค์ประกอบ **xsl:output** ของสไตล์ชีท. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C#. เปิดใช้งานการทำแฮชของอ็อบเจกต์กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ คล้ายการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType คล้ายตัวดำเนินการ 'is' ของ C#. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | คอมไพล์สไตล์ชีทที่อยู่ใน [XmlReader](../../system.xml/xmlreader/). |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | คอมไพล์สไตล์ชีท XSLT ที่อยู่ใน [XmlReader](../../system.xml/xmlreader/). [XmlResolver](../../system.xml/xmlresolver/) จัดการแก้ไของค์ประกอบ **import** หรือ **include** ของ XSLT ทั้งหมดและการตั้งค่า XSLT กำหนดสิทธิ์สำหรับสไตล์ชีท. |
| void [Load](./load/)(const [String](../../system/string/)\&) | โหลดและคอมไพล์สไตล์ชีทที่อยู่ใน URI ที่ระบุ. |
| void [Load](./load/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | โหลดและคอมไพล์สไตล์ชีท XSLT ที่ระบุโดย URI. [XmlResolver](../../system.xml/xmlresolver/) จัดการแก้ไของค์ประกอบ **import** หรือ **include** ของ XSLT และการตั้งค่า XSLT กำหนดสิทธิ์สำหรับสไตล์ชีท. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&) | คอมไพล์สไตล์ชีทที่อยู่ในอ็อบเจกต์ IXPathNavigable. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>) | คอมไพล์สไตล์ชีท XSLT ที่อยู่ใน IXPathNavigable. [XmlResolver](../../system.xml/xmlresolver/) จัดการแก้ไของค์ประกอบ **import** หรือ **include** ของ XSLT และการตั้งค่า XSLT กำหนดสิทธิ์สำหรับสไตล์ชีท. |
| void [Lock](../../system/object/lock/)() | ทำงานเหมือนการล็อกด้วยคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. เปิดใช้งานการโคลนประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงร่วมโดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) เปิดใช้งานการสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. เปิดใช้งานการแปลงอ็อบเจกต์กำหนดเองเป็นสตริง. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจกต์ IXPathNavigable และส่งผลลัพธ์ไปยัง [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจกต์ IXPathNavigable และส่งผลลัพธ์ไปยัง [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) ให้พารามิเตอร์เพิ่มเติมในระหว่างทำงาน. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจกต์ IXPathNavigable และส่งผลลัพธ์ไปยัง TextWriter. [XsltArgumentList](../xsltargumentlist/) ให้พารามิเตอร์เพิ่มเติมในระหว่างทำงาน. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจกต์ IXPathNavigable และส่งผลลัพธ์ไปยังสตรีม. [XsltArgumentList](../xsltargumentlist/) ให้พารามิเตอร์เพิ่มเติมในระหว่างทำงาน. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจกต์ [XmlReader](../../system.xml/xmlreader/) และส่งผลลัพธ์ไปยัง [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจกต์ [XmlReader](../../system.xml/xmlreader/) และส่งผลลัพธ์ไปยัง [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) ให้พารามิเตอร์เพิ่มเติมในระหว่างทำงาน. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจกต์ [XmlReader](../../system.xml/xmlreader/) และส่งผลลัพธ์ไปยัง TextWriter. [XsltArgumentList](../xsltargumentlist/) ให้พารามิเตอร์เพิ่มเติมในระหว่างทำงาน. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจกต์ [XmlReader](../../system.xml/xmlreader/) และส่งผลลัพธ์ไปยังสตรีม. [XsltArgumentList](../xsltargumentlist/) ให้พารามิเตอร์เพิ่มเติมในระหว่างทำงาน. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุด้วย URI และส่งผลลัพธ์ไปยัง [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุด้วย URI และส่งผลลัพธ์ไปยัง [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) ให้พารามิเตอร์เพิ่มเติมในระหว่างทำงาน. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุด้วย URI และส่งผลลัพธ์ไปยัง TextWriter. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุด้วย URI และส่งผลลัพธ์ไปยังสตรีม. [XsltArgumentList](../xsltargumentlist/) ให้พารามิเตอร์เพิ่มเติมในระหว่างทำงาน. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุด้วย URI และส่งผลลัพธ์ไปยังไฟล์. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจกต์ [XmlReader](../../system.xml/xmlreader/) และส่งผลลัพธ์ไปยัง [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) ให้พารามิเตอร์เพิ่มเติมในระหว่างทำงานและ [XmlResolver](../../system.xml/xmlresolver/) แก้ไขฟังก์ชัน XSLT **document()**. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ IXPathNavigable และส่งผลลัพธ์ไปยัง [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) ให้พารามิเตอร์เพิ่มเติมในระหว่างทำงานและ [XmlResolver](../../system.xml/xmlresolver/) แก้ไขฟังก์ชัน XSLT **document()**. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานคล้าย typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานคล้ายการปลดล็อกของคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
|  [XslCompiledTransform](./xslcompiledtransform/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XslCompiledTransform](./). |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## นิยามประเภท

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ

อ็อบเจกต์ของคลาสนี้ควรจัดสรรมาทางฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการละเมิดการอ้างอิง. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เป็นอาร์กิวเมนต์เมื่อส่งต่อให้ฟังก์ชัน.

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Xml::Xsl](../)
* ไลบรารี [Aspose.Slides](../../)