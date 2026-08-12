---
title: ServicePoint
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ให้การจัดการการเชื่อมต่อ HTTP. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือข้อผิดพลาดการยืนยัน. ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้ส่งต่อให้ฟังก์ชันเป็นอาร์กิวเมนต์."
type: docs
weight: 417
url: /th/system.net/servicepoint/
---
## ServicePoint คลาส


ให้การจัดการการเชื่อมต่อ HTTP. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือข้อผิดพลาดการยืนยัน. ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) เสมอและใช้ตัวชี้นี้ส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class ServicePoint : public System::Object
```

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | ปิดและลบการเชื่อมต่อที่เป็นส่วนหนึ่งของกลุ่มการเชื่อมต่อที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตามสไตล์ของ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตามสไตล์ของ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | คืนค่า URI ของเซิร์ฟเวอร์ที่อินสแตนซ์ปัจจุบันเชื่อมต่อ. |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | รับตัวแทนที่ใช้เชื่อมโยง [IPEndPoint](../ipendpoint/) ท้องถิ่นกับอินสแตนซ์ปัจจุบัน. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | คืนใบรับรองที่อินสแตนซ์ปัจจุบันใช้. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | คืนใบรับรองลูกค้ารายล่าสุด. |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | รับค่า timeout เป็นมิลลิวินาทีหลังจากนั้น [ServicePoint](./) ที่กำลังทำงานจะถูกปิด. |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | รับจำนวนการเชื่อมต่อสูงสุดที่อินสแตนซ์ปัจจุบันอนุญาต. |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | คืนชื่อการเชื่อมต่อ. |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | คืนจำนวนการเชื่อมต่อที่เปิดอยู่. |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | รับค่าสถานะที่บ่งบอกว่ามีการใช้พฤติกรรม 100-Continue. |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | คืนวันที่และเวลาของการเชื่อมต่อล่าสุดกับโฮสต์. |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | รับระยะเวลาเป็นมิลลิวินาทีหลังจากนั้นการเชื่อมต่อที่ไม่ได้ใช้งานจะถูกปิด. |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | คืนค่าเวอร์ชัน HTTP. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | รับขนาดของบัฟเฟอร์รับข้อมูล. |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | คืนค่าสถานะที่บ่งบอกว่าอินสแตนซ์ปัจจุบันรองรับการเชื่อมต่อแบบ pipeline. |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | รับค่าสถานะที่บ่งบอกว่าอัลกอริทึม Nagle ถูกใช้โดยการเชื่อมต่อที่จัดการโดยอินสแตนซ์ปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการทำงานคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นการทำงานคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการทำงานคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทกำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกค่าใด ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมาย. จริง ๆ แล้วไม่ได้คัดลอกค่าใด ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การปรับใช้พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การปรับใช้พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | ตั้งค่าตัวแทนที่ใช้เชื่อมโยง [IPEndPoint](../ipendpoint/) ท้องถิ่นกับอินสแตนซ์ปัจจุบัน. |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | ตั้งค่า timeout เป็นมิลลิวินาทีหลังจากนั้น [ServicePoint](./) ที่กำลังทำงานจะถูกปิด. |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | ตั้งค่าจำนวนการเชื่อมต่อสูงสุดที่อินสแตนซ์ปัจจุบันอนุญาต. |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | ตั้งค่าค่าสถานะที่บ่งบอกว่ามีการใช้พฤติกรรม 100-Continue. |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | ตั้งค่าระยะเวลาเป็นมิลลิวินาทีหลังจากนั้นการเชื่อมต่อที่ไม่ได้ใช้งานจะถูกปิด. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | ตั้งค่าขนาดของบัฟเฟอร์รับข้อมูล. |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | ตั้งค่าค่าสถานะที่บ่งบอกว่าอัลกอริทึม Nagle ถูกใช้โดยการเชื่อมต่อที่จัดการโดยอินสแตนซ์ปัจจุบัน. |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | ตั้งค่าค่าสถานะที่บ่งบอกว่าเปิดใช้งานตัวเลือก 'Keep-Alive' หรือไม่. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น pointer ชี้แบบ weak (แทน shared). อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นการทำงานคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่คล้ายการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Net](../)
* ไลบรารี [Aspose.Slides](../../)