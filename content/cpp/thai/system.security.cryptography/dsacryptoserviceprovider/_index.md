---
title: DSACryptoServiceProvider
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "อัลกอริทึม DSA ในรูปแบบ CSP. อ็อบเจกต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() . ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 144
url: /th/system.security.cryptography/dsacryptoserviceprovider/
---
## DSACryptoServiceProvider คลาส

[DSA](../dsa/) อัลกอริธึมในรูปแบบ CSP. อ็อบเจกต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class DSACryptoServiceProvider : public System::Security::Cryptography::DSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | ปลดปล่อยทรัพยากรทั้งหมด. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)() | สร้างการดำเนินการอัลกอริทึม [DSA](../dsa/) เริ่มต้น. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(const [String](../../system/string/)\&) | สร้างการดำเนินการอัลกอริทึม [DSA](../dsa/) เริ่มต้น. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(**int32_t**) | สร้างการดำเนินการอัลกอริทึม [DSA](../dsa/) เริ่มต้นโดยระบุขนาดคีย์. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(const [DSAParameters](../dsaparameters/)\&) | สร้างการดำเนินการอัลกอริทึม [DSA](../dsa/) เริ่มต้นโดยระบุพารามิเตอร์. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [CreateFromXmlString](../dsa/createfromxmlstring/)(const [String](../../system/string/)\&) | สร้างการดำเนินการอัลกอริทึม [DSA](../dsa/) เริ่มต้นโดยระบุพารามิเตอร์ที่เข้ารหัสเป็น XML. |
| [ByteArrayPtr](../../system/bytearrayptr/) [CreateSignature](./createsignature/)([ByteArrayPtr](../../system/bytearrayptr/)) override | สร้างลายเซ็น [DSA](../dsa/) สำหรับข้อมูลที่ระบุ. |
| void [Dispose](./dispose/)() override | ปลดปล่อยข้อมูลที่เชื่อมโยงกับอ็อบเจกต์. |
|  [DSACryptoServiceProvider](./dsacryptoserviceprovider/)() | คอนสตรัคเตอร์ ใช้พารามิเตอร์เริ่มต้น. |
|  [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const [DSAParameters](../dsaparameters/)\&) | คอนสตรัคเตอร์. |
|  [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | คอนสตรัคเตอร์ ยังไม่ได้ทำ. |
|  [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(**int32_t**) | คอนสตรัคเตอร์. |
|  [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(**int32_t**, const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | คอนสตรัคเตอร์ ยังไม่ได้ทำ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ชนิดอ้างอิงแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ชนิดค่าแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าเป็นค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าเป็นค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| [ByteArrayPtr](../../system/bytearrayptr/) [ExportCspBlob](./exportcspblob/)(**bool**) override | ส่งออกบล็อบพร้อมข้อมูลคีย์ ยังไม่ได้ทำ. |
| [DSAParameters](../dsaparameters/) [ExportParameters](./exportparameters/)(**bool**) override | ส่งออพารามิเตอร์ CSP. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| void [FromXmlString](../dsa/fromxmlstring/)([String](../../system/string/)) override | กำหนดค่าอ็อบเจกต์โดยใช้พารามิเตอร์ที่เข้ารหัสเป็น XML. |
| [SharedPtr](../../system/sharedptr/)\<[CspKeyContainerInfo](../cspkeycontainerinfo/)\> [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | ดึงอ็อบเจกต์ [CspKeyContainerInfo](../cspkeycontainerinfo/) |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | ตรวจสอบอัลกอริทึมการแลกเปลี่ยนคีย์ที่เกี่ยวข้องกับอ็อบเจกต์. |
| **int32_t** [get_KeySize](./get_keysize/)() override | ดึงขนาดคีย์. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | ดึงอาเรย์ของขนาดคีย์ที่อนุญาต. |
| **bool** [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | ตรวจสอบว่าคีย์ถูกเก็บไว้ในอ็อบเจกต์ CSP หรือไม่. |
| **bool** [get_PublicOnly](./get_publiconly/)() const | ตรวจสอบว่ามีคีย์สาธารณะอย่างเดียวอยู่ในอ็อบเจกต์ CSP หรือไม่. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | ดึงอัลกอริทึมลายเซ็นที่ใช้. |
| static **bool** [get_UseMachineKeyStore](./get_usemachinekeystore/)() | ตรวจสอบว่าคีย์ถูกเก็บในที่เก็บของเครื่องแทนที่เก็บของผู้ใช้หรือไม่. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C# เปิดใช้งานการแฮชอ็อบเจกต์กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจกต์ เทียบเคียงกับการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C#. |
| void [ImportCspBlob](./importcspblob/)([ByteArrayPtr](../../system/bytearrayptr/)) override | นำเข้าบล็อบพร้อมข้อมูลคีย์ ยังไม่ได้ทำ. |
| void [ImportParameters](./importparameters/)([DSAParameters](../dsaparameters/)) override | นำเข้าพารามิเตอร์ทั้งหมดจากโครงสร้างข้อมูล. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType เทียบเคียงกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# เปิดใช้งานการโคลนประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ กำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงกำหนดค่าอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงกำหนดค่าอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ชนิดค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายค่า. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | ตั้งค่าขนาดคีย์. |
| void [set_PersistKeyInCsp](./set_persistkeyincsp/)(**bool**) | กำหนดว่าคีย์ถูกเก็บในอ็อบเจกต์ CSP หรือไม่. |
| static void [set_UseMachineKeyStore](./set_usemachinekeystore/)(**bool**) | กำหนดว่าคีย์ถูกเก็บในที่เก็บของเครื่องแทนที่เก็บของผู้ใช้หรือไม่. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าจำนวนอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | คำนวณลายเซ็นของค่าข้อมูลที่ระบุ. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | คำนวณลายเซ็นของค่าข้อมูลที่ระบุ. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**) | คำนวณลายเซ็นของค่าข้อมูลที่ระบุ. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | คำนวณค่าแฮชของอาเรย์ข้อมูลที่ระบุโดยใช้อัลกอริทึมแฮชที่ระบุและลงลายเซ็นผลลัพธ์. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | คำนวณค่าแฮชของอาเรย์ข้อมูลที่ระบุโดยใช้อัลกอริทึมแฮชที่ระบุและลงลายเซ็นผลลัพธ์. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | คำนวณค่าแฮชของสตรีมไบนารีที่ระบุโดยใช้อัลกอริทึมแฮชที่ระบุและลงลายเซ็นผลลัพธ์. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | คำนวณลายเซ็นของค่าข้อมูลที่ระบุ. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# เปิดใช้งานการแปลงอ็อบเจกต์กำหนดเองเป็นสตริง. |
| [String](../../system/string/) [ToXmlString](../dsa/toxmlstring/)(**bool**) override | ส่งออพารามิเตอร์ทั้งหมดในรูปแบบ XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตาม construct typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | ตรวจสอบลายเซ็นข้อมูล. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นค่าที่ถูกต้อง. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นค่าที่ถูกต้อง. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | ตรวจสอบว่าลายเซ็นของสตรีมไบนารีที่ระบุเป็นค่าที่ถูกต้อง. |
| **bool** [VerifyHash](./verifyhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | ตรวจสอบลายเซ็นข้อมูล. |
| **bool** [VerifySignature](./verifysignature/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) override | ตรวจสอบลายเซ็น [DSA](../dsa/) สำหรับข้อมูลที่ระบุ. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [DSA](../dsa/)
* คลาส [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)