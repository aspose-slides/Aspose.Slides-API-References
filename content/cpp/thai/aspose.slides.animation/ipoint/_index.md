---
title: IPoint
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงจุดแอนิเมชัน.
type: docs
weight: 313
url: /th/aspose.slides.animation/ipoint/
---
## IPoint คลาส

แสดงจุดแอนิเมชัน.

```cpp
class IPoint : public virtual System::Object
```

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้แนวทางการทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าตัวเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าตัวเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการภายในเท่านั้น. |
| virtual [System::String](../../system/string/) [get_Formula](./get_formula/)() | สูตรภายในค่า, from, to, by attribute สามารถประกอบด้วยสิ่งต่อไปนี้: Standard arithmetic operators: \\uFFFD+\\uFFFD, \\uFFFD-\\uFFFD, \\uFFFD*\\uFFFD, \\uFFFD/\\uFFFD, \\uFFFD^\\uFFFD, \\uFFFD\\uFFFD (mod) Constants: \\uFFFDpi\\uFFFD \\uFFFDe\\uFFFD Conditional operators: \\uFFFDabs\\uFFFD, \\uFFFDmin\\uFFFD, \\uFFFDmax\\uFFFD, \\uFFFD?\\uFFFD (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: \\uFFFDsin()\\uFFFD, \\uFFFDcos()\\uFFFD, \\uFFFDtan()\\uFFFD, \\uFFFDasin()\\uFFFD, \\uFFFDacos()\\uFFFD, \\uFFFDatan()\\uFFFD Natural logarithm \\uFFFDln()\\uFFFD Property references (host supported properties) |
| virtual **float** [get_Time](./get_time/)() | แทนค่าช่วงเวลา. อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() | แทนค่าจุด. มีได้แค่: bool, [ColorFormat](../../aspose.slides/colorformat/), float, int, string. อ่าน [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้การแฮชอ็อบเจกต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจกต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดให้โคลนประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาของซับคลาสได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาของซับคลาสได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์แบบค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การปรับใช้พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การปรับใช้พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_Formula](./set_formula/)([System::String](../../system/string/)) | สูตรภายในค่า, from, to, by attribute สามารถประกอบด้วยสิ่งต่อไปนี้: Standard arithmetic operators: \\uFFFD+\\uFFFD, \\uFFFD-\\uFFFD, \\uFFFD*\\uFFFD, \\uFFFD/\\uFFFD, \\uFFFD^\\uFFFD, \\uFFFD\\uFFFD (mod) Constants: \\uFFFDpi\\uFFFD \\uFFFDe\\uFFFD Conditional operators: \\uFFFDabs\\uFFFD, \\uFFFDmin\\uFFFD, \\uFFFDmax\\uFFFD, \\uFFFD?\\uFFFD (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: \\uFFFDsin()\\uFFFD, \\uFFFDcos()\\uFFFD, \\uFFFDtan()\\uFFFD, \\uFFFDasin()\\uFFFD, \\uFFFDacos()\\uFFFD, \\uFFFDatan()\\uFFFD Natural logarithm \\uFFFDln()\\uFFFD Property references (host supported properties) |
| virtual void [set_Time](./set_time/)(**float**) | แทนค่าช่วงเวลา. เขียน **float**. |
| virtual void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | แทนค่าจุด. มีได้แค่: bool, [ColorFormat](../../aspose.slides/colorformat/), float, int, string. เขียน [System::Object](../../system/object/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์แม่แบบที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดให้แปลงอ็อบเจกต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยทรัพยากรโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides::Animation](../)
* ไลบรารี [Aspose.Slides](../../)