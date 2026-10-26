---
title: CompareInfo
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "ทำการเปรียบเทียบสตริงโดยคำนึงถึงวัฒนธรรม. วัตถุของคลาสนี้ควรได้รับการจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject(). ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดในระหว่างรันไทม์และ/หรือการยืนยันข้อผิดพลาด. ควรหุ้มคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 40
url: /th/system.globalization/compareinfo/
---
## คลาส CompareInfo

ทำการเปรียบเทียบสตริงโดยคำนึงถึงวัฒนธรรม. วัตถุของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดในขณะรันไทม์และ/หรือการยืนยันข้อผิดพลาด. ควรหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
class CompareInfo : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | เปรียบเทียบสตริง. ยังไม่ได้ทำ. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | เปรียบเทียบสตริง. รองรับเฉพาะโหมด Ordinal และ OrdinalIgnoreCase. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | เปรียบเทียบส่วนหนึ่งของสตริงกับส่วนของสตริงที่สอง. ยังไม่ได้ทำ. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | เปรียบเทียบส่วนท้ายของสตริงกับส่วนท้ายของสตริงที่สองโดยใช้วิธีการเปรียบเทียบสตริง. ยังไม่ได้ทำ. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | เปรียบเทียบส่วนท้ายของสตริงกับส่วนท้ายของสตริงที่สอง. ยังไม่ได้ทำ. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | เปรียบเทียบส่วนหนึ่งของสตริงกับส่วนของสตริงที่สองโดยใช้วิธีการเปรียบเทียบสตริง. ยังไม่ได้ทำ. |
| [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | ข้อมูล RTTI. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตัวแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตัวแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| int [get_LCID](./get_lcid/)() const | รับค่า LCID ของวัฒนธรรมที่เชื่อมโยงกับตัวเปรียบเทียบ. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | รับชื่อของวัฒนธรรมที่เชื่อมโยงกับตัวเปรียบเทียบ. |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | รับข้อมูลเกี่ยวกับรุ่นการเรียงลำดับ. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | รับ [CompareInfo](./) ที่เชื่อมโยงกับวัฒนธรรมที่ระบุและใช้วิธีการเปรียบเทียบสตริงใน assembly ที่ระบุ. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | รับ [CompareInfo](./) ที่เชื่อมโยงกับวัฒนธรรมที่ระบุและใช้วิธีการเปรียบเทียบสตริงใน assembly ที่ระบุ. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | รับ [CompareInfo](./) ที่เชื่อมโยงกับวัฒนธรรมที่ระบุ. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | รับ [CompareInfo](./) ที่เชื่อมโยงกับวัฒนธรรมที่ระบุ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | รับค่า hash code ของสตริงตามตัวเลือกการเปรียบเทียบที่ระบุ. |
| int [GetHashCode](./gethashcode/)() const override | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการสร้าง hash ของวัตถุที่กำหนดเอง. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | รับวัตถุ [SortKey](../sortkey/) สำหรับสตริงที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่ระบุ. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | รับวัตถุ [SortKey](../sortkey/) สำหรับสตริงที่ระบุ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นคล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | ค้นหาสตริงย่อย. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | ค้นหาสตริงย่อย. รองรับเฉพาะโหมด Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | ค้นหาสตริงย่อย. รองรับเฉพาะโหมด Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | ค้นหาตัวอักษรที่ระบุ. รองรับเฉพาะโหมด Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | ค้นหาสตริงย่อย. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | ค้นหาตัวอักษรที่ระบุ. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | ค้นหาสตริงย่อย. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | ค้นหาตัวอักษรที่ระบุ. รองรับเฉพาะโหมด Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | ค้นหาตัวอักษรที่ระบุ. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | ค้นหาตัวอักษรที่ระบุ. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | ค้นหาสตริงย่อย. รองรับเฉพาะโหมด Ordinal. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | ค้นหาตัวอักษรที่ระบุ. รองรับเฉพาะโหมด Ordinal. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่ targetType ระบุ. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | ตรวจสอบว่าสตริงที่ระบุเริ่มต้นด้วยคำนำหน้าที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่กำหนด. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | ตรวจสอบว่าสตริงที่ระบุเริ่มต้นด้วยคำนำหน้าที่ระบุ. |
| static **bool** [IsSortable](./issortable/)(char16_t) | ตรวจสอบว่าตัวอักษรที่ระบุสามารถเรียงลำดับได้หรือไม่. |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | ตรวจสอบว่าสตริงที่ระบุสามารถเรียงลำดับได้หรือไม่. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | ตรวจสอบว่่าสตริงที่ระบุลงท้ายด้วยส่วนต่อท้ายที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่กำหนด. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | ตรวจสอบว่่าสตริงที่ระบุลงท้ายด้วยส่วนต่อท้ายที่ระบุ. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของสตริงย่อยที่ระบุ. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของสตริงย่อยที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่กำหนด. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของตัวอักษรที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่กำหนด. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของสตริงที่ระบุ. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของสตริงที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่กำหนด. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของตัวอักษรที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่กำหนด. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของสตริงที่ระบุ. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของตัวอักษรที่ระบุ. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของสตริงที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่กำหนด. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของตัวอักษรที่ระบุโดยใช้ตัวเลือกการเปรียบเทียบที่กำหนด. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของตัวอักษรที่ระบุ. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | ค้นหาการเกิดขึ้นครั้งสุดท้ายของตัวอักษรที่ระบุ. |
| void [Lock](../../system/object/lock/)() | จำลองการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาชนิดที่กำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ ไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์แบบ value กับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำ specialize ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำ specialize ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | จำลองโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | จำลองการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)