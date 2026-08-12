---
title: HttpWebRequest
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "แสดงถึง HTTP web request. วัตถุของคลาสนี้ควรได้รับการจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject(). ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บน stack หรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบเงื่อนไข. ควรห่อคลาสนี้ด้วย pointer System::SmartPtr และใช้ pointer นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 274
url: /th/system.net/httpwebrequest/
---
## HttpWebRequest คลาส

Represents the HTTP web request. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| void [Abort](./abort/)() override | ยกเลิกคำขอปัจจุบัน. |
| virtual void [AddRange](./addrange/)(**int32_t**) | เพิ่ม header '[Range](../../system/range/)' ไปยังคำขอปัจจุบัน. |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | เพิ่ม header '[Range](../../system/range/)' ไปยังคำขอปัจจุบัน. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เริ่มกระบวนการแบบอะซิงโครนัสเพื่อรับสตรีมสำหรับเขียนข้อมูลไปยังทรัพยากร. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เริ่มคำขอแบบอะซิงโครนัสสำหรับทรัพยากร. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](../webrequest/) โดยใช้ URI ที่ระบุ. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | สร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](../webrequest/) โดยใช้ URI ที่ระบุ. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | สร้างทายาท [WebRequest](../webrequest/) สำหรับโครงแบบ URI ที่ระบุ. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](../webrequest/) โดยใช้ URI ที่ระบุ. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | สร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](../webrequest/) โดยใช้ URI ที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | รอจนกว่ากระบวนการอะซิงโครนัสที่ระบุสำหรับรับสตรีมจะเสร็จสิ้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | รอจนกว่าคำขออะซิงโครนัสที่ระบุสำหรับทรัพยากรจะเสร็จสิ้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงตามสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน ถึงแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน ถึงแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [String](../../system/string/) [get_Accept](./get_accept/)() | รับค่าหัวข้อ HTTP 'Accept'. |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | รับค่าที่บ่งบอกว่าคำขอควรทำตามการเปลี่ยนเส้นทางหรือไม่. |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | รับค่าที่บ่งบอกว่าข้อมูลที่รับจากทรัพยากรต้องบัฟเฟอร์หรือไม่. |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | รับค่าที่บ่งบอกว่าการบัฟเฟอร์สำหรับการส่งข้อมูลเปิดอยู่หรือไม่. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | รับนโยบายแคช. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | รับคอลเลกชันของใบรับรองที่เชื่อมโยงกับคำขอปัจจุบัน. |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | รับชื่อของกลุ่มการเชื่อมต่อ. |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | รับจำนวนไบต์ของข้อมูลคำขอที่จะส่ง. |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | รับประเภท MIME ของคำขอ. |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | รับค่า timeout เพื่อรอจนกว่าจะได้รับรหัสสถานะ 100-Continue. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | รับคอนเทนเนอร์คุ๊กกี้ที่เชื่อมโยงกับเว็บรีเคสปัจจุบัน. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | รับข้อมูลการยืนยันตัวที่เชื่อมโยงกับคำขอปัจจุบัน. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | รับพร็อกซี HTTP ระดับโลก. |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | คืนค่าที่บ่งบอกว่ามีการรับตอบกลับหรือไม่. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | รับคอลเลกชันของหัวข้อ HTTP. |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | รับค่าที่บ่งบอกว่าคำขอปัจจุบันต้องมีหัวข้อ 'Keep-Alive' หรือไม่. |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | รับค่าจำนวนสูงสุดของการเปลี่ยนเส้นทางที่อนุญาต. |
| [String](../../system/string/) [get_Method](./get_method/)() override | รับวิธีการ HTTP. |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | รับค่าที่บ่งบอกว่าคำขอควรได้รับการยืนยันล่วงหน้าหรือไม่. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | รับรายการพรีฟิกซ์. |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | รับพร็อกซี HTTP. |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | รับค่าของหัวข้อ 'Referer'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | คืนค่า URI ของคำขอ. |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | รับค่าที่บ่งบอกว่าข้อมูลต้องส่งเป็นส่วนหรือไม่. |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | คืนค่า service point ที่แสดงการเชื่อมต่อเครือข่ายไปยังทรัพยากร. |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | คืนค่าที่บ่งบอกว่าคำขอปัจจุบันสามารถใช้คุ๊กกี้คอนเทนเนอร์ได้หรือไม่. |
| **int32_t** [get_Timeout](./get_timeout/)() override | รับระยะเวลาเป็นมิลลิวินาทีหลังจากที่คำขอจะหมดเวลา. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | รับค่าที่บ่งบอกว่า property 'Credential' เท่ากับ property 'DefaultCredentials' หรือไม่. |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | รับค่าของหัวข้อ 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของวัตถุที่กำหนดเอง. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | คืนค่าสตรีมสำหรับเขียนข้อมูลไปยังทรัพยากร. |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | คืนค่าเว็บรีสปอนส์ที่เชื่อมโยงกับเว็บรีเคสปัจจุบัน. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของวัตถุ. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | สร้างอินสแตนซ์ใหม่. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | ลงทะเบียนทายาท [WebRequest](../webrequest/) สำหรับ URI ที่ระบุ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | ตั้งค่าหัวข้อ HTTP 'Accept'. |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | ตั้งค่าที่บ่งบอกว่าคำขอควรทำตามการเปลี่ยนเส้นทางหรือไม่. |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | ตั้งค่าที่บ่งบอกว่าข้อมูลที่รับจากทรัพยากรต้องบัฟเฟอร์หรือไม่. |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | ตั้งค่าที่บ่งบอกว่าการบัฟเฟอร์สำหรับการส่งข้อมูลเปิดอยู่หรือไม่. |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | ตั้งค่านโยบายแคช. |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | ตั้งค่าคอลเลกชันของใบรับรองที่เชื่อมโยงกับคำขอปัจจุบัน. |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | ตั้งค่าชื่อของกลุ่มการเชื่อมต่อ. |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | ตั้งค่าจำนวนไบต์ของข้อมูลคำขอที่จะส่ง. |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | ตั้งค่าประเภท MIME ของคำขอ. |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | ตั้งค่า timeout เพื่อรอจนกว่าจะได้รับรหัสสถานะ 100-Continue. |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | ตั้งค่าคอนเทนเนอร์คุ๊กกี้ที่เชื่อมโยงกับเว็บรีเคสปัจจุบัน. |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | ตั้งค่าข้อมูลการยืนยันตัวที่เชื่อมโยงกับคำขอปัจจุบัน. |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | ตั้งค่าพร็อกซี HTTP ระดับโลก. |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | ตั้งค่าคอลเลกชันของหัวข้อ HTTP. |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | ตั้งค่าที่บ่งบอกว่าคำขอปัจจุบันต้องมีหัวข้อ 'Keep-Alive' หรือไม่. |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | ตั้งค่าจำนวนสูงสุดของการเปลี่ยนเส้นทางที่อนุญาต. |
| void [set_Method](./set_method/)([String](../../system/string/)) override | ตั้งค่าวิธีการ HTTP. |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | ตั้งค่าที่บ่งบอกว่าคำขอควรได้รับการยืนยันล่วงหน้าหรือไม่. |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | ตั้งค่ารายการพรีฟิกซ์. |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | ตั้งค่าเวอร์ชันของ HTTP. |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | ตั้งค่าพร็อกซี HTTP. |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | ตั้งค่าค่าของหัวข้อ 'Referer'. |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | ตั้งค่าที่บ่งบอกว่าข้อมูลต้องส่งเป็นส่วนหรือไม่. |
| void [set_Timeout](./set_timeout/)(int) override | ตั้งค่าเวลาเป็นมิลลิวินาทีหลังจากที่คำขอจะหมดเวลา. |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | ตั้งค่าเวลาเป็นมิลลิวินาทีหลังจากที่คำขอจะหมดเวลา. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | ตั้งค่าที่บ่งบอกว่า property 'Credential' เท่ากับ property 'DefaultCredentials' หรือไม่. |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | ตั้งค่าค่าของหัวข้อ 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [WebRequest](../webrequest/)
* เนมส페ซ [System::Net](../)
* ไลบรารี [Aspose.Slides](../../)