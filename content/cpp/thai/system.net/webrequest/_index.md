---
title: WebRequest
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "เป็นตัวแทนของคำขอเว็บ. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject(). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการละเมิดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ System::SmartPtr และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 508
url: /th/system.net/webrequest/
---
## คลาส WebRequest


เป็นตัวแทนของคำขอเว็บ. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการละเมิดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class WebRequest : public virtual System::Object
```

## วิธีการ

| Method | Description |
| --- | --- |
| virtual void [Abort](./abort/)() | ยกเลิกคำขอที่กำลังทำอยู่. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เริ่มต้นการดำเนินการแบบอะซิงโครนัสเพื่อรับสตรีมสำหรับการเขียนข้อมูลไปยังทรัพยากร. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | เริ่มต้นการร้องขอแบบอะซิงโครนัสสำหรับทรัพยากร. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](./)\> [Create](./create/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](./) โดยใช้ URI ที่ระบุ. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](./)\> [Create](./create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | สร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](./) โดยใช้ URI ที่ระบุ. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](./)\> [CreateDefault](./createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | สร้างทายาท [WebRequest](./) สำหรับสเค็ม URI ที่ระบุ. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](./createhttp/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](./) โดยใช้ URI ที่ระบุ. |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](./createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | สร้างอินสแตนซ์ใหม่ของคลาส [WebRequest](./) โดยใช้ URI ที่ระบุ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | รอจนการดำเนินการแบบอะซิงโครนัสที่ระบุเพื่อรับสตรีมเสร็จสิ้น. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | รอจนการร้องขอแบบอะซิงโครนัสที่ระบุสำหรับทรัพยากรเสร็จสิ้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจุดทศนิยมสไตล์ C# ซึ่ง NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจุดทศนิยมแบบ double สไตล์ C# ซึ่ง NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการใช้งานภายในเท่านั้น. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](./get_cachepolicy/)() | รับนโยบายแคช. |
| virtual [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() | รับชื่อของกลุ่มการเชื่อมต่อ. |
| virtual **int64_t** [get_ContentLength](./get_contentlength/)() | รับจำนวนไบต์ของข้อมูลคำขอที่จะส่ง. |
| virtual [String](../../system/string/) [get_ContentType](./get_contenttype/)() | รับประเภท MIME ของคำขอ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() | รับข้อมูลการตรวจสอบสิทธิ์ที่เชื่อมโยงกับคำขอปัจจุบัน. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](./get_defaultwebproxy/)() | รับพร็อกซี HTTP ทั่วโลก. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() | รับคอลเลกชันของหัวข้อ HTTP. |
| virtual [String](../../system/string/) [get_Method](./get_method/)() | รับวิธีการ HTTP. |
| virtual **bool** [get_PreAuthenticate](./get_preauthenticate/)() | รับค่าที่ระบุว่าคำขอต้องทำการตรวจสอบสิทธิ์ล่วงหน้าหรือไม่. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](./get_prefixlist/)() | รับรายการคำนำหน้า. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() | รับพร็อกซี HTTP. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() | ส่งคืน URI ของคำขอ. |
| virtual **int32_t** [get_Timeout](./get_timeout/)() | รับระยะเวลามิลลิวินาทีที่หลังจากนั้นคำขอจะหมดเวลา. |
| virtual **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | รับค่าที่ระบุว่า property 'Credential' เท่ากับ property 'DefaultCredentials' หรือไม่. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกชนิดของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเอง. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() | ส่งคืนสตรีมสำหรับเขียนข้อมูลไปยังทรัพยากร. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() | ส่งคืนการตอบสนองเว็บที่เชื่อมโยงกับคำขอเว็บปัจจุบัน. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นอเนกชนิดของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอเนกชนิดของอ็อปเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกชนิดของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถคลอนอ็อบเจกต์ประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอ้อะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้การสร้างคัดลอกในคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอ้อะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้การสร้างคัดลอกในคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| static **bool** [RegisterPrefix](./registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | ลงทะเบียนทายาท [WebRequest](./) สำหรับ URI ที่ระบุ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| virtual void [set_CachePolicy](./set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | ตั้งค่านโยบายแคช. |
| virtual void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) | ตั้งชื่อของกลุ่มการเชื่อมต่อ. |
| virtual void [set_ContentLength](./set_contentlength/)(**int64_t**) | ตั้งค่าจำนวนไบต์ของข้อมูลคำขอที่จะส่ง. |
| virtual void [set_ContentType](./set_contenttype/)([String](../../system/string/)) | ตั้งค่าประเภท MIME ของคำขอ. |
| virtual void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | ตั้งค่าข้อมูลการตรวจสอบสิทธิ์ที่เชื่อมโยงกับคำขอปัจจุบัน. |
| static void [set_DefaultWebProxy](./set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | ตั้งค่าพร็อกซี HTTP ทั่วโลก. |
| virtual void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) | ตั้งค่าคอลเลกชันของหัวข้อ HTTP. |
| virtual void [set_Method](./set_method/)([String](../../system/string/)) | ตั้งค่าวิธีการ HTTP. |
| virtual void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) | ตั้งค่าที่ระบุว่าคำขอต้องทำการตรวจสอบล่วงหน้าหรือไม่. |
| static void [set_PrefixList](./set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | ตั้งค่ารายการคำนำหน้า. |
| virtual void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | ตั้งค่าพร็อกซี HTTP. |
| virtual void [set_Timeout](./set_timeout/)(**int32_t**) | ตั้งระยะเวลามิลลิวินาทีที่หลังจากนั้นคำขอจะหมดเวลา. |
| virtual void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) | ตั้งค่าที่ระบุว่า property 'Credential' เท่ากับ property 'DefaultCredentials' หรือไม่. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกชนิดของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Net](../)
* ไลบรารี [Aspose.Slides](../../)