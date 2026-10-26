---
title: DSA
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "คลาสฐานสำหรับการใช้งานอัลกอริธึม DSA. อ็อบเจกต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบข้อบังคับ. ควรห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 131
url: /th/system.security.cryptography/dsa/
---
## คลาส DSA

Base class for implementations of [DSA](./) algorithm. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | ปล่อยทรัพยากรทั้งหมด. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)() | สร้างการใช้งานอัลกอริธึม [DSA](./) เริ่มต้น. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)(const [String](../../system/string/)\&) | สร้างการใช้งานอัลกอริธึม [DSA](./) เริ่มต้น. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)(**int32_t**) | สร้างการใช้งานอัลกอริธึม [DSA](./) เริ่มต้นโดยกำหนดขนาดคีย์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)(const [DSAParameters](../dsaparameters/)\&) | สร้างการใช้งานอัลกอริธึม [DSA](./) เริ่มต้นโดยกำหนดพารามิเตอร์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [CreateFromXmlString](./createfromxmlstring/)(const [String](../../system/string/)\&) | สร้างการใช้งานอัลกอริธึม [DSA](./) เริ่มต้นโดยกำหนดพารามิเตอร์ที่เข้ารหัสเป็น XML ที่ระบุ. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [CreateSignature](./createsignature/)([ByteArrayPtr](../../system/bytearrayptr/)) | สร้างลายเซ็น [DSA](./) สำหรับข้อมูลที่ระบุ. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | ปล่อยทรัพยากรที่อ็อบเจกต์ปัจจุบันเป็นเจ้าของ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ตรรกะของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าตามสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual [DSAParameters](../dsaparameters/) [ExportParameters](./exportparameters/)(**bool**) | ส่งออกพารามิเตอร์ทั้งหมด. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น. |
| void [FromXmlString](./fromxmlstring/)([String](../../system/string/)) override | เริ่มต้นอ็อบเจกต์โดยใช้พารามิเตอร์ที่เข้ารหัสเป็น XML. |
| virtual [String](../../system/string/) [get_KeyExchangeAlgorithm](../asymmetricalgorithm/get_keyexchangealgorithm/)() | รับอัลกอริธึมการแลกเปลี่ยนคีย์ที่จะใช้. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | รับขนาดคีย์. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | รับอาเรย์ของขนาดคีย์ที่อนุญาต. |
| virtual [String](../../system/string/) [get_SignatureAlgorithm](../asymmetricalgorithm/get_signaturealgorithm/)() | รับอัลกอริธึมลายเซ็นที่จะใช้. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกแบบของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอเนกแบบของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [ImportParameters](./importparameters/)([DSAParameters](../dsaparameters/)) | นำเข้าพารามิเตอร์ทั้งหมดจากโครงสร้างข้อมูล. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType. เป็นอเนกแบบของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกแบบของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | โอเปอเรเตอร์การกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับการอ้างอิงที่ใช้ร่วมกันลงตามค่าที่ระบุ. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | ตั้งค่าขนาดคีย์. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n't ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)&, const [HashAlgorithmName](../hashalgorithmname/)&) | คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริธิมที่ระบุและทำการเซ็นผลลัพธ์. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)&) | คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริธิมที่ระบุและทำการเซ็นผลลัพธ์. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)&, const [HashAlgorithmName](../hashalgorithmname/)&) | คำนวณค่าแฮชของสตรีมไบนอรีที่ระบุโดยใช้แฮชอัลกอริธิมที่ระบุและทำการเซ็นผลลัพธ์. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกแบบของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)(**bool**) override | ส่งออกพารามิเตอร์ทั้งหมดในรูปแบบ XML. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)&, const [ByteArrayPtr](../../system/bytearrayptr/)&, const [HashAlgorithmName](../hashalgorithmname/)&) | ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นที่ถูกต้อง. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)&, const [HashAlgorithmName](../hashalgorithmname/)&) | ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นที่ถูกต้อง. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)&, const [ByteArrayPtr](../../system/bytearrayptr/)&, const [HashAlgorithmName](../hashalgorithmname/)&) | ตรวจสอบว่าลายเซ็นของสตรีมไบนอรีที่ระบุเป็นที่ถูกต้อง. |
| virtual **bool** [VerifySignature](./verifysignature/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) | ตรวจสอบลายเซ็น [DSA](./) สำหรับข้อมูลที่ระบุ. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [AsymmetricAlgorithm](../asymmetricalgorithm/)
* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)