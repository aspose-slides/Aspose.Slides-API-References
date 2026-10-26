---
title: TcpClient
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงถึงไคลเอนต์สำหรับบริการเครือข่าย TCP. ควรสร้างอ็อบเจ็กต์ของคลาสนี้โดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการขัดจังหวะ assertion. ควรห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 66
url: /th/system.net.sockets/tcpclient/
---
## TcpClient คลาส

แสดงถึงไคลเอนต์สำหรับบริการเครือข่าย TCP. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TcpClient : public System::IDisposable
```

## เมธอด

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส |
| void [Close](./close/)() | ปิดการเชื่อมต่อและทำลายอินสแตนซ์ปัจจุบัน |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | สร้างการเชื่อมต่อไปยังโฮสต์ระยะไกลที่ระบุ |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | สร้างการเชื่อมต่อไปยังโฮสต์ระยะไกลที่ระบุ |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | สร้างการเชื่อมต่อไปยังโฮสต์ระยะไกลที่ระบุ |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | สร้างการเชื่อมต่อไปยังโฮสต์ระยะไกลที่ระบุ |
| virtual void [Dispose](../../system/idisposable/dispose/)() | ไม่ทำอะไร |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | รอจนกว่าการเชื่อมต่อแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าถือเท่าเทียมกันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าถือเท่าเทียมกันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น |
| **int32_t** [get_Available](./get_available/)() | คืนจำนวนไบต์ที่ได้รับและพร้อมอ่าน |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | รับค่า socket |
| **bool** [get_Connected](./get_connected/)() | คืนค่าที่บ่งบอกว่า socket เชื่อมต่อกับโฮสต์ระยะไกลหรือไม่ |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | รับค่าที่บ่งบอกว่าอินสแตนซ์ปัจจุบันอนุญาตให้ไคลเอนต์เพียงหนึ่งเดียวใช้พอร์ตหรือไม่ |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | รับค่าที่บ่งบอกว่า socket จะหน่วงเวลาการปิดเพื่อพยายามส่งข้อมูลที่ค้างทั้งหมดหรือไม่ |
| **bool** [get_NoDelay](./get_nodelay/)() | รับค่าที่บ่งบอกว่าอินสแตนซ์ปัจจุบันกำลังใช้ الگอริทึม Nagle หรือไม่ |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | รับขนาดของบัฟเฟอร์ที่ใช้สำหรับรับข้อมูล |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | รับค่าที่บ่งบอกระยะเวลาที่หลังจากนั้นการรับข้อมูลจะหมดเวลา |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | รับขนาดของบัฟเฟอร์ที่ใช้สำหรับส่งข้อมูล |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | รับค่าที่บ่งบอกระยะเวลาที่หลังจากนั้นการส่งข้อมูลจะหมดเวลา |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์กำหนดเองได้ |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | คืนสตรีมที่ใช้สำหรับส่งและรับข้อมูล |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นอนาล็อกของคำเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นอนาล็อกของออปอเรเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning ประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | ตั้งค่า socket |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | ตั้งค่าที่บ่งบอกว่าอินสแตนซ์ปัจจุบันอนุญาตให้ไคลเอนต์เพียงหนึ่งเดียวใช้พอร์ตหรือไม่ |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | ตั้งค่าที่บ่งบอกว่า socket จะหน่วงเวลาการปิดเพื่อพยายามส่งข้อมูลที่ค้างทั้งหมดหรือไม่ |
| void [set_NoDelay](./set_nodelay/)(**bool**) | ตั้งค่าที่บ่งบอกว่าอินสแตนซ์ปัจจุบันกำลังใช้ الگอริทึม Nagle หรือไม่ |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | ตั้งค่าขนาดของบัฟเฟอร์ที่ใช้สำหรับรับข้อมูล |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | ตั้งค่าที่บ่งบอกระยะเวลาที่หลังจากนั้นการรับข้อมูลจะหมดเวลา |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | ตั้งค่าขนาดของบัฟเฟอร์ที่ใช้สำหรับส่งข้อมูล |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | ตั้งค่าที่บ่งบอกระยะเวลาที่หลังจากนั้นการส่งข้อมูลจะหมดเวลา |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared) ทำให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | สร้างอ็อบเจ็กต์ใหม่ |
|  [TcpClient](./tcpclient/)() | สร้างอ็อบเจ็กต์ใหม่ |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | สร้างอ็อบเจ็กต์ใหม่ |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | สร้างอ็อบเจ็กต์ใหม่ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
| virtual  [~TcpClient](./~tcpclient/)() | ทำลายอินสแตนซ์ปัจจุบัน |
## ดูเพิ่ม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::Net::Sockets](../)
* ไลบรารี [Aspose.Slides](../../)