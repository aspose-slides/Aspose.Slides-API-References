---
title: Object
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คลาสฐานที่ทำให้สามารถใช้เมธอดที่มีให้สำหรับคลาส System.Object ใน C# ได้ ทุกคลาสที่ไม่ใช่แบบง่ายที่ใช้ในสภาพแวดล้อมที่แปลควรสืบทอดจากคลาสนี้
type: docs
weight: 1132
url: /th/system/object/
---
## คลาส Object

Base class that enables using methods available for [System.Object](./) class in C#. All non-trivial classes used with translated environment should inherit it.

```cpp
class Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](./equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบค่าประเภทในสไตล์ C# |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# โดยถือว่า NaN สองค่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# โดยถือว่า NaN สองค่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | เช่นเมธอด C# [Object.GetHashCode()](./gethashcode/) ทำให้สามารถแฮชวัตถุที่กำหนดเองได้ |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | รับประเภทจริงของวัตถุ เป็นการจำลองการเรียก [System.Object.GetType()](./gettype/) ของ C# |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ จำลองการทำงานของตัวดำเนินการ 'is' ของ C# |
| void [Lock](./lock/)() | ทำงานเหมือนคำสั่ง lock() ของ C# ใช้โดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | เช่นเมธอด C# [Object.MemberwiseClone()](./memberwiseclone/) ทำให้สามารถทำสำเนาประเภทที่กำหนดเองได้ |
|  [Object](./object/)() | สร้างวัตถุและกำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](./object/)([Object](./) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงกำหนดวัตถุใหม่และเปิดให้คลาสย่อยคัดลอกได้ |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงกำหนดวัตถุใหม่และเปิดให้คลาสย่อยคัดลอกได้ |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กท์ค่าประเภทกับ nullptr |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | ความพิเศษของ [Object::ReferenceEquals](./referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | ความพิเศษของ [Object::ReferenceEquals](./referenceequals/) สำหรับกรณีสตริงหลายตัว |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | ตั้งค่าตัวแปรเทมเพลตตัวที่ n ให้เป็น weak pointer (แทน shared) เพื่อสลับโหมด pointer ในคอนเทนเนอร์ |
| int [SharedCount](./sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../string/) [ToString](./tostring/)() const | เช่นเมธอด C# [Object.ToString()](./tostring/) ทำให้สามารถแปลงวัตถุที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | จำลองการใช้ C# typeof([System.Object](./)) |
| void [Unlock](./unlock/)() | ทำงานคล้ายคำสั่ง lock() ของ C# เพื่อปลดล็อก ใช้โดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](./weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~Object](./~object/)() | ทำลายวัตถุและคืนค่าทรัพยากรภายในทั้งหมด |
## การกำหนดชนิด

| การกำหนดชนิด | คำอธิบาย |
| --- | --- |
| [ptr](./ptr/) | นามแฝงสำหรับประเภท smart pointer |
## หมายเหตุ

Alongside with methods available in C# [System.Object](./) class, it also enables support for some concepts specific for translated code environment. This includes reference counting used by smart pointer classes ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) and other services related to memory management, debug, etc.

Each [Object](./) has two reference counters: shared reference counter and weak reference counter. Weak reference counter is always stored in detached data structure rather than in [Object](./) itself which allows weak pointers overlive referenced object. Smart reference counter is stored either in object itself or in same detached structure, depending on ENABLE_EXTERNAL_REFCOUNT macro state. By default, it is enabled in debug builds and disabled in release builds. If smart pointer counter is stored in object itself, detached data structure is created only if weak pointers to object exist. Otherwise, it is created alongside with object itself.

All smart pointers use these two reference counters and contribute to same and only ownership group.

If [Object](./) subclass is created on stack, no smart pointers to it may be created, otherwise there is a stack deletion issue.

This type can be allocated either in stack as value type or in heap using [System::MakeObject()](../makeobject/) function. Once the object is allocated, never mix up these two usecases: having [SmartPtr](../smartptr/) pointers onto stack-allocated objects is strictly prohibited. 
## ดูเพิ่ม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)