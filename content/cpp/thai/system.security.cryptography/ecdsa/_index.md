---
title: ECDsa
second_title: "Aspose.Slides สำหรับ C++ API Reference"
description: "คลาสพื้นฐานสำหรับการใช้งานอัลกอริธึม ECDsa. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject(). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันและ/หรือข้อผิดพลาดการตรวจสอบ. หุ้มคลาสนี้ด้วยตัวชี้ System::SmartPtr เสมอและใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 183
url: /th/system.security.cryptography/ecdsa/
---
## คลาส ECDsa


คลาสพื้นฐานสำหรับการใช้งานอัลกอริธึม [ECDsa](./). วัตถุของคลาสนี้ควรที่จะจัดสรรเฉพาะผ่านฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือข้อผิดพลาดการตรวจสอบ. ให้หุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class ECDsa : public System::Security::Cryptography::AsymmetricAlgorithm
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | ปล่อยทรัพยากรทั้งหมด. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)() | สร้างการทำงานของอัลกอริธึม ECDSA เริ่มต้น. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [ECCurve](../eccurve/)\&) | สร้างการทำงานของอัลกอริธึม ECDSA เริ่มต้นพร้อมคีย์ที่สร้างใหม่บนโค้งที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [ECParameters](../ecparameters/)\&) | สร้างการทำงานของอัลกอริธึม ECDSA เริ่มต้นโดยใช้พารามิเตอร์ที่ระบุ. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [String](../../system/string/)\&) | สร้างการทำงานของอัลกอริธึม ECDSA ตามที่ระบุ. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | ปล่อยทรัพยากรที่เป็นของอ็อบเจ็กต์ปัจจุบัน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าด้วยค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าด้วยค่าใด ๆ รวมถึง NaN. |
| virtual [ECParameters](../ecparameters/) [ExportExplicitParameters](./exportexplicitparameters/)(**bool**) | ส่งออกพารามิเตอร์แบบชัดเจน. |
| virtual [ECParameters](../ecparameters/) [ExportParameters](./exportparameters/)(**bool**) | ส่งออกพารามิเตอร์ที่มีชื่อหรือแบบชัดเจน. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้ภายในเท่านั้น. |
| virtual void [FromXmlString](../asymmetricalgorithm/fromxmlstring/)([String](../../system/string/)) | อ่านพารามิเตอร์ของอัลกอริธึมจากสตริง XML. |
| virtual void [GenerateKey](./generatekey/)(const [ECCurve](../eccurve/)\&) | สร้างคู่คีย์สาธารณะ/ส่วนตัวใหม่สำหรับโค้งที่ระบุ. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | รับอัลกอริธึมการแลกเปลี่ยนคีย์ที่ใช้. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | รับขนาดคีย์. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | รับอาเรย์ของขนาดคีย์ที่อนุญาต. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | รับอัลกอริธึมลายเซ็นที่ใช้. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์ เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [ImportParameters](./importparameters/)(const [ECParameters](../ecparameters/)\&) | นำเข้าพารามิเตอร์ทั้งหมดจากโครงสร้างข้อมูล. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์แสดงเป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType เป็นอนาล็อกของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อคตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุตรวจสอบ [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | ตั้งค่าขนาดคีย์. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็นตัวชี้อ่อน (แทน shared) ทำให้สามารถสลับตัวชี้ในคอนเทนเนอร์เป็นโหมดอ่อน. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริธึมที่ระบุและลงลายเซ็นผลลัพธ์. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | คำนวณค่าแฮชของอาร์เรย์ข้อมูลที่ระบุโดยใช้แฮชอัลกอริธึมที่ระบุและลงลายเซ็นผลลัพธ์. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | คำนวณค่าแฮชของสตรีมไบนารีที่ระบุโดยใช้แฮชอัลกอริธึมที่ระบุและลงลายเซ็นผลลัพธ์. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | คำนวณลายเซ็นของค่าขาเข้าที่ระบุ. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| virtual [String](../../system/string/) [ToXmlString](../asymmetricalgorithm/toxmlstring/)(**bool**) | เขียนพารามิเตอร์ของอัลกอริธึมเป็นสตริง XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นคอนสตรัคต์ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุตรวจสอบ [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นค่าที่ถูกต้อง. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | ตรวจสอบว่าลายเซ็นของข้อมูลที่ระบุเป็นค่าที่ถูกต้อง. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | ตรวจสอบว่าลายเซ็นของสตรีมไบนารีที่ระบุเป็นค่าที่ถูกต้อง. |
| virtual **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) | ตรวจสอบลายเซ็นของข้อมูล. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบอ่อน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบอ่อน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [AsymmetricAlgorithm](../asymmetricalgorithm/)
* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)