---
title: Socket
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คลาส Socket ทำงานตามอินเทอร์เฟซ Berkeley sockets
type: docs
weight: 53
url: /th/system.net.sockets/socket/
---
## Socket คลาส

The [Socket](./) class implements the Berkeley sockets interface.

```cpp
class Socket : public System::IDisposable
```

## วิธีการ

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](./)\> [Accept](./accept/)() | สร้างซ็อกเก็ตใหม่สำหรับการเชื่อมต่อที่เพิ่งสร้างขึ้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เริ่มการดำเนินการเชื่อมต่อแบบอะซิงโครนัส. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginReceive](./beginreceive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เริ่มการดำเนินการเขียนแบบอะซิงโครนัส. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginSend](./beginsend/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เริ่มการดำเนินการส่งแบบอะซิงโครนัส. |
| void [Bind](./bind/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ผูกซ็อกเก็ตกับจุดปลายท้องถิ่นที่ระบุ. |
| void [Close](./close/)() | ปิดการเชื่อมต่อซ็อกเก็ต. |
| void [Close](./close/)(int) | ปิดการเชื่อมต่อซ็อกเก็ตพร้อมด้วยเวลาจำกัดที่ระบุเพื่อให้อบข้อมูลคิวถูกส่งออกไป. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | สร้างการเชื่อมต่อไปยังจุดปลายระยะไกลที่ระบุ. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | สร้างการเชื่อมต่อไปยังจุดปลายระยะไกลที่ระบุ. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | สร้างการเชื่อมต่อไปยังจุดปลายระยะไกลที่ระบุ. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | สร้างการเชื่อมต่อไปยังจุดปลายระยะไกลที่ระบุ. |
| void [Dispose](./dispose/)() override | ไม่มีการทำอะไร. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | รอจนกว่าการดำเนินการเชื่อมต่อแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | รอจนกว่าการดำเนินการรับแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์. |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | รอจนกว่าการดำเนินการรับแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | รอจนกว่าการดำเนินการส่งแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์. |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | รอจนกว่าการดำเนินการส่งแบบอะซิงโครนัสที่ระบุจะเสร็จสมบูรณ์. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้รูปแบบของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองตัวถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองตัวถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [System::Net::Sockets::AddressFamily](../addressfamily/) [get_AddressFamily](./get_addressfamily/)() | คืนค่าสร้างที่อยู่. |
| **int32_t** [get_Available](./get_available/)() | รับจำนวนไบต์ที่ได้รับจากเครือข่ายและพร้อมสำหรับการอ่าน. |
| **bool** [get_Blocking](./get_blocking/)() | รับค่าที่บ่งบอกว่าซ็อกเก็ตอยู่ในโหมดบล็อกหรือไม่. |
| **bool** [get_Connected](./get_connected/)() | คืนค่าที่บ่งบอกว่าซ็อกเก็ตเชื่อมต่อกับโฮสต์ระยะไกลหรือไม่. |
| **bool** [get_DontFragment](./get_dontfragment/)() | รับค่าที่บ่งบอกว่าซ็อกเก็ตอนุญาตให้แพ็กเก็ต IP แบ่งส่วนได้หรือไม่. |
| **bool** [get_DualMode](./get_dualmode/)() | รับค่าที่บ่งบอกว่าซ็อกเก็ตอยู่ในโหมดคู่หรือไม่. |
| **bool** [get_EnableBroadcast](./get_enablebroadcast/)() | รับค่าที่บ่งบอกว่าซ็อกเก็ตอนุญาตให้แพ็กเก็ตบรอดแคสต์หรือไม่. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | รับค่าที่บ่งบอกว่ามีเพียงกระบวนการเดียวเท่านั้นที่สามารถผูกซ็อกเก็ตกับพอร์ตได้หรือไม่. |
| **bool** [get_IsBound](./get_isbound/)() | คืนค่าที่บ่งบอกว่าซ็อกเก็ตผูกกับพอร์ตท้องถิ่นเฉพาะหรือไม่. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | รับค่าที่บ่งบอกว่าซ็อกเก็ตจะหน่วงการปิดเพื่อลองส่งข้อมูลที่ค้างอยู่ทั้งหมดหรือไม่. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndPoint](./get_localendpoint/)() | คืนจุดปลายท้องถิ่น. |
| **bool** [get_MulticastLoopback](./get_multicastloopback/)() | รับค่าที่บ่งบอกว่าซ็อกเก็ตรับแพ็กเก็ตมัลติคาสต์ขาออกหรือไม่. |
| **bool** [get_NoDelay](./get_nodelay/)() | รับค่าที่บ่งบอกว่าซ็อกเก็ตใช้ 알고리즘 Nagle หรือไม่. |
| static **bool** [get_OSSupportsIPv4](./get_ossupportsipv4/)() | คืนค่าที่บ่งบอกว่าระบบปฏิบัติการและอะแดปเตอร์เครือข่ายรองรับ IPv4 หรือไม่. |
| static **bool** [get_OSSupportsIPv6](./get_ossupportsipv6/)() | คืนค่าที่บ่งบอกว่าระบบปฏิบัติการและอะแดปเตอร์เครือข่ายรองรับ IPv6 หรือไม่. |
| [System::Net::Sockets::ProtocolType](../protocoltype/) [get_ProtocolType](./get_protocoltype/)() | คืนประเภทโปรโตคอล. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | รับขนาดบัฟเฟอร์รับ. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | รับช่วงเวลาซึ่งการเรียก 'Receive' จะหมดเวลา. |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_RemoteEndPoint](./get_remoteendpoint/)() | คืนจุดปลายระยะไกล. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | รับขนาดบัฟเฟอร์ส่ง. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | รับช่วงเวลาซึ่งการเรียก 'Send' จะหมดเวลา. |
| [System::Net::Sockets::SocketType](../sockettype/) [get_SocketType](./get_sockettype/)() | คืนประเภทซ็อกเก็ต. |
| static **bool** [get_SupportsIPv4](./get_supportsipv4/)() | คืนค่าที่บ่งบอกว่าโฮสต์ปัจจุบันรองรับ IPv4 หรือไม่. |
| **int16_t** [get_Ttl](./get_ttl/)() | รับค่า TTL. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อันตรักษาเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้การแฮชวัตถุที่กำหนดเอง. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | คืนตัวชี้ไปยังการดำเนินการ. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/)) | คืนค่าที่สอดคล้องกับชื่อออพชั่นที่ระบุ. |
| void [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับค่าที่สอดคล้องกับชื่อออพชั่นที่ระบุ. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | คืนค่าที่สอดคล้องกับชื่อออพชั่นที่ระบุ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. อันตรักษาการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| **int32_t** [IOControl](./iocontrol/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ตั้งโหมดการทำงานระดับต่ำสำหรับซ็อกเก็ต. |
| **int32_t** [IOControl](./iocontrol/)([IOControlCode](../iocontrolcode/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ตั้งโหมดการทำงานระดับต่ำสำหรับซ็อกเก็ต. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. อันตรักษาออปเตอเรเตอร์ 'is' ของ C#. |
| void [Listen](./listen/)(**int32_t**) | เปลี่ยนสถานะซ็อกเก็ตเป็น 'listen'. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อันตรรักษาเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นวัตถุใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ออปเรเตอร์การกำหนดค่า. ไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นวัตถุใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| **bool** [Poll](./poll/)(**int32_t**, [SelectMode](../selectmode/)) | คืนสถานะของซ็อกเก็ตตามโหมดการโพลที่ระบุ. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์หลายชุด. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์หลายชุด. |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | รับข้อมูลจากซ็อกเก็ตและเขียนลงในอาร์เรย์ไบต์หลายชุด. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากจุดปลายที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากจุดปลายที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากจุดปลายที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากจุดปลายที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากจุดปลายที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ. |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากปลายทางที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากปลายทางที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากปลายทางที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากปลายทางที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากปลายทางที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากปลายทางที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | รับข้อมูลจากปลายทางที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | รับข้อมูลจากปลายทางที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | รับข้อมูลจากปลายทางที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | รับข้อมูลจากปลายทางที่ระบุและเขียนลงในอาร์เรย์ไบต์ที่ระบุ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมตามค่าที่ระบุ |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | ส่งข้อมูลที่ระบุไปยังซ็อกเก็ต |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | ส่งข้อมูลที่ระบุไปยังปลายทางที่ระบุ |
| void [set_Blocking](./set_blocking/)(**bool**) | กำหนดค่าที่ระบุว่าซ็อกเก็ตอยู่ในโหมดบล็อกหรือไม่ |
| void [set_ConnectionTimeout](./set_connectiontimeout/)(**int32_t**) | กำหนดค่า timeout ของการเชื่อมต่อ |
| void [set_DontFragment](./set_dontfragment/)(**bool**) | กำหนดค่าที่ระบุว่าซ็อกเก็ตอนุญาตให้แพ็คเกจ IP ถูกแบ่งส่วนหรือไม่ |
| void [set_DualMode](./set_dualmode/)(**bool**) | กำหนดค่าที่ระบุว่าซ็อกเก็ตอยู่ในโหมด dual หรือไม่ |
| void [set_EnableBroadcast](./set_enablebroadcast/)(**bool**) | กำหนดค่าที่ระบุว่าซ็อกเก็ตอนุญาตให้แพ็คเกจ broadcast หรือไม่ |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | กำหนดค่าที่ระบุว่ามีเพียงกระบวนการเดียวที่สามารถผูกซ็อกเก็ตกับพอร์ตได้หรือไม่ |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | กำหนดค่าที่ระบุว่าซ็อกเก็ตจะหน่วงเวลาปิดเพื่อพยามส่งข้อมูลที่ค้างอยู่ทั้งหมดหรือไม่ |
| void [set_MulticastLoopback](./set_multicastloopback/)(**bool**) | กำหนดค่าที่ระบุว่าซ็อกเก็ตรับแพ็คเกจมัลติคาสท์ที่ส่งออกหรือไม่ |
| void [set_NoDelay](./set_nodelay/)(**bool**) | กำหนดค่าที่ระบุว่าซ็อกเก็ตใช้ алгоритм Nagle หรือไม่ |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | กำหนดขนาดบัฟเฟอร์รับ |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | กำหนดช่วงเวลาที่การเรียก 'Receive' จะหมดเวลา |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | กำหนดขนาดบัฟเฟอร์ส่ง |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | กำหนดช่วงเวลาที่การเรียก 'Send' จะหมดเวลา |
| void [set_Ttl](./set_ttl/)(**int16_t**) | กำหนดค่า TTL |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | กำหนดตัวเลือกซ็อกเก็ตที่ระบุให้เป็นค่าที่ระบุ |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | กำหนดตัวเลือกซ็อกเก็ตที่ระบุให้เป็นค่าที่ระบุ |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **bool**) | กำหนดตัวเลือกซ็อกเก็ตที่ระบุให้เป็นค่าที่ระบุ |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | กำหนดตัวเลือกซ็อกเก็ตที่ระบุให้เป็นค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) ให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [Shutdown](./shutdown/)([SocketShutdown](../socketshutdown/)) | ปิดการทำงานส่งและรับของซ็อกเก็ต |
|  [Socket](./socket/)([System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | สร้างอินสแตนซ์ใหม่ |
|  [Socket](./socket/)([System::Net::Sockets::AddressFamily](../addressfamily/), [System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | สร้างอินสแตนซ์ใหม่ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นการทำงานที่คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจกต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | จำลองโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | จำลองการปลดล็อกของ C# lock() เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
| virtual  [~Socket](./~socket/)() | ทำลายอินสแตนซ์ปัจจุบัน |
## ชนิดอ้างอิง

| ชนิดอ้างอิง | คำอธิบาย |
| --- | --- |
| [ImplPtr](./implptr/) | การดำเนินการของซ็อกเก็ต |
## ดูเพิ่มเติม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::Net::Sockets](../)
* ไลบรารี [Aspose.Slides](../../)