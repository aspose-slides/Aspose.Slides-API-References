---
title: Details_SoapException
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงถึงข้อยกเว้นที่ถูกขว้างเมื่อเรียกเมธอดผ่าน SOAP แล้วเกิดข้อผิดพลาด ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส SoapException แทน ไม่ควรห่ออินสแตนซ์ของคลาส SoapException เข้าไปใน System::SmartPtr."
type: docs
weight: 1
url: /th/system.web.services.protocols/details_soapexception/
---
## Details_SoapException คลาส

แสดงถึงข้อยกเว้นที่ถูกขว้างเมื่อเรียกเมธอดผ่าน SOAP แล้วเกิดข้อผิดพลาด ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ให้ใช้คลาส SoapException แทน ไม่ควรห่ออินสแตนซ์ของคลาส SoapException เข้าไปใน [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_SoapException : public System::Details_SystemException
```

## เมธอด

| Method | Description |
| --- | --- |
|  [Details_SoapException](./details_soapexception/)() | สร้างอินสแตนซ์ใหม่ |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | สร้างอินสแตนซ์ใหม่ |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [Exception](../../system/exception/)) | สร้างอินสแตนซ์ใหม่ |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [Exception](../../system/exception/)) | สร้างอินสแตนซ์ใหม่ |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>) | สร้างอินสแตนซ์ใหม่ |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [Exception](../../system/exception/)) | สร้างอินสแตนซ์ใหม่ |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>) | สร้างอินสแตนซ์ใหม่ |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | สร้างอินสแตนซ์ใหม่ |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | สร้างอินสแตนซ์ใหม่ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เชิงปฏิบัติของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์อ้างอิงแบบสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ค่าประเภทแบบสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมสไตล์ C# โดยถือว่า NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมสไตล์ C# โดยถือว่า NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [String](../../system/string/) [get_Actor](./get_actor/)() | คืนส่วนของโค้ดที่ทำให้ข้อยกเว้นถูกขว้างเมื่อใช้ SOAP เวอร์ชัน 1.1 |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_Code](./get_code/)() | คืนชื่อท้องถิ่นที่มีคำนำหน้าชื่อเนมสเปซในรูปแบบ 'namespace:localname' ซึ่งระบุรหัสข้อผิดพลาดของ SOAP |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | คืนพจนานุกรมที่มีข้อมูลข้อยกเว้นแบบกำหนดเอง |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\> [get_Detail](./get_detail/)() | คืนรายละเอียดของข้อยกเว้นที่ถูกขว้าง |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | คืนค่าจำนวนเต็ม 32-บิตที่เป็นรหัส HRESULT ที่สัมพันธ์กับข้อยกเว้นที่แสดงโดยอ็อบเจ็กต์นี้ |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | คืนการอ้างอิงไปยังอ็อบเจ็กต์ที่เป็นข้อยกเว้นภายใน |
| [String](../../system/string/) [get_Lang](./get_lang/)() | คืนภาษาที่ใช้ในการแปลคุณสมบัติของข้อยกเว้น |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | คืนสตริงที่บรรจุคำอธิบายข้อผิดพลาด |
| [String](../../system/string/) [get_Node](./get_node/)() | คืนส่วนของโค้ดที่ทำให้ข้อยกเว้นถูกขว้างเมื่อใช้ SOAP เวอร์ชัน 1.2 |
| [String](../../system/string/) [get_Role](./get_role/)() | คืนบทบาทของเว็บเซอร์วิส XML ที่ขว้างข้อยกเว้น |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | คืนสตริงที่บรรจุตราสำหรับสแตก |
| [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\> [get_SubCode](./get_subcode/)() | คืนข้อมูลเพิ่มเติมจากอิลเมนต์ XML 'subcode' |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | คืนสำเนาของอ็อบเจ็กต์ Exception ที่เป็นข้อยกเว้นที่ลึกที่สุด |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เวอร์ชันของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชของอ็อบเจ็กต์กำหนดเอง |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | รับชนิดจริงของอ็อบเจ็กต์ เวอร์ชันของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| static **bool** [IsClientFaultCode](./isclientfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | ตรวจสอบว่ารหัสที่ระบุเท่ากับรหัสข้อผิดพลาด SOAP 'Client' หรือไม่ |
| static **bool** [IsMustUnderstandFaultCode](./ismustunderstandfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | ตรวจสอบว่ารหัสที่ระบุเท่ากับรหัสข้อผิดพลาด SOAP 'MustUnderstand' หรือไม่ |
| static **bool** [IsServerFaultCode](./isserverfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | ตรวจสอบว่ารหัสที่ระบุเท่ากับรหัสข้อผิดพลาด SOAP 'Server' หรือไม่ |
| static **bool** [IsVersionMismatchFaultCode](./isversionmismatchfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | ตรวจสอบว่ารหัสที่ระบุเท่กับรหัสข้อผิดพลาด SOAP 'VersionMismatch' หรือไม่ |
| void [Lock](../../system/object/lock/)() | ติดตั้งการล็อกแบบ C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เวอร์ชันของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการคล cloning แบบกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาในคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาในคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ค่าประเภทกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับการอ้างอิงร่วมลงตามค่าที่ระบุ |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT ซึ่งเป็นค่าตัวเลขที่รหัสสำหรับข้อยกเว้นเฉพาะ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) เพื่อสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงร่วม ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับการอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | คืนสตริงที่เป็นการแสดงผลของอ็อบเจ็กต์ปัจจุบัน |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | ปล่อยการล็อกแบบ C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| virtual const char * [what](../../system/details_exception/what/)() const | implements [what()](../../system/details_exception/what/) method ซึ่งถูกเรียกโดยคลาส [ExceptionWrapper](../../system/exceptionwrapper/) แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception แต่คลาสที่สืบทอดสามารถใช้สมาชิกที่เป็น protected/private เพื่อทำตรรกะของตน การย้ายการดำเนินการเมธอดนี้ไปที่ [ExceptionWrapper](../../system/exceptionwrapper/) อาจทำให้ตรรกะเสีย |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ฟิลด์

| Field | Description |
| --- | --- |
| static [ClientFaultCode](./clientfaultcode/) | รหัสข้อผิดพลาด SOAP ที่แสดงถึงการเรียกจากไคลเอนท์ที่รูปแบบไม่ถูกต้องหรือขาดข้อมูลที่จำเป็น |
| static [DetailElementName](./detailelementname/) | ชื่อท้องถิ่นที่มีคำนำหน้าชื่อเนมสเปซในรูปแบบ 'namespace:localname' |
| static [MustUnderstandFaultCode](./mustunderstandfaultcode/) | รหัสข้อผิดพลาด SOAP ที่บ่งบอกว่าองค์ประกอบ SOAP ที่มีแอตทริบิวต์ 'MustUnderstand' ไม่ได้ถูกประมวลผล |
| static [ServerFaultCode](./serverfaultcode/) | รหัสข้อผิดพลาด SOAP ที่แสดงถึงข้อผิดพลาดที่เกิดบนเซิร์ฟเวอร์ |
| static [VersionMismatchFaultCode](./versionmismatchfaultcode/) | รหัสข้อผิดพลาด SOAP ที่แสดงถึงเนมสเปซที่ไม่ถูกต้อง |

## ดูเพิ่มเติม

* คลาส [Details_SystemException](../../system/details_systemexception/)
* เนมสเปซ [System::Web::Services::Protocols](../)
* ไลบรารี [Aspose.Slides](../../)