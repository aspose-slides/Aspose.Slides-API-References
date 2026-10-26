---
title: IEquatable
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "กำหนดเมธอดที่ใช้ตรวจสอบความเท่ากันของวัตถุสองตัว วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของชนิดนี้บนสแต็คหรือด้วยตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบเงื่อนไขล้มเหลว ควรห่อคลาสตนี้ด้วยตัวชี้ System::SmartPtr แล้วใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอากิวเมนต์ให้ฟังก์ชันต่าง ๆ"
type: docs
weight: 976
url: /th/system/iequatable/
---
## IEquatable คลาส

กำหนดเมธอดที่ใช้ตรวจสอบความเท่ากันของวัตถุสองตัว วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแต็คหรือด้วยตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบเงื่อนไขล้มเหลว ควรห่อคลาสตนี้ด้วยตัวชี้ [System::SmartPtr](../smartptr/) แล้วใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอากิวเมนต์ให้ฟังก์ชันต่าง ๆ

```cpp
template<typename T>class IEquatable : public virtual System::Object
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของวัตถุที่เปรียบเทียบ |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](./equals/)(T) | กำหนดว่าวัตถุปัจจุบันและวัตถุที่ระบุเท่ากันหรือไม่ |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบวัตถุโดยใช้การทำงานของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยของ C#-style ซึ่ง NaN สองค่าถูกพิจารณาเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยของ C#-style ซึ่ง NaN สองค่าถูกพิจารณาเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/) เปิดใช้งานการแฮชของวัตถุที่กำหนดเอง |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทจริงของวัตถุ คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/) |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../object/lock/)() | ทำการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/) เปิดใช้งานการทำสำเนาชนิดกำหนดเอง |
|  [Object](../object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นวัตถุใหม่และทำให้ซับคลาสสามารถสำเนาได้ |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นวัตถุใหม่และทำให้ซับคลาสสามารถสำเนาได้ |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงค่าชนิดค่าออบเจกต์กับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงหลายค่า |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าพารามิเตอร์เทมเพลตตัวที่ n ให้เป็น weak pointer (แทน shared) อนุญาตให้สลับตัวชี้ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../string/) [ToString](../object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../object/tostring/) เปิดใช้งานการแปลงวัตถุกำหนดเองเป็นสตริง |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำการสร้างโครงสร้าง C# typeof([System.Object](../object/)) |
| void [Unlock](../object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~Object](../object/~object/)() | ทำลายวัตถุ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)