---
title: XmlWriterSettings
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ระบุชุดของคุณลักษณะที่สนับสนุนบนวัตถุ XmlWriter ที่สร้างโดยเมธอด XmlWriter::Create."
type: docs
weight: 586
url: /th/system.xml/xmlwritersettings/
---
## XmlWriterSettings คลาส


ระบุชุดของคุณลักษณะที่สนับสนุนบนวัตถุ [XmlWriter](../xmlwriter/) ที่สร้างโดยเมธอด [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | สร้างสำเนาของอินสแตนซ์ [XmlWriterSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้สัญลักษณ์ [Object.Equals](../../system/object/equals/) ของ C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | คืนค่าแบบบูลีนที่บ่งชี้ว่า writer XML ควรตรวจสอบเพื่อให้แน่ใจว่าตัวอักษรทั้งหมดในเอกสารสอดคล้องกับส่วน "2.2 Characters" ของ W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | คืนค่าแบบบูลีนที่บ่งชี้ว่า [XmlWriter](../xmlwriter/) ควรปิดสตรีมหรือ TextWriter ที่อยู่พื้นฐานด้วยเมื่อเมธอด [XmlWriter::Close](../xmlwriter/close/) ถูกเรียก. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | คืนระดับของการปฏิบัติตามที่ writer XML ตรวจสอบผลลัพธ์ XML. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | คืนค่าแบบบูลีนที่บ่งชี้ว่า [XmlWriter](../xmlwriter/) ไม่ทำการ escape แอตทริบิวต์ URI. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | คืนประเภทของการเข้ารหัสข้อความที่ใช้. |
| **bool** [get_Indent](./get_indent/)() | คืนค่าแบบบูลีนที่บ่งชี้ว่าควรเยื้ององค์ประกอบหรือไม่. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | คืนสตริงอักขระที่ใช้สำหรับเยื้อง การตั้งค่านี้ใช้เมื่อค่าของ [XmlWriterSettings::set_Indent](./set_indent/) ถูกตั้งเป็น **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | คืนค่าแบบบูลีนที่บ่งชี้ว่า [XmlWriter](../xmlwriter/) ควรลบการประกาศเนมสเปซที่ซ้ำกันเมื่อเขียนเนื้อหา XML หรือไม่ พฤติกรรมเริ่มต้นคือ writer จะส่งออกการประกาศเนมสเปซทั้งหมดที่มีอยู่ใน namespace resolver ของ writer. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | คืนสตริงอักขระที่ใช้สำหรับการขึ้นบรรทัดใหม่. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | คืนค่าแบบบูลีนที่บ่งชี้ว่าควรทำให้การขึ้นบรรทัดใหม่เป็นรูปแบบมาตรฐานในผลลัพธ์หรือไม่. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | คืนค่าแบบบูลีนที่บ่งชี้ว่าควรเขียนแอตทริบิวต์ในบรรทัดใหม่หรือไม่. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | คืนค่าแบบบูลีนที่บ่งชี้ว่าจะละทิ้งการประกาศ XML หรือไม่. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | คืนเมธอดที่ใช้ในการจัดเรียงผลลัพธ์ [XmlWriter](../xmlwriter/). |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | คืนค่าแบบบูลีนที่บ่งชี้ว่า [XmlWriter](../xmlwriter/) จะเพิ่มแท็กปิดให้กับทุกแท็กองค์ประกอบที่ยังไม่ปิดเมื่อเมธอด [XmlWriter::Close](../xmlwriter/close/) ถูกเรียก. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอเนกประสงค์ของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนชนิดที่กำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงระหว่างอ็อบเจ็กต์ประเภทค่าและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉือนของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉือนของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายค่า. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับการอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| void [Reset](./reset/)() | รีเซ็ตสมาชิกของคลาสการตั้งค่าให้เป็นค่าเริ่มต้น. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | ตั้งค่าที่บ่งชี้ว่า writer XML ควรตรวจสอบเพื่อให้แน่ใจว่าตัวอักษรทั้งหมดในเอกสารสอดคล้องกับส่วน "2.2 Characters" ของ W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | ตั้งค่าที่บ่งชี้ว่า [XmlWriter](../xmlwriter/) ควรปิดสตรีมหรือ TextWriter พื้นฐานด้วยเมื่อเมธอด [XmlWriter::Close](../xmlwriter/close/) ถูกเรียก. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | ตั้งค่าระดับของการปฏิบัติตามที่ writer XML ตรวจสอบผลลัพธ์ XML. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | ตั้งค่าที่บ่งชี้ว่า [XmlWriter](../xmlwriter/) ไม่ทำการ escape แอตทริบิวต์ URI. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | ตั้งค่าประเภทของการเข้ารหัสข้อความที่ใช้. |
| void [set_Indent](./set_indent/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าควรเยื้ององค์ประกอบหรือไม่. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | ตั้งค่าสตริงอักขระที่ใช้สำหรับเยื้อง การตั้งค่านี้ใช้เมื่อค่าของ [XmlWriterSettings::set_Indent](./set_indent/) ถูกตั้งเป็น **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | ตั้งค่าที่บ่งชี้ว่า [XmlWriter](../xmlwriter/) ควรลบการประกาศเนมสเปซที่ซ้ำกันเมื่อเขียนเนื้อหา XML หรือไม่ พฤติกรรมเริ่มต้นคือ writer จะส่งออกการประกาศเนมสเปซทั้งหมดที่มีอยู่ใน namespace resolver ของ writer. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | ตั้งค่าสตริงอักขระที่ใช้สำหรับการขึ้นบรรทัดใหม่. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | ตั้งค่าที่บ่งชี้ว่าควรทำให้การขึ้นบรรทัดใหม่เป็นรูปแบบมาตรฐานในผลลัพธ์หรือไม่. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าควรเขียนแอตทริบิวต์ในบรรทัดใหม่หรือไม่. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าจะละทิ้งการประกาศ XML หรือไม่. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | ตั้งค่าที่บ่งชี้ว่า [XmlWriter](../xmlwriter/) จะเพิ่มแท็กปิดให้กับทุกแท็กองค์ประกอบที่ยังไม่ปิดเมื่อเมธอด [XmlWriter::Close](../xmlwriter/close/) ถูกเรียก. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n เป็น weak pointer (แทนที่ shared) ซึ่งอนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| [XmlWriterSettings](./xmlwritersettings/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlWriterSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ชนิดนิยาม

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | เป็นนามแฝงของพอยเตอร์ที่แชร์ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ

วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยเตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้ฟังก์ชัน.

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)