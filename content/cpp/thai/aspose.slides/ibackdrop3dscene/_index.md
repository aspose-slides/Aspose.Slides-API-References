---
title: IBackdrop3DScene
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดระนาบที่เอฟเฟกต์ เช่น แสงเรืองแสงและเงา ถูกนำไปใช้สัมพันธ์กับรูปร่างที่กำลังนำไปใช้
type: docs
weight: 1392
url: /th/aspose.slides/ibackdrop3dscene/
---
## IBackdrop3DScene คลาส

กำหนดระนาบที่เอฟเฟกต์เช่นเรืองแสงและเงาถูกนำไปใช้สัมพันธ์กับรูปร่างที่กำลังถูกนำไปใช้

```cpp
class IBackdrop3DScene : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้รูปแบบของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | เลียนแบบการเปรียบเทียบ floating point แบบ C#-style ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | เลียนแบบการเปรียบเทียบ floating point แบบ C#-style ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_AnchorPoint](./get_anchorpoint/)() | ส่งคืนจุดในพื้นที่ 3 มิติ จุดนี้เป็นจุดในอวกาศที่ทำหน้าที่เป็นจุดยึดของพื้นหลังของระนาบ 3D จุด 3 มิติแสดงโดยอาร์เรย์ของค่า **float** 3 ตัวที่กำหนดพิกัด X, Y และ Z อ่าน **float**[]. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_NormalVector](./get_normalvector/)() | ส่งคืนเวกเตอร์ปกติ เพื่อความชัดเจน แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากต่อหน้า ของพื้นหลังระนาบ เวกเตอร์แสดงโดยอาร์เรย์ของค่า **float** 3 ตัวที่กำหนดพิกัด X, Y และ Z อ่าน **float**[]. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_UpVector](./get_upvector/)() | ส่งคืนเวกเตอร์ที่แทนการขึ้นไป เพื่อความชัดเจน แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงการขึ้นในทิศทางสัมพันธ์กับหน้า ของพื้นหลังระนาบ เวกเตอร์แสดงโดยอาร์เรย์ของค่า **float** 3 ตัวที่กำหนดพิกัด X, Y และ Z อ่าน **float**[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่สัมพันธ์กับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเวอร์ชันคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของวัตถุที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเวอร์ชันคล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การมอบหมายค่า. จริงๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์โดยค่าที่ระบุ. |
| virtual void [set_AnchorPoint](./set_anchorpoint/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | กำหนดจุดในพื้นที่ 3 มิติ จุดนี้เป็นจุดที่ยึดพื้นหลังระนาบ 3D จุด 3 มิติแสดงโดยอาร์เรย์ของค่า **float** 3 ตัวที่กำหนดพิกัด X, Y และ Z เขียน **float**[]. |
| virtual void [set_NormalVector](./set_normalvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | กำหนดเวกเตอร์ปกติ เพื่อความชัดเจน แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากต่อหน้า ของพื้นหลังระนาบ เวกเตอร์แสดงโดยอาร์เรย์ของค่า **float** 3 ตัวที่กำหนดพิกัด X, Y และ Z เขียน **float**[]. |
| virtual void [set_UpVector](./set_upvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | กำหนดเวกเตอร์ที่แทนการขึ้นไป เพื่อความชัดเจน แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงการขึ้นในทิศทางสัมพันธ์กับหน้า ของพื้นหลังระนาบ เวกเตอร์แสดงโดยอาร์เรย์ของค่า **float** 3 ตัวที่กำหนดพิกัด X, Y และ Z เขียน **float**[]. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared). อนุญาตเปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบแชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเวอร์ชันคล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)