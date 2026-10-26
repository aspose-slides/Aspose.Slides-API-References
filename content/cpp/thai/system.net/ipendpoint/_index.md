---
title: IPEndPoint
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แทนที่จุดสิ้นสุดของเครือข่ายซึ่งประกอบด้วยที่อยู่ IP และพอร์ต อ็อบเจ็กต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด ควรห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้ดังกล่าวเพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 339
url: /th/system.net/ipendpoint/
---
## IPEndPoint คลาส


แทนที่จุดสิ้นสุดของเครือข่ายซึ่งประกอบด้วยที่อยู่ IP และพอร์ต วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดในระหว่างการทำงานและ/หรือการละเมิดการตรวจสอบเสมอ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class IPEndPoint : public System::Net::EndPoint
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../endpoint/)\> [Create](./create/)([System::SharedPtr](../../system/sharedptr/)\<[SocketAddress](../socketaddress/)\>) override | สร้างอินสแตนซ์ใหม่ของคลาส [EndPoint](../endpoint/) โดยใช้ที่อยู่ซ็อกเก็ตที่ระบุ |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิด [Object.Equals](../../system/object/equals/) ของ C# |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิด [Object.Equals](../../system/object/equals/) ของ C# |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่พิจารณา NaN สองค่าเท่าเทียมกันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่พิจารณา NaN สองค่าเท่าเทียมกันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\> [get_Address](./get_address/)() | รับที่อยู่ของจุดสิ้นสุด |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() override | คืนค่าครอบครัวที่อยู่ (address family) ที่อินสแตนซ์ปัจจุบันเป็นส่วนหนึ่ง |
| **int32_t** [get_Port](./get_port/)() | รับหมายเลขพอร์ต |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| **int32_t** [GetHashCode](./gethashcode/)() const override | คล้ายกับเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C# ซึ่งทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| [ImplPtr](../endpoint/implptr/) [GetImpl](./getimpl/)() const override | ส่งคืนตัวชี้ไปยังการทำงานภายใน |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์ ซึ่งคล้ายกับการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
|  [IPEndPoint](./ipendpoint/)(**int64_t**, **int32_t**) | สร้างอินสแตนซ์ใหม่ |
|  [IPEndPoint](./ipendpoint/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>, **int32_t**) | สร้างอินสแตนซ์ใหม่ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ ซึ่งคล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# ซึ่งทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์และเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก ซึ่งไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และอนุญาตให้คัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ซึ่งไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และอนุญาตให้คัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ |
| void [set_Address](./set_address/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>) | ตั้งค่าที่อยู่ของจุดสิ้นสุด |
| void [set_Port](./set_port/)(**int32_t**) | ตั้งค่าหมายเลขพอร์ต |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็นตัวชี้อ่อน (weak pointer) แทน shared pointer ซึ่งทำให้สามารถสลับตัวชี้ในคอนเทนเนอร์เป็นโหมดอ่อนได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและส่งคืนตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน |
| [String](../../system/string/) [ToString](./tostring/)() const override | คล้ายกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# ซึ่งทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงอ่อน ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงอ่อน ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์และปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Any](./any/) | จุดสิ้นสุดสำหรับที่อยู่ IPv4 ใด ๆ และพอร์ตใด ๆ |
| static [AnyPort](./anyport/) | ค่าที่บ่งบอกว่าพอร์ตใดก็ได้สามารถใช้ได้ |
| static [IPv6Any](./ipv6any/) | จุดสิ้นสุดสำหรับที่อยู่ IPv6 ใด ๆ และพอร์ตใด ๆ |
| static [MaxPort](./maxport/) | หมายเลขพอร์ตสูงสุด |
| static [MinPort](./minport/) | หมายเลขพอร์ตต่ำสุด |

## ดูเพิ่มเติม

* คลาส [EndPoint](../endpoint/)
* เนมสเปซ [System::Net](../)
* ไลบรารี [Aspose.Slides](../../)