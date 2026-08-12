---
title: TripleDESManaged
second_title: "เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++"
description: "การดำเนินการ TripleDES แบบจัดการ (Managed) รองรับเฉพาะโหมด ECB และ CFB พร้อมการเติม None และโหมด CBC พร้อมการเติม None, Zeros และ PKCS7 เท่านั้น วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาทำงานและ/หรือการตรวจสอบข้อผิดพลาด เสมอห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 690
url: /th/system.security.cryptography/tripledesmanaged/
---
## TripleDESManaged คลาส

Managed [TripleDES](../tripledes/) implementation. Only supports ECB and CFB modes with None padding and CBC mode with None, Zeros and PKCS7 paddings. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TripleDESManaged : public System::Security::Cryptography::TripleDES
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ของอัลกอริทึม. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | สร้างอ็อบเจกต์ Decryptor ด้วยพารามิเตอร์ที่ระบุอย่างชัดเจน. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | สร้างอ็อบเจกต์ Decryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจกต์อัลกอริทึม. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | สร้างอ็อบเจกต์ Decryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจกต์อัลกอริทึม. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | สร้างอ็อบเจกต์ Encryptor ด้วยพารามิเตอร์ที่ระบุอย่างชัดเจน. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | สร้างอ็อบเจกต์ Encryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจกต์อัลกอริทึม. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | สร้างอ็อบเจกต์ Encryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจกต์อัลกอริทึม. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบค่าตามสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ NaN สองค่าเทียบเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ NaN สองค่าเทียบเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| void [GenerateIV](./generateiv/)() override | สร้างค่าเริ่มต้นแบบสุ่มและเก็บไว้ในภายในของอัลกอริทึม. |
| void [GenerateKey](./generatekey/)() override | สร้างคีย์แบบสุ่มและเก็บไว้ในภายในของอัลกอริทึม. |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | รับขนาดบล็อกของการดำเนินการเข้ารหัส. |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | รับขนาดฟีดแบ็กของการดำเนินการเข้ารหัส. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | รับค่าเริ่มต้นของการดำเนินการเข้ารหัส. สร้างใหม่หากยังไม่ได้สร้าง. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | รับคีย์ของการดำเนินการเข้ารหัส. สร้างใหม่หากยังไม่ได้สร้าง. |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | รับขนาดคีย์ของการดำเนินการเข้ารหัส. |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | รับโหมดของการดำเนินการเข้ารหัส. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | รับการเติมของการดำเนินการเข้ารหัส. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจกต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. คล้ายตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทแบบกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์แบบค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงแชร์ลงตามค่าที่ระบุ. |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | ตั้งค่าขนาดบล็อกของการดำเนินการเข้ารหัส. |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | ตั้งค่าขนาดฟีดแบ็กของการดำเนินการเข้ารหัส. |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ตั้งค่าค่าเริ่มต้นของการดำเนินการเข้ารหัส. |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ตั้งค่าคีย์ของการดำเนินการเข้ารหัส. |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | ตั้งค่าขนาดคีย์ของการดำเนินการเข้ารหัส. |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | ตั้งค่าโหมดของการดำเนินการเข้ารหัส. |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | ตั้งค่าการเติมของการดำเนินการเข้ารหัส. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงแชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงแชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์แบบกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น construct typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | ตรวจสอบว่าขนาดคีย์ถูกต้องหรือไม่. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยทุกโครงสร้างข้อมูลภายใน. |

## ดูเพิ่มเติม

* คลาส [TripleDES](../tripledes/)
* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)