---
title: RSA
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "คลาสฐานสำหรับการใช้งานของอัลกอริทึม RSA. วัตถุของคลาสนี้ควรจะถูกจัดสรรด้วยฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดระหว่างการทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 456
url: /th/system.security.cryptography/rsa/
---
## RSA คลาส

คลาสฐานสำหรับการใช้งานของอัลกอริทึม [RSA](./). วัตถุของคลาสนี้ควรจะจองหน่วยความจำโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดระหว่างการทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class RSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | ปล่อยทรัพยากรทั้งหมด. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)() | สร้างการทำงานเริ่มต้นของอัลกอริทึม [RSA](./). |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)(const [String](../../system/string/)\&) | สร้างการทำงานเริ่มต้นของอัลกอริทึม [RSA](./). |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)(**int32_t**) | สร้างการทำงานเริ่มต้นของอัลกอริทึม [RSA](./) ด้วยขนาดคีย์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)(const [RSAParameters](../rsaparameters/)\&) | สร้างการทำงานเริ่มต้นของอัลกอริทึม [RSA](./) ด้วยพารามิเตอร์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [CreateFromXmlString](./createfromxmlstring/)(const [String](../../system/string/)\&) | สร้างการทำงานเริ่มต้นของอัลกอริทึม [RSA](./) ด้วยพารามิเตอร์ที่เข้ารหัสเป็น XML ที่ระบุ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) | ถอดรหัสข้อมูลเข้าโดยใช้โหมดการเติมที่ระบุ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [DecryptValue](./decryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | ถอดรหัสค่าโดยใช้คีย์ส่วนตัว. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | ปล่อยทรัพยากรที่ออบเจ็กต์ปัจจุบันเป็นเจ้าของ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) | เข้ารหัสข้อมูลเข้าโดยใช้โหมดการเติมที่ระบุ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [EncryptValue](./encryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | เข้ารหัสค่าด้วยคีย์ส่วนตัว. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงตามสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยใช้สไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าตัวเลขแบบ floating point ตามสไตล์ของ C# ซึ่ง NaN สองค่า ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าตัวเลขแบบ floating point ตามสไตล์ของ C# ซึ่ง NaN สองค่า ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual [RSAParameters](../rsaparameters/) [ExportParameters](./exportparameters/)(**bool**) | ส่งออกพารามิเตอร์ทั้งหมด. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| void [FromXmlString](./fromxmlstring/)([String](../../system/string/)) override | เริ่มต้นอ็อบเจ็กต์โดยใช้พารามิเตอร์ที่เข้ารหัสเป็น XML. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | ตรวจสอบอัลกอริทึมการแลกเปลี่ยนคีย์ที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | รับขนาดคีย์. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | รับอาร์เรย์ของขนาดคีย์ที่อนุญาต. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | รับอัลกอริทึมลายเซ็นที่เชื่อมโยงกับอ็อบเจ็กต์ CSP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ออนาล็อกของเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C#. ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. ออนาล็อกของการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C#. |
| virtual void [ImportParameters](./importparameters/)([RSAParameters](../rsaparameters/)) | นำเข้าพารามิเตอร์ทั้งหมดจากโครงสร้างข้อมูล. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. ออนาล็อกของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ออนาล็อกของเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เช specialized ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เช specialized ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | ตั้งค่าขนาดคีย์. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการนับอ้างอิงร่วมและส่งค่ากลับ. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | คำนวณค่าฮัชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริทึมและการเติมที่ระบุ, แล้วทำการเซ็นผลลัพธ์. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | คำนวณค่าฮัชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริทึมและการเติมที่ระบุ, แล้วทำการเซ็นผลลัพธ์. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | คำนวณค่าฮัชของสตรีมไบนารีที่ระบุโดยใช้แฮชอัลกอริทึมและการเติมที่ระบุ, แล้วทำการเซ็นผลลัพธ์. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)([ByteArrayPtr](../../system/bytearrayptr/), [HashAlgorithmName](../hashalgorithmname/), [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) | คำนวณลายเซ็นสำหรับค่าฮัชที่ระบุ. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ออนาล็อกของเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)(**bool**) override | ส่งออกพารามิเตอร์ทั้งหมดในรูปแบบ XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นค่าที่ถูกต้อง. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นค่าที่ถูกต้อง. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | ตรวจสอบว่าลายเซ็นของสตรีมไบนารีที่ระบุเป็นค่าที่ถูกต้อง. |
| virtual **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/), const [HashAlgorithmName](../hashalgorithmname/)\&, [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) | ตรวจสอบว่าลายเซ็นของฮัชที่ระบุเป็นค่าที่ถูกต้อง. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [AsymmetricAlgorithm](../asymmetricalgorithm/)
* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)