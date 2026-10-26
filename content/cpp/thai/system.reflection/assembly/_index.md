---
title: Assembly
second_title: "อ้างอิง API ของ Aspose.Slides สำหรับ C++"
description: "คลาส Reflection ที่อธิบายแอสเซมบลี การสนับสนุนมีจำกัดเนื่องจากกฎต่างกันอย่างมากระหว่าง C# และ C++ วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() ไม่ควรสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการ assert ผิดพลาด เสมอห่อคลาสนี้ในพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้ส่งต่อให้ฟังก์ชันเป็นอาร์กิวเมนต์."
type: docs
weight: 1
url: /th/system.reflection/assembly/
---
## คลาส Assembly

[Reflection](../) คลาสที่อธิบายแอสเซมบลี การสนับสนุนมีจำกัดเนื่องจากกฎแตกต่างอย่างมากระหว่าง C# และ C++. วัตถุของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการ assert ผิดพลาด เสมอห่อคลาสนี้ในพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้ส่งต่อให้ฟังก์ชันเป็นอาร์กิวเมนต์

```cpp
class Assembly : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
|  [Assembly](./assembly/)() | คอนสตรัคเตอร์. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่โดยที่ NaN สองค่าถูกถือว่าเท่ากัน ถึงแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่โดยที่ NaN สองค่าถูกถือว่าเท่ากัน ถึงแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [String](../../system/string/) [get_CodeBase](./get_codebase/)() const | รับไดเรกทอรีของแอสเซมบลีปัจจุบัน การสนับสนุนมีจำกัด. |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() const | รับชื่อเต็มของแอสเซมบลี. |
| virtual [String](../../system/string/) [get_Location](./get_location/)() const | รับตำแหน่งของแอสเซมบลี ยังไม่ได้ทำการติดตั้ง. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Assembly](./)\> [GetAssembly](./getassembly/)(const [TypeInfo](../../system/typeinfo/)\&) | รับแอสเซมบลีที่กำหนดประเภทเฉพาะ. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Assembly](./)\> [GetCallingAssembly](./getcallingassembly/)() | รับแอสเซมบลีที่เรียกใช้งาน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Assembly](./)\> [GetEntryAssembly](./getentryassembly/)() | รับแอสเซมบลี entry. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Assembly](./)\> [GetExecutingAssembly](./getexecutingassembly/)() | รับแอสเซมบลีที่กำลังทำงาน. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เหมือนกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ช่วยให้ทำแฮชของอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetManifestResourceNames](./getmanifestresourcenames/)() const | รับชื่อของทรัพยากร manifest. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetManifestResourceStream](./getmanifestresourcestream/)([String](../../system/string/)) const | รับสตรีมที่เชื่อมต่อกับทรัพยากร manifest. |
| virtual [SharedPtr](../../system/sharedptr/)\<[AssemblyName](../assemblyname/)\> [GetName](./getname/)() const | รับชื่อแอสเซมบลี. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เหมือนการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [ArrayPtr](../../system/arrayptr/)\<[System::TypeInfo](../../system/typeinfo/)\> [GetTypes](./gettypes/)() const | รับประเภทที่ประกาศโดยแอสเซมบลี. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เหมือนกับผู้ดำเนินการ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ช่วยให้ทำการโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย จริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรเลย จริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะแชร์) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และคืนค่า ควรไม่เรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) ช่วยให้แปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Reflection](../)
* ไลบรารี [Aspose.Slides](../../)