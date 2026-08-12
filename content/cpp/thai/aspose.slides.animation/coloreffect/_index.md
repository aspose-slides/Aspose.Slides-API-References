---
title: ColorEffect
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: เป็นตัวแทนของเอฟเฟกต์สีสำหรับพฤติกรรมแอนิเมชัน.
type: docs
weight: 79
url: /th/aspose.slides.animation/coloreffect/
---
## ColorEffect คลาส

Represents a color effect for an animation behavior.

```cpp
class ColorEffect : public Aspose::Slides::Animation::Behavior,
                    public Aspose::Slides::Animation::IColorEffect
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
|  [ColorEffect](./coloreffect/)() | สร้างอินสแตนซ์ใหม่. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยโดยสไตล์ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยโดยสไตล์ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | แสดงว่าพฤติกรรมแอนิเมชันถูกสะสมหรือไม่. อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | แสดงว่าพฤติกรรมแอนิเมชันปัจจุบันถูกรวมกับแอนิเมชันที่กำลังทำงานอื่น ๆ หรือไม่. อ่าน [BehaviorAdditiveType](../behavioradditivetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOffset](../icoloroffset/)\> [get_By](./get_by/)() override | บรรยายค่าการเลื่อนตำแหน่งสัมพัทธ์สำหรับแอนิเมชันสี. อ่าน [IColorOffset](../icoloroffset/). |
| [Aspose::Slides::Animation::ColorSpace](../colorspace/) [get_ColorSpace](./get_colorspace/)() override | แสดงพื้นที่สีของพฤติกรรม. อ่าน [Animation::ColorSpace](../colorspace/). |
| [ColorDirection](../colordirection/) [get_Direction](./get_direction/)() override | ระบุทิศทางการหมุนของเฉดสีรอบล้อสี. อ่าน [ColorDirection](../colordirection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_From](./get_from/)() override | ค่านี้ใช้ระบุสีเริ่มต้นของพฤติกรรม. อ่าน [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | แสดงคุณสมบัติของพฤติกรรม. อ่านอย่างเดียว [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | แสดงคุณสมบัติด้านเวลา สำหรับพฤติกรรมเอฟเฟกต์. อ่าน [ITiming](../itiming/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_To](./get_to/)() override | บรรยายสีผลลัพธ์สำหรับการเปลี่ยนสีของแอนิเมชัน. อ่าน [IColorFormat](../../aspose.slides/icolorformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เทียบเคียงกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของอ็อบเจกต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแปรรูปพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแปรรูปพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | แสดงว่าพฤติกรรมแอนิเมชันถูกสะสมหรือไม่. เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | แสดงว่าพฤติกรรมแอนิเมชันปัจจุบันถูกรวมกับแอนิเมชันที่กำลังทำงานอื่นหรือไม่. เขียน [BehaviorAdditiveType](../behavioradditivetype/). |
| void [set_By](./set_by/)([System::SharedPtr](../../system/sharedptr/)\<[IColorOffset](../icoloroffset/)\>) override | บรรยายค่าการเลื่อนตำแหน่งสัมพัทธ์สำหรับแอนิเมชันสี. เขียน [IColorOffset](../icoloroffset/). |
| void [set_ColorSpace](./set_colorspace/)([Aspose::Slides::Animation::ColorSpace](../colorspace/)) override | แสดงพื้นที่สีของพฤติกรรม. เขียน [Animation::ColorSpace](../colorspace/). |
| void [set_Direction](./set_direction/)([ColorDirection](../colordirection/)) override | ระบุทิศทางการหมุนของเฉดสีรอบล้อสี. เขียน [ColorDirection](../colordirection/). |
| void [set_From](./set_from/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | ค่านี้ใช้ระบุสีเริ่มต้นของพฤติกรรม. เขียน [IColorFormat](../../aspose.slides/icolorformat/). |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | แสดงคุณสมบัติด้านเวลา สำหรับพฤติกรรมเอฟเฟกต์. เขียน [ITiming](../itiming/). |
| void [set_To](./set_to/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | บรรยายสีผลลัพธ์สำหรับการเปลี่ยนสีของแอนิเมชัน. เขียน [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Behavior](../behavior/)
* คลาส [IColorEffect](../icoloreffect/)
* เนมสเปซ [Aspose::Slides::Animation](../)
* ไลบรารี [Aspose.Slides](../../)