---
title: SoapClientMessage
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แทนข้อมูลในคำขอ SOAP ที่ส่งหรือการตอบกลับ SOAP ที่รับมา. อ็อบเจกต์ของคลาสนี้ควรจะถูกจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบเงื่อนไข. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 40
url: /th/system.web.services.protocols/soapclientmessage/
---
## คลาส SoapClientMessage

แทนข้อมูลในคำขอ SOAP ที่ส่งหรือการตอบกลับ SOAP ที่รับมา อ็อบเจกต์ของคลาสนี้ควรจะถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบเงื่อนไข ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class SoapClientMessage : public System::Web::Services::Protocols::SoapMessage
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| void [CollectHeaders](../soapmessage/collectheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, [SoapHeaderDirection](../soapheaderdirection/)) | ตั้งค่าคอลเลกชันภายในของส่วนหัว SOAP |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตัวแบบ C# ซึ่ง NaN สองค่า ถือเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตัวแบบ C# ซึ่ง NaN สองค่า ถือเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เฉพาะเพื่อการใช้งานภายใน |
| [System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\> [FindHeader](../soapmessage/findheader/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, const [TypeInfo](../../system/typeinfo/)\&) | ค้นหาการแมปส่วนหัวโดยประเภทส่วนหัวที่ระบุ |
| [String](../../system/string/) [get_Action](./get_action/)() override | คืนค่าแอตทริบิวต์ 'SOAPAction' |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHttpClientProtocol](../soaphttpclientprotocol/)\> [get_Client](./get_client/)() | คืนอินสแตนซ์ของคลาสพร็อกซีคลายเอนต์ |
| [String](../../system/string/) [get_ContentEncoding](../soapmessage/get_contentencoding/)() | รับค่าของส่วนหัว 'Content-Encoding' |
| [String](../../system/string/) [get_ContentType](../soapmessage/get_contenttype/)() | รับค่าของส่วนหัว 'Content-Type' |
| [SoapException](../soapexception/) [get_Exception](../soapmessage/get_exception/)() | รับข้อยกเว้นที่ถูกโยนโดยเมธอดบริการ XML [Web](../../system.web/) |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\> [get_Headers](../soapmessage/get_headers/)() | คืนคอลเลกชันของส่วนหัว SOAP |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_InParameters](../soapmessage/get_inparameters/)() | รับพารามิเตอร์ที่ถูกส่งเข้าสู่เมธอดบริการ XML [Web](../../system.web/) |
| **bool** [get_IsSoap12](../soapmessage/get_issoap12/)() | คืนค่าที่บ่งบอกว่าใช้เวอร์ชัน SOAP 1.2 หรือไม่ |
| virtual **bool** [get_OneWay](./get_oneway/)() | คืนค่าที่บ่งบอกว่าคลายเอนต์ไม่รอให้เซิร์ฟเวอร์ทำการประมวลผลเมธอดจนเสร็จ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_OutParameters](../soapmessage/get_outparameters/)() | รับพารามิเตอร์ผลลัพธ์ที่ถูกส่งเข้าสู่เมธอดบริการ XML [Web](../../system.web/) |
| [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() override | คืนเวอร์ชัน SOAP ที่ใช้อยู่ |
| [SoapMessageStage](../soapmessagestage/) [get_Stage](../soapmessage/get_stage/)() | รับขั้นตอนการประมวลผลของข้อความ SOAP |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [get_Stream](../soapmessage/get_stream/)() | รับสตรีมที่บรรจุข้อมูลข้อความ SOAP |
| [String](../../system/string/) [get_Url](./get_url/)() override | คืน URL ของบริการ XML [Web](../../system.web/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้ |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetInParameterValue](../soapmessage/getinparametervalue/)(**int32_t**) | รับค่าพารามิเตอร์อินพุตที่ดัชนีที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetOutParameterValue](../soapmessage/getoutparametervalue/)(**int32_t**) | รับค่าพารามิเตอร์ผลลัพธ์ที่ดัชนีที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetReturnValue](../soapmessage/getreturnvalue/)() | รับค่าผลลัพธ์ของเมธอดบริการ XML [Web](../../system.web/) |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจกต์ เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่ เป็นอเนกประสงค์ของโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และทำให้สามารถคัดลอกการสร้างซับคลาสได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และทำให้สามารถคัดลอกการสร้างซับคลาสได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าและ nullptr ตามการอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์ลงตามค่าที่ระบุ |
| void [set_ContentEncoding](../soapmessage/set_contentencoding/)([String](../../system/string/)) | ตั้งค่าของส่วนหัว 'Content-Encoding' |
| void [set_ContentType](../soapmessage/set_contenttype/)([String](../../system/string/)) | ตั้งค่าของส่วนหัว 'Content-Type' |
| void [set_InParameters](../soapmessage/set_inparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | ตั้งค่าพารามิเตอร์ที่ถูกส่งเข้าสู่เมธอดบริการ XML [Web](../../system.web/) |
| void [set_InternalStream](../soapmessage/set_internalstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | ตั้งค่าสตรีมที่บรรจุข้อมูลข้อความ SOAP |
| void [set_OutParameters](../soapmessage/set_outparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | ตั้งค่าพารามิเตอร์ผลลัพธ์ที่ถูกส่งเข้าสู่เมธอดบริการ XML [Web](../../system.web/) |
| void [SetException](../soapmessage/setexception/)([SoapException](../soapexception/)) | ตั้งค่าข้อยกเว้นที่ถูกโยนโดยเมธอดบริการ XML [Web](../../system.web/) |
| void [SetHeaders](../soapmessage/setheaders/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\>) | ตั้งค่าคอลเลกชันของส่วนหัว SOAP |
| void [SetStage](../soapmessage/setstage/)([SoapMessageStage](../soapmessagestage/)) | ตั้งค่าขั้นตอนการประมวลผลของข้อความ SOAP |
| void [SetStream](../soapmessage/setstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | ตั้งค่าสตรีมที่บรรจุข้อมูลข้อความ SOAP |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็นพอยน์เตอร์แบบวีก (แทนที่จะแบ่งปัน) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมดวีกได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง; แทนที่ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบแชร์และคืนค่า ไม่ควรเรียกโดยตรง; แทนที่ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
|  [SoapClientMessage](./soapclientmessage/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHttpClientProtocol](../soaphttpclientprotocol/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapMethodStubInfo\>, [String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | สร้างอินสแตนซ์ใหม่ |
|  [SoapMessage](../soapmessage/soapmessage/)() | สร้างอินสแตนซ์ใหม่ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ตาม constructs ของ C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| void [UpdateHeaderValues](../soapmessage/updateheadervalues/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>) | อัปเดตคอลเลกชันภายในของส่วนหัว SOAP |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบวีก ไม่ควรเรียกโดยตรง; แทนที่ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบวีก ไม่ควรเรียกโดยตรง; แทนที่ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [SoapMessage](../soapmessage/)
* เนมสเปซ [System::Web::Services::Protocols](../)
* ไลบรารี [Aspose.Slides](../../)