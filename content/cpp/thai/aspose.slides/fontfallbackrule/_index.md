---
title: FontFallBackRule
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึงกฎการสำรองแบบอักษร
type: docs
weight: 937
url: /th/aspose.slides/fontfallbackrule/
---
## FontFallBackRule คลาส


Represents font fallback rule

```cpp
class FontFallBackRule : public Aspose::Slides::IFontFallBackRule
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [AddFallBackFonts](./addfallbackfonts/)([System::String](../../system/string/)) override | เพิ่มแบบอักษรใหม่ (s) ไปยังรายการ FallBack fonts. |
| void [AddFallBackFonts](./addfallbackfonts/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | เพิ่มแบบอักษรใหม่ไปยังรายการ FallBack fonts. |
| void [Clear](./clear/)() override | ลบแบบอักษรทั้งหมดออกจากรายการ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C#-style ที่โดยที่ค่า NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C#-style ที่โดยที่ค่า NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น. |
|  [FontFallBackRule](./fontfallbackrule/)(**uint32_t**, **uint32_t**, [System::String](../../system/string/)) | สร้างอินสแตนซ์ใหม่. |
|  [FontFallBackRule](./fontfallbackrule/)(**uint32_t**, **uint32_t**, [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | สร้างอินสแตนซ์ใหม่. |
| **int32_t** [get_Count](./get_count/)() override | รับจำนวนแบบอักษรที่กำหนดจริง ๆ สำหรับช่วงนี้ อ่านอย่างเดียว **int32_t**. |
| **uint32_t** [get_RangeEndIndex](./get_rangeendindex/)() override | รับดัชนีสุดท้ายของช่วงยูนิโค้ดต่อเนื่อง. |
| **uint32_t** [get_RangeStartIndex](./get_rangestartindex/)() override | รับดัชนีแรกของช่วงยูนิโค้ดต่อเนื่อง. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) override | รับชื่อแบบอักษรที่ดัชนีที่ระบุ. อ่านอย่างเดียว [IFontFallBackRule](../ifontfallbackrule/). |
| **int32_t** [IndexOf](./indexof/)([System::String](../../system/string/)) override | ส่งคืนดัชนีของกฎที่ระบุในคอลเลกชัน. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock() . เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้คลาสย่อยสามารถคัดลอกได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้คลาสย่อยสามารถคัดลอกได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแยกประเภทของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแยกประเภทของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| void [Remove](./remove/)([System::String](../../system/string/)) override | ลบการปรากฏครั้งแรกของฟอนต์ FallBack เฉพาะจากรายการ. |
| void [RemoveAt](./removeat/)(**int32_t**) override | ลบฟอนต์ FallBack ที่ดัชนีที่ระบุในรายการ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_RangeEndIndex](./set_rangeendindex/)(**uint32_t**) | รับดัชนีสุดท้ายของช่วงยูนิโค้ดต่อเนื่อง. |
| void [set_RangeStartIndex](./set_rangestartindex/)(**uint32_t**) | รับดัชนีแรกของช่วงยูนิโค้ดต่อเนื่อง. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [ToArray](./toarray/)() override | สร้างและส่งคืนอาเรย์ที่มี FallBack fonts ทั้งหมดสำหรับกฎนี้. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | สร้างและส่งคืนอาเรย์ที่มี FallBack fonts ทั้งหมดจากช่วงที่ระบุในรายการ. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock() . เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [IFontFallBackRule](../ifontfallbackrule/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)