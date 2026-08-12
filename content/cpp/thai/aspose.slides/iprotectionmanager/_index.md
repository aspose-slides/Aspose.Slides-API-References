---
title: IProtectionManager
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: การจัดการการป้องกันการนำเสนอด้วยรหัสผ่าน.
type: docs
weight: 3459
url: /th/aspose.slides/iprotectionmanager/
---
## IProtectionManager คลาส

[Presentation](../presentation/) การจัดการการป้องกันด้วยรหัสผ่าน.

```cpp
class IProtectionManager : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) | กำหนดว่าการนำเสนอถูกป้องกันด้วยรหัสผ่านสำหรับการแก้ไขหรือไม่. |
| virtual void [Encrypt](./encrypt/)([System::String](../../system/string/)) | เข้ารหัส [Presentation](../presentation/) ด้วยรหัสผ่านที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับภายในเท่านั้น. |
| virtual **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() | คุณสมบัตินี้มีความหมายเมื่อการนำเสนอถูกป้องกันด้วยรหัสผ่าน หากเป็น true แล้วคุณสมบัติของเอกสารจะถูกเข้ารหัสในไฟล์การนำเสนอ หากเป็น false แล้วคุณสมบัติของเอกสารจะเป็นสาธารณะขณะที่การนำเสนอถูกเข้ารหัส อ่าน **bool**. |
| virtual [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() | ส่งคืนรหัสผ่านการเข้ารหัส. อ่านอย่างเดียว [System::String](../../system/string/). |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() | รับค่าแสดงว่าอินสแตนซ์นี้ถูกเข้ารหัสหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() | คุณสมบัตินี้มีความหมายเมื่อไฟล์การนำเสนอถูกป้องกันด้วยรหัสผ่านและคุณสมบัติของเอกสารของไฟล์นี้เป็นสาธารณะ ค่า true หมายถึงโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์การนำเสนอที่เข้ารหัสโดยไม่ใช้รหัสผ่าน ค่า false หมายถึงโหลดการนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง ไม่ได้โหลดเฉพาะคุณสมบัติของเอกสาร หากการนำเสนอไม่ได้ถูกเข้ารหัสค่าคุณสมบัติจะแสดงเป็น false เสมอ หากคุณสมบัติของเอกสารของไฟล์ที่เข้ารหัสไม่เป็นสาธารณะค่าคุณสมบัติจะแสดงเป็น false เสมอ หาก PresentationEx.EncryptDocumentProperties เป็น true ค่าคุณสมบัติ IsOnlyDocumentPropertiesLoaded จะเป็น false เสมอ อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_IsWriteProtected](./get_iswriteprotected/)() | รับค่าแสดงว่าการนำเสนอนี้ถูกป้องกันการเขียนหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() | รับคำแนะนำแบบอ่านอย่างเดียว. อ่าน **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการสร้างแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. อนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. อนาล็อกของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาชนิดที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์แบบค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [RemoveEncryption](./removeencryption/)() | ลบการเข้ารหัส. |
| virtual void [RemoveWriteProtection](./removewriteprotection/)() | ลบการป้องกันการเขียนสำหรับการนำเสนอนี้. |
| virtual void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) | คุณสมบัตินี้มีความหมายเมื่อการนำเสนอถูกป้องกันด้วยรหัสผ่าน หากเป็น true แล้วคุณสมบัติของเอกสารจะถูกเข้ารหัสในไฟล์การนำเสนอ หากเป็น false แล้วคุณสมบัติของเอกสารจะเป็นสาธารณะขณะที่การนำเสนอถูกเข้ารหัส เขียน **bool**. |
| virtual void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) | ตั้งค่าคำแนะนำแบบอ่านอย่างเดียว เขียน **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| virtual void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) | ตั้งค่าการป้องกันการเขียนสำหรับการนำเสนอนี้ด้วยรหัสผ่านที่ระบุ. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)