---
title: ProtectionManager
second_title: Aspose.Slides สำหรับ API ของ C++
description: การจัดการการป้องกันรหัสผ่านของการนำเสนอ
type: docs
weight: 4915
url: /th/aspose.slides/protectionmanager/
---
## ProtectionManager คลาส

[Presentation](../presentation/) การจัดการการป้องกันรหัสผ่าน.

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | กำหนดว่าการนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อแก้ไขหรือไม่ |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | เข้ารหัส [Presentation](../presentation/) ด้วยรหัสผ่านที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบค่าที่เก็บโดยค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | property นี้มีความหมายเมื่อการนำเสนอถูกป้องกันด้วยรหัสผ่าน หากเป็น true แล้วคุณสมบัติของเอกสารจะถูกเข้ารหัสในไฟล์การนำเสนอ หากเป็น false แล้วคุณสมบัติของเอกสารจะเป็นสาธารณะขณะการนำเสนอถูกเข้ารหัส อ่าน **bool** |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | รับรหัสผ่านที่ใช้สำหรับการเข้ารหัสการนำเสนอ อ่านอย่างเดียว [System::String](../../system/string/) |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | รับค่าที่บ่งบอกว่าตัวอย่างนี้ถูกเข้ารหัสหรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | property นี้มีความหมายเมื่อไฟล์การนำเสนอถูกป้องกันด้วยรหัสผ่านและคุณสมบัติของเอกสารในไฟล์นี้เป็นสาธารณะ ค่า true หมายความว่าจะโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์การนำเสนอที่เข้ารหัสโดยไม่ต้องใช้รหัสผ่าน ค่า false หมายความว่าจะโหลดการนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง ไม่ได้โหลดเฉพาะคุณสมบัติของเอกสาร หากการนำเสนอไม่ได้ถูกเข้ารหัส property นี้จะเป็น false เสมอ หากคุณสมบัติของเอกสารในไฟล์ที่เข้ารหัสไม่ได้เป็นสาธารณะ property นี้จะเป็น false เสมอ หาก Presentation.EncryptDocumentProperties เป็น true แล้วค่า IsOnlyDocumentPropertiesLoaded จะเป็น false เสมอ อ่านอย่างเดียว **bool** |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | รับค่าที่บ่งบอกว่าการนำเสนอนี้ถูกป้องกันการเขียนหรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | รับคำแนะนำอ่านอย่างเดียว อ่าน **bool** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ตรงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์แบบกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ ตรงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ ตรงกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | จำลองการใช้คำสั่ง lock() ของ C# การล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ตรงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงระหว่างอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | ความพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | ความพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่ใช้ร่วมโดยค่าที่ระบุ |
| void [RemoveEncryption](./removeencryption/)() override | ลบการเข้ารหัส |
| void [RemoveWriteProtection](./removewriteprotection/)() override | ลบการป้องกันการเขียนสำหรับการนำเสนอนี้ |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | property นี้มีความหมายเมื่อการนำเสนอถูกป้องกันด้วยรหัสผ่าน หากเป็น true แล้วคุณสมบัติของเอกสารจะถูกเข้ารหัสในไฟล์การนำเสนอ หากเป็น false แล้วคุณสมบัติของเอกสารจะเป็นสาธารณะขณะการนำเสนอถูกเข้ารหัส เขียน **bool** |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | ตั้งคำแนะนำอ่านอย่างเดียว เขียน **bool** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) อนุญาตให้สลับพอยท์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | ตั้งค่าการป้องกันการเขียนสำหรับการนำเสนอด้วยรหัสผ่านที่ระบุ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่ใช้ร่วม ไม่ควรเรียกโดยตรง ให้ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่ใช้ร่วมและคืนค่า ไม่ควรเรียกโดยตรง ให้ใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ตรงกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | จำลองการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | จำลองการปลดล็อกคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ให้ใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* Class [IProtectionManager](../iprotectionmanager/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)