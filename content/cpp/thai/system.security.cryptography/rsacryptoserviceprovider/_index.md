---
title: RSACryptoServiceProvider
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "อัลกอริธึม RSA ในรูปแบบ CSP. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการตรวจสอบล้มเหลว. ให้ห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr เสมอและใช้ตัวชี้นี้เพื่อส่งผ่านให้กับฟังก์ชันเป็นอาร์กิวเมนต์."
type: docs
weight: 469
url: /th/system.security.cryptography/rsacryptoserviceprovider/
---
## RSACryptoServiceProvider class

[RSA](../rsa/) algorithm ในรูปแบบ CSP. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการตรวจสอบล้มเหลว. ให้ห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งผ่านให้กับฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
class RSACryptoServiceProvider : public System::Security::Cryptography::RSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Methods

| Method | Description |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | ปล่อยทรัพยากรทั้งหมด. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)() | สร้างการทำงานของอัลกอริธึม [RSA](../rsa/) เริ่มต้น. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [String](../../system/string/)\&) | สร้างการทำงานของอัลกอริธึม [RSA](../rsa/) เริ่มต้น. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(**int32_t**) | สร้างการทำงานของอัลกอริธึม [RSA](../rsa/) เริ่มต้นด้วยขนาดคีย์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [RSAParameters](../rsaparameters/)\&) | สร้างการทำงานของอัลกอริธึม [RSA](../rsa/) เริ่มต้นด้วยพารามิเตอร์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [CreateFromXmlString](../rsa/createfromxmlstring/)(const [String](../../system/string/)\&) | สร้างการทำงานของอัลกอริธึม [RSA](../rsa/) เริ่มต้นด้วยพารามิเตอร์ที่เข้ารหัสเป็น XML. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | ถอดรหัสข้อความ. ยังไม่ได้ทำ. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | ถอดรหัสข้อมูลอินพุตโดยใช้โหมดแพดดิ้งที่ระบุ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [DecryptValue](../rsa/decryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | ถอดรหัสค่าโดยใช้คีย์ส่วนตัว. |
| void [Dispose](./dispose/)() override | ปล่อยข้อมูลที่สัมพันธ์กับอ็อบเจ็กต์. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | เข้ารหัสข้อความ. ยังไม่ได้ทำ. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | เข้ารหัสข้อมูลอินพุตโดยใช้โหมดแพดดิ้งที่ระบุ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [EncryptValue](../rsa/encryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | เข้ารหัสค่าโดยใช้คีย์ส่วนตัว. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| [ByteArrayPtr](../../system/bytearrayptr/) [ExportCspBlob](./exportcspblob/)(**bool**) override | ส่งออกบล็อบที่มีข้อมูลของคีย์. ยังไม่ได้ทำ. |
| [RSAParameters](../rsaparameters/) [ExportParameters](./exportparameters/)(**bool**) override | ส่งออกพารามิเตอร์ CSP. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้ภายในเท่านั้น. |
| void [FromXmlString](../rsa/fromxmlstring/)([String](../../system/string/)) override | เริ่มต้นอ็อบเจ็กต์โดยใช้พารามิเตอร์ที่เข้ารหัสเป็น XML. |
| [SharedPtr](../../system/sharedptr/)\<[CspKeyContainerInfo](../cspkeycontainerinfo/)\> [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | รับอ็อบเจ็กต์ [CspKeyContainerInfo](../cspkeycontainerinfo/). |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | ตรวจสอบอัลกอริธึมการแลกเปลี่ยนคีย์ที่สัมพันธ์กับอ็อบเจ็กต์. |
| **int32_t** [get_KeySize](./get_keysize/)() override | รับขนาดคีย์ที่อัลกอริธึมใช้. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | รับอาร์เรย์ของขนาดคีย์ที่อนุญาต. |
| **bool** [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | ตรวจสอบว่าคีย์ถูกเก็บรักษาในอ็อบเจ็กต์ CSP หรือไม่. |
| **bool** [get_PublicOnly](./get_publiconly/)() const | ตรวจสอบว่ามีคีย์สาธารณะอย่างเดียวอยู่ในอ็อบเจ็กต์ CSP หรือไม่. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | รับอัลกอริธึมลายเซ็นที่สัมพันธ์กับอ็อบเจ็กต์ CSP. |
| static **bool** [get_UseMachineKeyStore](./get_usemachinekeystore/)() | ตรวจสอบว่าคีย์ถูกเก็บในที่เก็บของเครื่องแทนที่เก็บของผู้ใช้หรือไม่. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่สัมพันธ์กับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| void [ImportCspBlob](./importcspblob/)([ByteArrayPtr](../../system/bytearrayptr/)) override | นำเข้าบล็อบที่มีข้อมูลของคีย์. ยังไม่ได้ทำ. |
| void [ImportParameters](./importparameters/)([RSAParameters](../rsaparameters/)) override | นำเข้าพารามิเตอร์ CSP. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนของประเภทที่กำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างคอนสตรัคเตอร์คัดลอกของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมายค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างคอนสตรัคเตอร์คัดลอกของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับการอ้างอิงร่วมตามค่าที่ระบุ. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)() | คอนสตรัคเตอร์. ใช้พารามิเตอร์ค่าเริ่มต้น. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | คอนสตรัคเตอร์. ยังไม่ได้ทำ. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [RSAParameters](../rsaparameters/)\&) | คอนสตรัคเตอร์. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**) | คอนสตรัคเตอร์. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**, const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | คอนสตรัคเตอร์. ยังไม่ได้ทำ. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | ตั้งค่าขนาดคีย์. |
| void [set_PersistKeyInCsp](./set_persistkeyincsp/)(**bool**) | กำหนดว่าคีย์ถูกเก็บในอ็อบเจ็กต์ CSP หรือไม่. |
| static void [set_UseMachineKeyStore](./set_usemachinekeystore/)(**bool**) | กำหนดว่าคีย์ถูกเก็บในที่เก็บของเครื่องแทนที่ของผู้ใช้หรือไม่. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | คำนวณลายเซ็นของค่าที่ระบุ. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | คำนวณลายเซ็นของค่าที่ระบุ. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | คำนวณลายเซ็นของค่าที่ระบุ. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริธึมและการแพดดิ้งที่ระบุ, แล้วทำลายผลลัพธ์. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริธึมและการแพดดิ้งที่ระบุ, แล้วทำลายผลลัพธ์. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | คำนวณค่าแฮชของสตรีมไบต์ที่ระบุโดยใช้แฮชอัลกอริธึมและการแพดดิ้งที่ระบุ, แล้วทำลายผลลัพธ์. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)([ByteArrayPtr](../../system/bytearrayptr/), [HashAlgorithmName](../hashalgorithmname/), [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | คำนวณลายเซ็นสำหรับค่าแฮชที่ระบุ. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | คำนวณลายเซ็นของค่าที่ระบุ. ยังไม่ได้ทำ. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง. |
| [String](../../system/string/) [ToXmlString](../rsa/toxmlstring/)(**bool**) override | ส่งออกพารามิเตอร์ทั้งหมดในรูปแบบ XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentinel [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | ตรวจสอบลายเซ็นข้อมูล. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นค่าที่ถูกต้อง. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นค่าที่ถูกต้อง. |
| **bool** [VerifyData](../rsa/verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | ตรวจสอบว่าลายเซ็นของสตรีมไบต์ที่ระบุเป็นค่าที่ถูกต้อง. |
| **bool** [VerifyHash](./verifyhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | ตรวจสอบลายเซ็นข้อมูล. |
| **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/), const [HashAlgorithmName](../hashalgorithmname/)\&, [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | ตรวจสอบว่าลายเซ็นของแฮชที่ระบุเป็นค่าที่ถูกต้อง. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [RSA](../rsa/)
* คลาส [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)