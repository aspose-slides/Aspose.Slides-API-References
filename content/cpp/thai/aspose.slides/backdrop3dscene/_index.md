---
title: Backdrop3DScene
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: กำหนดระนาบที่ใช้ในการประยุกต์ผลแบบต่าง ๆ เช่น แสงเรืองแสงและเงา โดยสัมพันธ์กับรูปร่างที่กำลังประยุกต์ผลอยู่.
type: docs
weight: 92
url: /th/aspose.slides/backdrop3dscene/
---
## Backdrop3DScene คลาส


Defines a plane in which effects, such as glow and shadow, are applied in relation to the shape they are being applied to.

```cpp
class Backdrop3DScene : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IBackdrop3DScene
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_AnchorPoint](./get_anchorpoint/)() override | ส่งคืนจุดในพื้นที่ 3 มิติ จุดนี้เป็นจุดที่ยึดระนาบแบ็คดรอปในอากาศ. จุด 3 มิตินี้แสดงด้วยอาร์เรย์ของค่า float 3 ค่า ซึ่งกำหนดพิกัด X, Y และ Z. อ่าน **float**[]. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_NormalVector](./get_normalvector/)() override | ส่งคืนเวกเตอร์ปกติ ให้ชัดเจนกว่านั้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากกับพื้นผิวของระนาบแบ็คดรอป. เวกเตอร์แสดงด้วยอาร์เรย์ของค่า float 3 ค่า ซึ่งกำหนดพิกัด X, Y และ Z. อ่าน **float**[]. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | ส่งคืนอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | ส่งคืนพาเรนต์ [IPresentationComponent](../ipresentationcomponent/). อ่านอย่างเดียว [IPresentationComponent](../ipresentationcomponent/). |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_UpVector](./get_upvector/)() override | ส่งคืนเวกเตอร์ที่แสดงทิศขึ้น ให้ชัดเจนกว่านั้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงทิศขึ้นสัมพันธ์กับพื้นผิวของระนาบแบ็คดรอป. เวกเตอร์แสดงด้วยอาร์เรย์ของค่า float 3 ค่า ซึ่งกำหนดพิกัด X, Y และ Z. อ่าน **float**[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | ส่งคืนค่าแฮชโค้ด. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เทียบเท่าการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เทียบเท่าตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่ากับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การมอบหมาย. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| void [set_AnchorPoint](./set_anchorpoint/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | ตั้งค่าจุดในพื้นที่ 3 มิติ จุดนี้เป็นจุดที่ยึดระนาบแบ็คดรอปในอากาศ. จุด 3 มิติแสดงด้วยอาร์เรย์ของค่า float 3 ค่า ซึ่งกำหนดพิกัด X, Y และ Z. เขียน **float**[]. |
| void [set_NormalVector](./set_normalvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | ตั้งค่าเวกเตอร์ปกติ ให้ชัดเจนกว่านั้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากกับพื้นผิวของระนาบแบ็คดรอป. เวกเตอร์แสดงด้วยอาร์เรย์ของค่า float 3 ค่า ซึ่งกำหนดพิกัด X, Y และ Z. เขียน **float**[]. |
| void [set_UpVector](./set_upvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | ตั้งค่าเวกเตอร์ที่แสดงทิศขึ้น ให้ชัดเจนกว่านั้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงทิศขึ้นสัมพันธ์กับพื้นผิวของระนาบแบ็คดรอป. เวกเตอร์แสดงด้วยอาร์เรย์ของค่า float 3 ค่า ซึ่งกำหนดพิกัด X, Y และ Z. เขียน **float**[]. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และส่งค่ากลับ. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject/)
* คลาส [IBackdrop3DScene](../ibackdrop3dscene/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)