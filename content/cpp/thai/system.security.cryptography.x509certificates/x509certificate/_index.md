---
title: X509Certificate
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ใบรับรอง X.509 รุ่น 3. ไม่รองรับใบรับรองที่เข้ารหัส. รองรับเพียงแฟล็ก X509KeyStorageFlags::DefaultKeySet เท่านั้น. วัตถุของคลาสนี้ควรสร้างด้วยฟังก์ชัน System::MakeObject() เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน."
type: docs
weight: 27
url: /th/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate คลาส

ใบรับรอง X.509 รุ่น 3. ไม่รองรับใบรับรองที่เข้ารหัส. รองรับเพียงแฟล็ก [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/). วัตถุของคลาสนี้ควรสร้างเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้ในการส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | สร้างใบรับรองจากไฟล์ PKCS7 ที่ระบุ |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | สร้างใบรับรองจากไฟล์ที่ลงนามที่ระบุ |
| void [Dispose](./dispose/)() override | ไม่ได้ทำอะไร |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบใบรับรองสองใบ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจกต์โดยใช้หลักการ [Object.Equals](../../system/object/equals/) ของ C# |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าทศนิยมสไตล์ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ แม้แต่ NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าทศนิยมสไตล์ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ แม้แต่ NaN เอง |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | ส่งออกออบเจกต์ปัจจุบันเป็นอาร์เรย์ไบต์โดยใช้รูปแบบที่ระบุ. ยังไม่ได้ทำ |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | ส่งออกออบเจกต์ปัจจุบันเป็นอาร์เรย์ไบต์โดยใช้รูปแบบที่ระบุ. ยังไม่ได้ทำ |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | ส่งออกออบเจกต์ปัจจุบันเป็นอาร์เรย์ไบต์โดยใช้รูปแบบที่ระบุ. ยังไม่ได้ทำ |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ส่งออกออบเจกต์ปัจจุบันเป็นอาร์เรย์ไบต์โดยใช้รูปแบบที่ระบุ. ยังไม่ได้ทำ |
| IntPtr [get_Handle](./get_handle/)() const | รับแฮนเดิลไปยังคอนเท็กซ์ใบรับรองของ Microsoft Cryptographic API |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | รับชื่อของหน่วยงานออกใบรับรองที่ออกใบรับรอง X.509v3 |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | รับชื่อที่แยกของผู้ถือจากใบรับรอง |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | รับแฮชของออบเจกต์ปัจจุบันเป็นอาร์เรย์ไบต์ |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | รับแฮชของออบเจกต์ปัจจุบันเป็นอาร์เรย์ไบต์ |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | รับแฮช [SHA1](../../system.security.cryptography/sha1/) ของออบเจกต์ปัจจุบันเป็นสตริงเลขฐานสิบหก |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | รับแฮช [SHA1](../../system.security.cryptography/sha1/) ของออบเจกต์ปัจจุบันเป็นสตริงเลขฐานสิบหก |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลเคาน์เตอร์อ้างอิงที่สัมพันธ์กับออบเจกต์ |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | รับวันที่มีผลของใบรับรองปัจจุบัน |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | รับวันที่หมดอายุของใบรับรองปัจจุบัน |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | รับชื่อรูปแบบของใบรับรอง |
| **int32_t** [GetHashCode](./gethashcode/)() const override | รับค่าแฮชโค้ดของใบรับรอง |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | รับชื่อของหน่วยงานออกใบรับรองที่ออกใบรับรองปัจจุบัน |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | รับข้อมูลคีย์ของใบรับรองปัจจุบันเป็นสตริง |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | รับข้อมูลคีย์ของใบรับรองปัจจุบันเป็นอาร์เรย์ไบต์ |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | รับข้อมูลคีย์ของใบรับรองปัจจุบันเป็นสตริงเลขฐานสิบหก |
| virtual [String](../../system/string/) [GetName](./getname/)() const | รับชื่อของผู้ถือที่ใบรับรองปัจจุบันถูกออกให้ |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | รับคีย์สาธารณะจากใบรับรองเป็นอาร์เรย์ไบต์ |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | รับคีย์สาธารณะจากใบรับรองเป็นสตริงเลขฐานสิบหก |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | รับข้อมูลดิบจากใบรับรองเป็นอาร์เรย์ไบต์ |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | รับข้อมูลดิบจากใบรับรองเป็นสตริงเลขฐานสิบหก |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | รับหมายเลขซีเรียลจากใบรับรองเป็นอาร์เรย์ไบต์ |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | รับหมายเลขซีเรียลจากใบรับรองเป็นสตริงเลขฐานสิบหก |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจกต์. ตรงกับการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | นำเข้าข้อมูลจากไฟล์ใบรับรองที่ระบุ. ยังไม่ได้ทำ |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | นำเข้าข้อมูลจากไฟล์ใบรับรองที่ระบุ. ยังไม่ได้ทำ |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | นำเข้าข้อมูลจากข้อมูลใบรับรองที่ระบุ. ยังไม่ได้ทำ |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | นำเข้าข้อมูลจากข้อมูลใบรับรองที่ระบุ. ยังไม่ได้ทำ |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | นำเข้าข้อมูลจากไฟล์ใบรับรองที่ระบุ. ยังไม่ได้ทำ |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | นำเข้าข้อมูลจากข้อมูลใบรับรองที่ระบุ. ยังไม่ได้ทำ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. ตรงกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบของเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างออบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่คัดลอ้อะไรเลย เพียงเริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของออบเจกต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแยกประเภทของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแยกประเภทของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงแบบแชร์โดยค่าที่ระบุ |
| virtual void [Reset](./reset/)() | รีเซ็ตสถานะของใบรับรอง |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงแบบแชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | คืนข้อมูลใบรับรองในรูปแบบข้อความ |
| [String](../../system/string/) [ToString](./tostring/)() const override | คืนข้อมูลใบรับรองในรูปแบบข้อความ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
|  [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
|  [X509Certificate](./x509certificate/)() | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | คอนสตรัคเตอร์ |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | คอนสตรัคเตอร์ |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ชนิดนิยาม

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | ประเภทพอยน์เตอร์ |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::Security::Cryptography::X509Certificates](../)
* ไลบรารี [Aspose.Slides](../../)