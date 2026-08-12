---
title: IPAddress
second_title: "เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++"
description: "แทนที่อยู่ IP. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เพราะจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการตรวจสอบล้มเหลว. ควรห่อหุ้คลาสนี้ด้วยพอยเตอร์ System::SmartPtr เสมอและใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 326
url: /th/system.net/ipaddress/
---
## IPAddress คลาส

แทนที่อยู่ IP. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการตรวจสอบล้มเหลว. ควรห่อหุ้มหรือครอบคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class IPAddress : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าตัวเลขลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าตัวเลขลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | ส่งคืน family ของที่อยู่ |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | ส่งคืนค่าที่บ่งชี้ว่าที่อยู่เป็น IPv4 และถูกแม็ปเป็น IPv6 |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | ส่งคืนค่าที่บ่งชี้ว่าที่อยู่เป็น IPv6 link-local |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | ส่งคืนค่าที่บ่งชี้ว่าที่อยู่เป็น IPv6 multicast ระดับ global |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | ส่งคืนค่าที่บ่งชี้ว่าที่อยู่เป็น IPv6 site-local |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | ส่งคืนค่าที่บ่งชี้ว่าที่อยู่เป็น IPv6 Teredo |
| **int64_t** [get_ScopeId](./get_scopeid/)() | รับตัวระบุสโคปของที่อยู่ IPv6 |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | ส่งคืนอาร์เรย์บ이트ของที่อยู่ IP |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| **int32_t** [GetHashCode](./gethashcode/)() const override | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | ส่งคืนพอยเตอร์ไปยังการนำไปใช้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | แปลงลำดับไบต์ของโฮสต์ที่ระบุเป็นลำดับไบต์ของเครือข่ายที่สอดคล้องกัน |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | แปลงลำดับไบต์ของโฮสต์ที่ระบุเป็นลำดับไบต์ของเครือข่ายที่สอดคล้องกัน |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | แปลงลำดับไบต์ของโฮสต์ที่ระบุเป็นลำดับไบต์ของเครือข่ายที่สอดคล้องกัน |
|  [IPAddress](./ipaddress/)(**int64_t**) | สร้างอินสแตนซ์ใหม่ |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | สร้างอินสแตนซ์ใหม่ |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | สร้างอินสแตนซ์ใหม่ |
|  [IPAddress](./ipaddress/)() | สร้างอินสแตนซ์ใหม่ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นอเนกประสงค์ของตัวดำเนินการ C# 'is' |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | ส่งคืนค่าที่บ่งชี้ว่าที่อยู่ที่ระบุเป็น loopback address |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | แม็ปที่อยู่เป็นที่อยู่ IPv4 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | แม็ปที่อยู่เป็นที่อยู่ IPv6 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | แปลงลำดับไบต์ของเครือข่ายที่ระบุเป็นลำดับไบต์ของโฮสต์ที่สอดคล้องกัน |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | แปลงลำดับไบต์ของเครือข่ายที่ระบุเป็นลำดับไบต์ของโฮสต์ที่สอดคล้องกัน |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | แปลงลำดับไบต์ของเครือข่ายที่ระบุเป็นลำดับไบต์ของโฮสต์ที่สอดคล้องกัน |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การสร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การสร้างสำเนาสำหรับคลาสย่อย |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | แปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [IPAddress](./) |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | ตั้งตัวระบุสโคปของที่อยู่ IPv6 |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | ตั้งพอยเตอร์ไปยังการนำไปใช้ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลต argument ที่ n เป็นพอยเตอร์แบบอ่อน (weak) (แทนที่จะเป็น shared). อนุญาตให้เปลี่ยนพอยเตอร์ในคอนเทนเนอร์เป็นโหมดอ่อน |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้สมาร์ตพอยเตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ใช้สมาร์ตพอยเตอร์หรือ ThisProtector แทน |
| [String](../../system/string/) [ToString](./tostring/)() const override | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [IPAddress](./) |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ใช้สมาร์ตพอยเตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ใช้สมาร์ตพอยเตอร์หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ฟิลด์

| Field | Description |
| --- | --- |
| static [Any](./any/) | ที่อยู่ IPv4 ที่ระบุว่าตัวเซิร์ฟเวอร์ต้องฟังบนอินเทอร์เฟซเครือข่ายทั้งหมด |
| static [Broadcast](./broadcast/) | ที่อยู่ IPv4 broadcast |
| static [IPv6Any](./ipv6any/) | ที่อยู่ IPv6 ที่ระบุว่าตัวเซิร์ฟเวอร์ต้องฟังบนอินเทอร์เฟซเครือข่ายทั้งหมด |
| static [IPv6Loopback](./ipv6loopback/) | ที่อยู่ IPv6 loopback |
| static [IPv6None](./ipv6none/) | ที่อยู่ IPv6 ที่ระบุว่าตัวเซิร์ฟเวอร์ไม่ควรฟังบนอินเทอร์เฟซเครือข่ายใดเลย |
| static [Loopback](./loopback/) | ที่อยู่ IPv4 loopback |
| static [None](./none/) | ที่อยู่ IPv4 ที่ระบุว่าตัวเซิร์ฟเวอร์ไม่ควรฟังบนอินเทอร์เฟซเครือข่ายใดเลย |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | พอยเตอร์ไปยังประเภทการนำไปใช้ |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Net](../)
* ไลบรารี [Aspose.Slides](../../)