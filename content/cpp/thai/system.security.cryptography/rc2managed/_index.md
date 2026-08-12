---
title: RC2Managed
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "อัลกอริธึม RC2 ที่จัดการ รองรับโหมดการเข้ารหัส ECB, CFB และ CBC เท่านั้น ควรสร้างอ็อบเจ็กต์ของคลาสนี้โดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบไม่สำเร็จ ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 378
url: /th/system.security.cryptography/rc2managed/
---
## คลาส RC2Managed

อัลกอริธึม [RC2](../rc2/) ที่จัดการ. รองรับโหมดการเข้ารหัส ECB, CFB และ CBC เท่านั้น. วัตถุของคลาสนี้ควรสร้างด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินส턴ซ์ของประเภทนี้บนสแตกหรือใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือความล้มเหลวของการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน.

```cpp
class RC2Managed : public System::Security::Cryptography::RC2
```

## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | สร้างอินส턴ซ์ของอัลกอริธึม |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | สร้างอ็อบเจ็กต์ดีคริปเตอร์ด้วยพารามิเตอร์ที่ระบุอย่างชัดเจน |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | สร้างอ็อบเจ็กต์ดีคริปเตอร์ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริธึม |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | สร้างอ็อบเจ็กต์ดีคริปเตอร์ด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริธึม |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | สร้างอ็อบเจ็กต์เข้ารหัสด้วยพารามิเตอร์ที่ระบุอย่างชัดเจน |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | สร้างอ็อบเจ็กต์เข้ารหัสด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริธึม |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | สร้างอ็อบเจ็กต์เข้ารหัสด้วยพารามิเตอร์ที่กำหนดโดยอ็อบเจ็กต์อัลกอริธึม |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ชนิดอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่าตามสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงตามสไตล์ของ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริง double ตามสไตล์ของ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| void [GenerateIV](./generateiv/)() override | สร้างค่าเริ่มต้นแบบสุ่มและบันทึกลงในภายในของอัลกอริธึม |
| void [GenerateKey](./generatekey/)() override | สร้างคีย์แบบสุ่มและบันทึกลงในภายในของอัลกอริธึม |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | ดึงขนาดบล็อกของการทำงานเข้ารหัส |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | ดึงขนาดฟีดแบ็กของการทำงานเข้ารหัส |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | ดึงค่าเริ่มต้นของการทำงานเข้ารหัส หากยังไม่มีจะสร้างใหม่ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | ดึงคีย์ของการทำงานเข้ารหัส หากยังไม่มีจะสร้างใหม่ |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | ดึงขนาดคีย์ของการทำงานเข้ารหัส |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | ดึงโหมดของการทำงานเข้ารหัส |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | ดึงการเติมข้อมูลของการทำงานเข้ารหัส |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถสร้างแฮชของอ็อบเจ็กต์กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงชนิดจริงของอ็อบเจ็กต์ คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินส턴ซ์ของชนิดที่อธิบายโดย targetType คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์และกำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริงๆ เพียงกำหนดค่าอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงกำหนดค่าอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมตามค่าที่ระบุ |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | ตั้งค่าขนาดบล็อกของการทำงานเข้ารหัส |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | ตั้งค่าขนาดฟีดแบ็กของการทำงานเข้ารหัส |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ตั้งค่าค่าเริ่มต้นของการทำงานเข้ารหัส |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ตั้งค่าคีย์ของการทำงานเข้ารหัส |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | ตั้งค่าขนาดคีย์ของการทำงานเข้ารหัส |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | ตั้งค่าโหมดของการทำงานเข้ารหัส |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | ตั้งค่าการเติมข้อมูลของการทำงานเข้ารหัส |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง แต่ควรใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่าตัวนับ ไม่ควรเรียกโดยตรง แต่ควรใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | ตรวจสอบว่าขนาดคีย์เป็นค่าที่ถูกต้องหรือไม่ |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง แต่ควรใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง แต่ควรใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์และปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [RC2](../rc2/)
* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)