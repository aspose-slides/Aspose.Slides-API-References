---
title: RijndaelManaged
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "อัลกอริธึม Rijndael ที่จัดการโดย . สนับสนุนเฉพาะโหมด ECB และ CFB พร้อม padding None และโหมด CBC พร้อม padding None และ Zeros เท่านั้น วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือข้อผิดพลาดการยืนยันค่า ให้ห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 417
url: /th/system.security.cryptography/rijndaelmanaged/
---
## RijndaelManaged คลาส

Managed [Rijndael](../rijndael/) algorithm. Only supports ECB and CFB modes with None padding and CBC mode with None and Zeros paddings. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RijndaelManaged : public System::Security::Cryptography::Rijndael
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ของอัลกอริธึม |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | สร้างอ็อบเจ็กต์ decryptor ด้วยพารามิเตอร์ที่ระบุชัดเจน |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | สร้างอ็อบเจ็กต์ decryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริธึม |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | สร้างอ็อบเจ็กต์ decryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริธึม |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่ระบุชัดเจน |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริธึม |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | สร้างอ็อบเจ็กต์ encryptor ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริธึม |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตามสไตล์ C# ซึ่ง NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตามสไตล์ C# ซึ่ง NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| void [GenerateIV](./generateiv/)() override | สร้างค่าตั้งต้นแบบสุ่มและเก็บไว้ในส่วนภายในของอัลกอริธึม |
| void [GenerateKey](./generatekey/)() override | สร้างคีย์แบบสุ่มและเก็บไว้ในส่วนภายในของอัลกอริธึม |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | ดึงขนาดบล็อกของการดำเนินการเข้ารหัส |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | ดึงขนาดฟีดแบ็กของการดำเนินการเข้ารหัส |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | ดึงค่าตั้งต้นของการดำเนินการเข้ารหัส หากยังไม่มีจะสร้างใหม่ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | ดึงคีย์ของการดำเนินการเข้ารหัส หากยังไม่มีจะสร้างใหม่ |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | ดึงขนาดคีย์ของการดำเนินการเข้ารหัส |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | ดึงโหมดของการดำเนินการเข้ารหัส |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | ดึง padding ของการดำเนินการเข้ารหัส |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่สัมพันธ์กับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นฟังก์ชันที่คล้ายกับ [Object.GetHashCode()](../../system/object/gethashcode/) ของ C# ให้การแฮชอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจ็กต์ เป็นฟังก์ชันคล้าย [System.Object.GetType()](../../system/object/gettype/) ของ C# |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบเท่ากับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้อ็อบเจ็กต์ [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเมธอดคล้ายกับ [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# ให้การโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ กำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงกำหนดค่าอ็อบเจ็กต์ใหม่และอนุญาตการคัดลอกสำหรับซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงกำหนดค่าอ็อบเจ็กต์ใหม่และอนุญาตการคัดลอกสำหรับซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดนับอ้างอิงแบบแชร์ลงตามค่าที่ระบุ |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | ตั้งค่าขนาดบล็อกของการดำเนินการเข้ารหัส |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | ตั้งค่าขนาดฟีดแบ็กของการดำเนินการเข้ารหัส |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ตั้งค่าตั้งต้นของการดำเนินการเข้ารหัส |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ตั้งค่าคีย์ของการดำเนินการเข้ารหัส |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | ตั้งค่าขนาดคีย์ของการดำเนินการเข้ารหัส |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | ตั้งค่าโหมดของการดำเนินการเข้ารหัส |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | ตั้งค่า padding ของการดำเนินการเข้ารหัส |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตพารามิเตอร์ที่ n เป็น weak pointer (แทนการเป็น shared) ให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มนับอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเมธอดคล้าย [Object.ToString()](../../system/object/tostring/) ของ C# ให้การแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้อ็อบเจ็กต์ [LockContext](../../system/lockcontext/) |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | ตรวจสอบว่าขนาดคีย์เป็นค่าที่ถูกต้องหรือไม่ |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Rijndael](../rijndael/)
* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)