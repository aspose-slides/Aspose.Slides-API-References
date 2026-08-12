---
title: X509Certificate2
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงถึงใบรับรอง X509. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยเตอร์ System::SmartPtr และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 40
url: /th/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 คลาส

แสดงถึงใบรับรอง X509. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromCertFile](../x509certificate/createfromcertfile/)(const [String](../../system/string/)\&) | สร้างใบรับรองจากไฟล์ PKCS7 ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromSignedFile](../x509certificate/createfromsignedfile/)(const [String](../../system/string/)\&) | สร้างใบรับรองจากไฟล์ที่เซ็นแล้วที่ระบุ. |
| void [Dispose](../x509certificate/dispose/)() override | ไม่ทำอะไร. |
| **bool** [Equals](../x509certificate/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบใบรับรองสองใบ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้รูปแบบการทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าได้รับการพิจารณาว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าได้รับการพิจารณาว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/)) const | ส่งออกวัตถุปัจจุบันเป็นอาร์เรย์ไบต์โดยใช้รูปแบบที่ระบุ. ยังไม่ได้ทำการดำเนินการ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | ส่งออกวัตถุปัจจุบันเป็นอาร์เรย์ไบต์โดยใช้รูปแบบที่ระบุ. ยังไม่ได้ทำการดำเนินการ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | ส่งออกวัตถุปัจจุบันเป็นอาร์เรย์ไบต์โดยใช้รูปแบบที่ระบุ. ยังไม่ได้ทำการดำเนินการ. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| **bool** [get_Archived](./get_archived/)() const | รับค่าที่ระบุว่าใบรับรองถูกเก็บถาวร. |
| [X509ExtensionCollectionPtr](../x509extensioncollectionptr/) [get_Extensions](./get_extensions/)() const | รับคอลเลกชันของอ็อบเจกต์ส่วนขยายที่เชื่อมโยงกับใบรับรอง. |
| [String](../../system/string/) [get_FriendlyName](./get_friendlyname/)() const | รับชื่อที่เป็นมิตรของใบรับรอง. |
| IntPtr [get_Handle](../x509certificate/get_handle/)() const | รับแฮนด์เดิลไปยังบริบทใบรับรองของ Microsoft Cryptographic API. |
| **bool** [get_HasPrivateKey](./get_hasprivatekey/)() const | ตรวจสอบว่าใบรับรองมีคีย์ส่วนตัวหรือไม่. |
| [String](../../system/string/) [get_Issuer](../x509certificate/get_issuer/)() const | รับชื่อของหน่วยงานออกใบรับรองที่ออกใบรับรอง X.509v3 |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_IssuerName](./get_issuername/)() const | รับชื่อของฝ่ายที่ออกใบรับรอง. |
| [DateTime](../../system/datetime/) [get_NotAfter](./get_notafter/)() const | รับวันที่และเวลาท้องถิ่นที่หลังจากนั้นใบรับรองจะไม่เป็นที่ใช้ได้อีก. |
| [DateTime](../../system/datetime/) [get_NotBefore](./get_notbefore/)() const | รับวันที่และเวลาท้องถิ่นที่ใบรับรองเริ่มมีผล. |
| [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\> [get_PrivateKey](./get_privatekey/)() const | รับคีย์ส่วนตัวที่เชื่อมโยงกับใบรับรอง. |
| [SharedPtr](../../system/sharedptr/)\<[PublicKey](../publickey/)\> [get_PublicKey](./get_publickey/)() const | รับอ็อบเจกต์ใบรับรอง [PublicKey](../publickey/). |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](./get_rawdata/)() const | รับข้อมูลดิบของใบรับรอง. |
| [String](../../system/string/) [get_SerialNumber](./get_serialnumber/)() const | รับหมายเลขลำดับของใบรับรอง. |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | รับอัลกอริทึมที่ใช้สร้างลายเซ็นของใบรับรอง. |
| [String](../../system/string/) [get_Subject](../x509certificate/get_subject/)() const | รับชื่อแยกแยะของผู้ถือจากใบรับรอง. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_SubjectName](./get_subjectname/)() const | รับชื่อผู้ถือจากใบรับรอง. |
| [String](../../system/string/) [get_Thumbprint](./get_thumbprint/)() const | รับลายนิ้วมือของใบรับรอง. |
| **int32_t** [get_Version](./get_version/)() const | รับเวอร์ชันของรูปแบบใบรับรอง. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | รับประเภทของใบรับรองที่อยู่ในอาร์เรย์ไบต์ที่ระบุ. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [String](../../system/string/)\&) | รับประเภทของใบรับรองที่อยู่ในไฟล์ที่ระบุ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)() const | รับแฮชของวัตถุปัจจุบันเป็นอาร์เรย์ไบต์. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | รับแฮชของวัตถุปัจจุบันเป็นอาร์เรย์ไบต์. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)() const | รับแฮช [SHA1](../../system.security.cryptography/sha1/) ของวัตถุปัจจุบันเป็นสตริงฐานสิบหก. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | รับแฮช [SHA1](../../system.security.cryptography/sha1/) ของวัตถุปัจจุบันเป็นสตริงฐานสิบหก. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPrivateKey](./getdsaprivatekey/)() const | รับคีย์ส่วนตัว [RSA](../../system.security.cryptography/rsa/); |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPublicKey](./getdsapublickey/)() const | รับคีย์สาธารณะ [RSA](../../system.security.cryptography/rsa/). |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | รับคีย์ส่วนตัว [RSA](../../system.security.cryptography/rsa/); |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPublicKey](./getecdsapublickey/)() const | รับคีย์สาธารณะ [RSA](../../system.security.cryptography/rsa/). |
| virtual [String](../../system/string/) [GetEffectiveDateString](../x509certificate/geteffectivedatestring/)() const | รับวันที่มีผลของใบรับรองปัจจุบัน. |
| virtual [String](../../system/string/) [GetExpirationDateString](../x509certificate/getexpirationdatestring/)() const | รับวันที่หมดอายุของใบรับรองปัจจุบัน. |
| virtual [String](../../system/string/) [GetFormat](../x509certificate/getformat/)() const | รับชื่อของรูปแบบใบรับรอง. |
| **int32_t** [GetHashCode](../x509certificate/gethashcode/)() const override | รับค่าแฮชของใบรับรอง. |
| virtual [String](../../system/string/) [GetIssuerName](../x509certificate/getissuername/)() const | รับชื่อของหน่วยงานรับรองที่ออกใบรับรองปัจจุบัน. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](../x509certificate/getkeyalgorithm/)() const | รับข้อมูลคีย์ของใบรับรองปัจจุบันเป็นสตริง. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](../x509certificate/getkeyalgorithmparameters/)() const | รับข้อมูลคีย์ของใบรับรองปัจจุบันเป็นอาร์เรย์ไบต์. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](../x509certificate/getkeyalgorithmparametersstring/)() const | รับข้อมูลคีย์ของใบรับรองปัจจุบันเป็นสตริงฐานสิบหก. |
| virtual [String](../../system/string/) [GetName](../x509certificate/getname/)() const | รับชื่อของผู้ถือหลักที่ใบรับรองปัจจุบันออกให้. |
| [String](../../system/string/) [GetNameInfo](./getnameinfo/)([X509NameType](../x509nametype/), **bool**) const | รับชื่อผู้ถือหรือผู้ออกจากใบรับรอง. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](../x509certificate/getpublickey/)() const | รับคีย์สาธารณะจากใบรับรองเป็นอาร์เรย์ไบต์. |
| virtual [String](../../system/string/) [GetPublicKeyString](../x509certificate/getpublickeystring/)() const | รับคีย์สาธารณะจากใบรับรองเป็นสตริงฐานสิบหก. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](../x509certificate/getrawcertdata/)() const | รับข้อมูลดิบจากใบรับรองเป็นอาร์เรย์ไบต์. |
| virtual [String](../../system/string/) [GetRawCertDataString](../x509certificate/getrawcertdatastring/)() const | รับข้อมูลดิบจากใบรับรองเป็นสตริงฐานสิบหก. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPrivateKey](./getrsaprivatekey/)() const | รับคีย์ส่วนตัว [RSA](../../system.security.cryptography/rsa/); |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPublicKey](./getrsapublickey/)() const | รับคีย์สาธารณะ [RSA](../../system.security.cryptography/rsa/). |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](../x509certificate/getserialnumber/)() const | รับหมายเลขลำดับจากใบรับรองเป็นอาร์เรย์ไบต์. |
| virtual [String](../../system/string/) [GetSerialNumberString](../x509certificate/getserialnumberstring/)() const | รับหมายเลขลำดับจากใบรับรองเป็นสตริงฐานสิบหก. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของวัตถุ. เป็นการจำลองการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | นำเข้าข้อมูลจากไฟล์ใบรับรองที่ระบุ. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | นำเข้าข้อมูลจากไฟล์ใบรับรองที่ระบุ. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | นำเข้าข้อมูลจากข้อมูลใบรับรองที่ระบุ. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | นำเข้าข้อมูลจากข้อมูลใบรับรองที่ระบุ. |
| void [Import](./import/)(const [String](../../system/string/)\&) override | นำเข้าข้อมูลจากไฟล์ใบรับรองที่ระบุ. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | นำเข้าข้อมูลจากข้อมูลใบรับรองที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการจำลองตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการจำลองเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวก่อสร้างคัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| [X509Certificate](../x509certificate/)\& [operator=](../x509certificate/operator_equal/)(const [X509Certificate](../x509certificate/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิงเปรียบเทียบวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | ความเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | ความเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [Reset](./reset/)() override | รีเซ็ตสถานะของใบรับรอง. |
| void [set_Archived](./set_archived/)(**bool**) const | ตั้งค่าที่ระบุว่าใบรับรองถูกเก็บถาวร. |
| void [set_FriendlyName](./set_friendlyname/)(const [String](../../system/string/)\&) | ตั้งชื่อที่เป็นมิตรของใบรับรอง. |
| void [set_PrivateKey](./set_privatekey/)(const [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>\&) | ตั้งหรือเคลียร์คีย์ส่วนตัวที่เชื่อมโยงกับใบรับรอง. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| [String](../../system/string/) [ToString](./tostring/)(**bool**) const override | คืนข้อมูลใบรับรองในรูปแบบข้อความ. |
| [String](../../system/string/) [ToString](./tostring/)() const override | คืนข้อมูลใบรับรองในรูปแบบข้อความ. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตาม construct typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| **bool** [Verify](./verify/)() const | ตรวจสอบห่วงโซ่ของใบรับรอง. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบอ่อน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบอ่อน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [X509Certificate](../x509certificate/)\&) |  |
|  [X509Certificate](../x509certificate/x509certificate/)() | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate2](./x509certificate2/)() | Constructs empty [X509Certificate2](./). |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |

## ดูเพิ่มเติม

* คลาส [X509Certificate](../x509certificate/)
* เนมสเปซ [System::Security::Cryptography::X509Certificates](../)
* ไลบรารี [Aspose.Slides](../../)