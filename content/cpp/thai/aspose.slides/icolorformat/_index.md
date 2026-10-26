---
title: IColorFormat
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทนสีที่ใช้ในงานนำเสนอ.
type: docs
weight: 1691
url: /th/aspose.slides/icolorformat/
---
## IColorFormat คลาส


แทนสีที่ใช้ในงานนำเสนอ.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | คัดลอกรูปแบบสีจาก \"color\". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนแบบจุดลอยของ C# ที่ NaN สองค่าถือเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตรงไหนเลย รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนแบบจุดลอยของ C# ที่ NaN สองค่าถือเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตรงไหนเลย รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| virtual **uint8_t** [get_B](./get_b/)() | คืนค่าคอมโพแนนต์สีน้ำเงินของสี การแปลงสีทั้งหมดจะถูกละเลย อ่าน **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | คืนค่าสีที่ได้ (พร้อมการแปลงสีทั้งหมดที่ถูกนำมาใช้) ตั้งค่าสี RGB และล้างการแปลงสีทั้งหมด อ่าน [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | คืนการดำเนินการแปลงสีที่ถูกนำไปใช้กับสีที่ตำแหน่งที่ระบุ อ่าน/เขียน [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | คืนคอลเลกชันของการแปลงสีที่ถูกนำไปใช้กับสี อ่านอย่างเดียว [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | คืนวิธีการกำหนดสี อ่าน [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | คืนค่าคอมโพแนนต์สีน้ำเงินของสี การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | คืนค่าคอมโพแนนต์สีเขียวของสี การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | คืนค่าคอมโพแนนต์สีแดงของสี การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | คืนค่าคอมโพแนนต์สีเขียวของสี การแปลงสีทั้งหมดจะถูกละเลย อ่าน **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | คืนค่าคอมโพแนนต์สีสีสันของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | คืนค่าคอมโพแนนต์ความสว่างของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | คืนค่าสีที่ตั้งล่วงหน้า อ่าน [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | คืนค่าคอมโพแนนต์สีแดงของสี การแปลงสีทั้งหมดจะถูกละเลย อ่าน **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | คืนค่าคอมโพแนนต์ความอิ่มตัวของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | คืนสีที่ระบุโดยโครงการสี อ่าน [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | คืนสีที่ระบุโดยตารางสีระบบ อ่าน [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นฟังก์ชันคล้ายกับ C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถทำแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นฟังก์ชันคล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนส์ของประเภทที่อธิบายโดย targetType เป็นฟังก์ชันคล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นฟังก์ชันคล้ายกับ C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับการอ้างอิงแบบแชร์โดยค่าที่ระบุ. |
| virtual void [set_B](./set_b/)(**uint8_t**) | ตั้งค่าคอมโพแนนต์สีน้ำเงินของสี การแปลงสีทั้งหมดจะถูกละเลย เขียน **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | คืนค่าสีที่ได้ (พร้อมการแปลงสีทั้งหมด) ตั้งค่าสี RGB และล้างการแปลงสีทั้งหมด เขียน [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | ตั้งการดำเนินการแปลงสีที่นำไปใช้กับสีที่ตำแหน่งที่ระบุ อ่าน/เขียน [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | ตั้งวิธีการกำหนดสี เขียน [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | ตั้งค่าคอมโพแนนต์สีน้ำเงินของสี การแปลงสีทั้งหมดจะถูกละเลย เขียน **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | ตั้งค่าคอมโพแนนต์สีเขียวของสี การแปลงสีทั้งหมดจะถูกละเลย เขียน **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | ตั้งค่าคอมโพแนนต์สีแดงของสี การแปลงสีทั้งหมดจะถูกละเลย เขียน **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | ตั้งค่าคอมโพแนนต์สีเขียวของสี การแปลงสีทั้งหมดจะถูกละเลย เขียน **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | ตั้งค่าคอมโพแนนต์สีสีสันของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย เขียน **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | ตั้งค่าคอมโพแนนต์ความสว่างของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย เขียน **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | ตั้งค่าสีที่ตั้งล่วงหน้า เขียน [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | ตั้งค่าคอมโพแนนต์สีแดงของสี การแปลงสีทั้งหมดจะถูกละเลย เขียน **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | ตั้งค่าคอมโพแนนต์ความอิ่มตัวของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย เขียน **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | ตั้งสีที่ระบุโดยโครงการสี เขียน [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | ตั้งสีที่ระบุโดยตารางสีระบบ เขียน [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับการอ้างอิงแบบแชร์และคืนค่า ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | คืนค่า [System::String](../../system/string/) ที่แสดงรูปแบบสีปัจจุบัน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นฟังก์ชันคล้ายกับ C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IFillParamSource](../ifillparamsource/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)