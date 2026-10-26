---
title: HttpRequestMessage
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "เป็นข้อความคำขอ HTTP. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยเตอร์ System::SmartPtr และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 105
url: /th/system.net.http/httprequestmessage/
---
## HttpRequestMessage คลาส


เป็นข้อความคำขอ HTTP. อ็อบเจ็กต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class HttpRequestMessage : public System::IDisposable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Dispose](./dispose/)() override | ทำลายอินสแตนซ์ปัจจุบัน เมธอดนี้ยังทำลายเนื้อหาของคำขอ HTTP ด้วย |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\> [get_Content](./get_content/)() | ดึงเนื้อหาของคำขอ HTTP |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Http::Headers::HttpRequestHeaders](../../system.net.http.headers/httprequestheaders/)\> [get_Headers](./get_headers/)() | คืนหัวข้อเนื้อหา HTTP |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\> [get_Method](./get_method/)() | ดึงเมธอดของคำขอ HTTP |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Properties](./get_properties/)() | คืนคอลเลกชันของคุณสมบัติคำขอ HTTP |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() | ดึง URI ของทรัพยากรที่ร้องขอ |
| [System::Version](../../system/version/) [get_Version](./get_version/)() | ดึงเวอร์ชัน HTTP |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลคอนเทอร์รีฟเฟอเรนซ์ที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอุปกรณ์คล้ายเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C# ทำให้สามารถทำแฮชอ็อบเจ็กต์แบบกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทที่แท้จริงของอ็อบเจ็กต์ เป็นอุปกรณ์คล้ายการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
|  [HttpRequestMessage](./httprequestmessage/)() | สร้างอินสแตนซ์ใหม่ |
|  [HttpRequestMessage](./httprequestmessage/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | สร้างอินสแตนซ์ใหม่ |
|  [HttpRequestMessage](./httprequestmessage/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\>, [String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นอุปกรณ์คล้ายออเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| **bool** [MarkAsSent](./markassent/)() | ทำเครื่องหมายคำขอปัจจุบันว่าได้ส่งแล้ว |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอุปกรณ์คล้ายเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# ทำให้สามารถคล cloning ประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์และกำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่กำหนดค่าอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่กำหนดค่าอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนคอนเทอร์รีฟเฟอเรนซ์แบบแชร์โดยค่าที่ระบุ |
| void [set_Content](./set_content/)([System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\>) | ตั้งค่าเนื้อหาของคำขอ HTTP |
| void [set_Method](./set_method/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\>) | ตั้งค่าเมธอดของคำขอ HTTP |
| void [set_RequestUri](./set_requesturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ตั้งค่า URI ของทรัพยากรที่ร้องขอ |
| void [set_Version](./set_version/)([System::Version](../../system/version/)) | ตั้งค่าเวอร์ชัน HTTP |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็นพอยเตอร์แบบอ่อน (แทนที่จะแบ่งปัน) เพื่อให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมดอ่อนได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของคอนเทอร์รีฟเฟอเรนซ์แบบแชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มคอนเทอร์รีฟเฟอเรนซ์แบบแชร์ ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยเตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าคอนเทอร์รีฟเฟอเรนซ์แบบแชร์ ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยเตอร์หรือ ThisProtector |
| [String](../../system/string/) [ToString](./tostring/)() const override | เป็นอุปกรณ์คล้ายเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# ทำให้สามารถแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่สร้างโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มคอนเทอร์รีฟเฟอเรนซ์แบบอ่อน ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยเตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดคอนเทอร์รีฟเฟอเรนซ์แบบอ่อน ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยเตอร์หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์และปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::Net::Http](../)
* ไลบรารี [Aspose.Slides](../../)