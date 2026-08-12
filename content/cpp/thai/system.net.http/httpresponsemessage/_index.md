---
title: HttpResponseMessage
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "เป็นตัวแทนของข้อความตอบกลับ HTTP. วัตถุของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการขัดจังหวะการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 118
url: /th/system.net.http/httpresponsemessage/
---
## HttpResponseMessage คลาส

เป็นตัวแทนของข้อความตอบกลับ HTTP วัตถุของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการขัดจังหวะการตรวจสอบ ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class HttpResponseMessage : public System::IDisposable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Dispose](./dispose/)() override | ทำลายอินสแตนซ์ปัจจุบัน เมธอดนี้ยังทำลายเนื้อหาของการตอบกลับ HTTP ด้วย. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpResponseMessage](./)\> [EnsureSuccessStatusCode](./ensuresuccessstatuscode/)() | ตรวจสอบรหัสสถานะ หากรหัสสถานะไม่อยู่ในช่วง 2xx จะเกิดข้อยกเว้น HttpRequestException. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ตรรกะของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าบางค่าใดรวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าบางค่าใดรวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\> [get_Content](./get_content/)() const | ดึงเนื้อหาของการตอบกลับ HTTP. |
| [System::SharedPtr](../../system/sharedptr/)\<[Headers::HttpResponseHeaders](../../system.net.http.headers/httpresponseheaders/)\> [get_Headers](./get_headers/)() const | ส่งคืนส่วนหัวเนื้อหา HTTP. |
| **bool** [get_IsSuccessStatusCode](./get_issuccessstatuscode/)() const | ตรวจสอบว่ารหัสสถานะบ่งชี้ว่าการกระทำที่ไคลเอนต์ร้องขอได้รับการรับ, เข้าใจและยอมรับแล้วหรือไม่. |
| [String](../../system/string/) [get_ReasonPhrase](./get_reasonphrase/)() const | ดึง Reason-Phrase ที่เซิร์ฟเวอร์ส่งพร้อมกับรหัสสถานะ. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\> [get_RequestMessage](./get_requestmessage/)() const | ดึงข้อความคำร้องขอ HTTP. |
| [HttpStatusCode](../../system.net/httpstatuscode/) [get_StatusCode](./get_statuscode/)() const | ดึงรหัสสถานะ HTTP. |
| [System::Version](../../system/version/) [get_Version](./get_version/)() const | ดึงเวอร์ชัน HTTP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชออบเจกต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของออบเจกต์ เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpResponseMessage](./httpresponsemessage/)() | สร้างอินสแตนซ์ใหม่. |
|  [HttpResponseMessage](./httpresponsemessage/)([HttpStatusCode](../../system.net/httpstatuscode/)) | สร้างอินสแตนซ์ใหม่. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นอเนกประสงค์ของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างออบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Content](./set_content/)([System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\>) | กำหนดเนื้อหาของการตอบกลับ HTTP. |
| void [set_ReasonPhrase](./set_reasonphrase/)([String](../../system/string/)) | กำหนด Reason-Phrase ที่เซิร์ฟเวอร์ส่งพร้อมกับรหัสสถานะ. |
| void [set_RequestMessage](./set_requestmessage/)([System::SharedPtr](../../system/sharedptr/)\<[HttpRequestMessage](../httprequestmessage/)\>) | กำหนดข้อความคำร้องขอ HTTP. |
| void [set_StatusCode](./set_statuscode/)([HttpStatusCode](../../system.net/httpstatuscode/)) | กำหนดรหัสสถานะ HTTP. |
| void [set_Version](./set_version/)([System::Version](../../system/version/)) | กำหนดเวอร์ชัน HTTP. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็นพอยน์เตอร์แบบอ่อน (แทนการแชร์) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมดอ่อนได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งกลับค่าตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| [String](../../system/string/) [ToString](./tostring/)() const override | [System::Object::ToString](../../system/object/tostring/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่คล้ายกับ construct typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบอ่อน ไม่ควรเรียกโดยตรง ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบอ่อน ไม่ควรเรียกโดยตรง ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::Net::Http](../)
* ไลบรารี [Aspose.Slides](../../)