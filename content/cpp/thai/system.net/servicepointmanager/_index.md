---
title: ServicePointManager
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "จัดการขั้นตอนวงจรชีวิต (การสร้าง, การดูแลรักษาและการลบ) ของอินสแตนซ์คลาส ServicePoint. อ็อบเจกต์ของคลาสนี้ควรได้รับการจัดสรรเท่านั้นโดยใช้ฟังก์ชัน System::MakeObject(). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการยืนยัน. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 430
url: /th/system.net/servicepointmanager/
---
## ServicePointManager คลาส

จัดการขั้นตอนวงจรชีวิต (การสร้าง, การดูแลรักษา, และการลบ) ของอินสแตนซ์คลาส [ServicePoint](../servicepoint/). อ็อบเจกต์ของคลาสนี้ควรจะได้รับการจัดสรรเฉพาะด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าเลยสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการยืนยัน. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class ServicePointManager : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบ floating point สไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบ floating point สไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | รับนโยบายใบรับรอง. |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | รับค่าที่บ่งบอกว่าใบรับรองต้องถูกตรวจสอบกับรายการยกเลิกขององค์กรออกใบรับรองหรือไม่. |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | รับจำนวนสูงสุดของการเชื่อมต่อพร้อมกันที่อนุญาตโดยอินสแตนซ์คลาส ServicePoint. |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | รับค่า timeout เป็นมิลลิวินาทีที่การแก้ไข DNS ถือว่าถูกต้อง. |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | รับค่าที่บ่งบอกว่าการแก้ไข DNS จะหมุนระหว่างที่อยู่ IP ที่ใช้ได้หรือไม่. |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | ส่งคืนนโยบายการเข้ารหัสที่ใช้โดยอินสแตนซ์ปัจจุบัน. |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | รับค่าที่บ่งบอกว่าอินสแตนซ์คลาส ServicePoint ใช้พฤติกรรม 100-Continue หรือไม่. |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | รับเวลาว่างสูงสุดของอินสแตนซ์คลาส ServicePoint. |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | รับจำนวนสูงสุดของอินสแตนซ์คลาส ServicePoint ที่สามารถจัดการโดยอินสแตนซ์ปัจจุบัน. |
| static **bool** [get_ReusePort](./get_reuseport/)() | รับค่าที่บ่งบอกว่าซ็อกเก็ตการเชื่อมต่อออกใช้ตัวเลือก 'SO_REUSE_UNICASTPORT' หรือไม่. |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | รับประเภทโปรโตคอลความปลอดภัยที่ใช้โดยอินสแตนซ์คลาส ServicePoint ที่จัดการโดยอินสแตนซ์ปัจจุบัน. |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | รับ callback ที่ใช้ในการตรวจสอบความถูกต้องของใบรับรองเซิร์ฟเวอร์. |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | รับค่าที่บ่งบอกว่าอินสแตนซ์คลาส ServicePoint ใช้อัลกอริธึม Nagle หรือไม่. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกเดียวของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้การแฮชอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นอเนกเดียวของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอเนกเดียวของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกเดียวของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้การโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้การคัดลอกคอนสตรักเตอร์ของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้การคัดลอกคอนสตรักเตอร์ของคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | ตั้งค่านโยบายใบรับรอง. |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | ตั้งค่าที่บ่งบอกว่าใบรับรองต้องถูกตรวจสอบกับรายการยกเลิกขององค์กรออกใบรับรองหรือไม่. |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | ตั้งค่าจำนวนสูงสุดของการเชื่อมต่อพร้อมกันที่อนุญาตโดยอินสแตนซ์คลาส ServicePoint. |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | ตั้งค่า timeout เป็นมิลลิวินาทีที่การแก้ไข DNS ถือว่าถูกต้อง. |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | ตั้งค่าที่บ่งบอกว่าการแก้ไข DNS จะหมุนระหว่าง IP ที่ใช้ได้หรือไม่. |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | ตั้งค่าที่บ่งบอกว่าอินสแตนซ์คลาส ServicePoint ใช้พฤติกรรม 100-Continue หรือไม่. |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | ตั้งค่าเวลาว่างสูงสุดของอินสแตนซ์คลาส ServicePoint. |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | ตั้งค่าจำนวนสูงสุดของอินสแตนซ์คลาส ServicePoint ที่สามารถจัดการโดยอินสแตนซ์ปัจจุบัน. |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | ตั้งค่าที่บ่งบอกว่าซ็อกเก็ตการเชื่อมต่อออกใช้ตัวเลือก 'SO_REUSE_UNICASTPORT' หรือไม่. |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | ตั้งค่าประเภทโปรโตคอลความปลอดภัยที่อินสแตนซ์คลาส ServicePoint ที่จัดการโดยอินสแตนซ์ปัจจุบันใช้. |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | ตั้งค่า callback ที่ใช้ในการตรวจสอบความถูกต้องของใบรับรองเซิร์ฟเวอร์. |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | ตั้งค่าที่บ่งบอกว่าอินสแตนซ์คลาส ServicePoint ใช้อัลกอริธึม Nagle หรือไม่. |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | ตั้งค่าที่บ่งบอกว่าตัวเลือก 'Keep-Alive' เปิดใช้งานหรือไม่. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกเดียวของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้การแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการจำลองโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | จำนวนเริ่มต้นของการเชื่อมต่อที่ไม่คงที่. |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | จำนวนเริ่มต้นของการเชื่อมต่อที่คงที่. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Net](../)
* ไลบรารี [Aspose.Slides](../../)