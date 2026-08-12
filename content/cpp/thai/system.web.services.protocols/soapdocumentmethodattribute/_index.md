---
title: SoapDocumentMethodAttribute
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "ระบุว่าข้อความ SOAP ทั้งหมดที่ส่งผ่านหรือส่งคืนจากเมธอดจะใช้รูปแบบ Document. ควรจัดสรรอ็อบเจ็กต์ของคลาสนี้เฉพาะด้วยฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยเตอร์ System::SmartPtr และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 53
url: /th/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute คลาส

ระบุว่าข้อความ SOAP ทั้งหมดที่ส่งผ่านหรือส่งคืนจากเมธอดใช้รูปแบบ Document. ออบเจ็กต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ห่อหุ้มคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยเตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น. |
| [String](../../system/string/) [get_Action](./get_action/)() | ดึงค่าของแอตทริบิวต์ 'SOAPAction'. |
| [String](../../system/string/) [get_Binding](./get_binding/)() | รับค่าการผูกที่เมธอดเว็บเซอร์วิส XML นี้กำลังดำเนินการ. |
| **bool** [get_OneWay](./get_oneway/)() | รับค่าที่ระบุว่าคลไอเอนท์ไม่รอให้เซิร์ฟเวอร์ทำการประมวลผลเมธอดจนเสร็จ. |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | รับค่าที่ระบุว่าพารามิเตอร์ถูกบรรจุไว้ในองค์ประกอบ XML เดียวภายใต้องค์ประกอบ 'Body'. |
| [String](../../system/string/) [get_RequestElementName](./get_requestelementname/)() | รับชื่อขององค์ประกอบ XML ที่เกี่ยวข้องกับคำขอ SOAP ซึ่งกำหนดในคำอธิบายบริการเป็นการดำเนินการ. |
| [String](../../system/string/) [get_RequestNamespace](./get_requestnamespace/)() | รับเนมสเปซที่เกี่ยวข้องกับคำขอ SOAP. |
| [String](../../system/string/) [get_ResponseElementName](./get_responseelementname/)() | รับชื่อขององค์ประกอบ XML ที่เกี่ยวข้องกับการตอบกลับ SOAP. |
| [String](../../system/string/) [get_ResponseNamespace](./get_responsenamespace/)() | รับเนมสเปซที่เกี่ยวข้องกับการตอบกลับ SOAP. |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | รับค่าที่กำหนดวิธีการเข้ารหัสข้อความ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | คืนค่าแอตทริบิวต์ที่กำหนดเองของประเภทที่ระบุที่ใช้กับประเภทที่ระบุ. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | คืนค่าแอตทริบิวต์ที่กำหนดเองทั้งหมดที่ใช้กับประเภทที่ระบุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถทำแฮชของอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์ เป็นคล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นคล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นคล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์และเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์สำเนา ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาของซับคลาสได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาของซับคลาสได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Action](./set_action/)([String](../../system/string/)) | ตั้งค่าของแอตทริบิวต์ 'SOAPAction'. |
| void [set_Binding](./set_binding/)([String](../../system/string/)) | ตั้งค่าการผูกที่เมธอดเว็บเซอร์วิส XML นี้กำลังดำเนินการ. |
| void [set_OneWay](./set_oneway/)(**bool**) | ตั้งค่าที่ระบุว่าคลไอเอนท์ไม่รอให้เซิร์ฟเวอร์ทำการประมวลผลเมธอดจนเสร็จ. |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | ตั้งค่าที่ระบุว่าพารามิเตอร์ถูกบรรจุในองค์ประกอบ XML เดียวภายใต้ 'Body'. |
| void [set_RequestElementName](./set_requestelementname/)([String](../../system/string/)) | ตั้งชื่อขององค์ประกอบ XML ที่เกี่ยวข้องกับคำขอ SOAP ซึ่งกำหนดในคำอธิบายบริการเป็นการดำเนินการ. |
| void [set_RequestNamespace](./set_requestnamespace/)([String](../../system/string/)) | ตั้งค่าเนมสเปซที่เกี่ยวข้องกับคำขอ SOAP. |
| void [set_ResponseElementName](./set_responseelementname/)([String](../../system/string/)) | ตั้งชื่อขององค์ประกอบ XML ที่เกี่ยวข้องกับการตอบกลับ SOAP. |
| void [set_ResponseNamespace](./set_responsenamespace/)([String](../../system/string/)) | ตั้งค่าเนมสเปซที่เกี่ยวข้องกับการตอบกลับ SOAP. |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | ตั้งค่าที่กำหนดวิธีการเข้ารหัสข้อความ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared) ให้สามารถเปลี่ยนพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | สร้างอินสแตนซ์ใหม่. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นคล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์และลบโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Attribute](../../system/attribute/)
* เนมสเปซ [System::Web::Services::Protocols](../)
* ไลบรารี [Aspose.Slides](../../)