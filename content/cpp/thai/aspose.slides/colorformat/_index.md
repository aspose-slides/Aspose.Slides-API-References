---
title: ColorFormat
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: แสดงสีที่ใช้ในงานนำเสนอ.
type: docs
weight: 339
url: /th/aspose.slides/colorformat/
---
## ColorFormat คลาส

Represents a color used in a presentation.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## เมธอด

| Method | Description |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | คัดลอกรูปแบบสีจาก "color". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | ตรวจสอบความเท่าเทียมกับอ็อบเจ็กต์ที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่ NaN สองค่า ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| **uint8_t** [get_B](./get_b/)() override | คืนค่าองค์ประกอบสีฟ้าของสี การแปลงสีทุกอย่างจะถูกละเลย อ่าน **uint8_t** |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | คืนค่าสีที่ได้ (โดยใช้การแปลงสีทั้งหมด) ตั้งค่าสี RGB และเคลียร์การแปลงสีทั้งหมด อ่าน [System::Drawing::Color](../../system.drawing/color/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | คืนการดำเนินการแปลงสีที่ใช้กับสีที่ตำแหน่งที่ระบุ อ่าน/เขียน [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | คืนคอลเลกชันของการแปลงสีที่ใช้กับสี อ่านอย่างเดียว [IColorOperationCollection](../icoloroperationcollection/) |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | คืนวิธีการกำหนดสี อ่าน [Slides::ColorType](../colortype/) |
| **float** [get_FloatB](./get_floatb/)() override | คืนค่าองค์ประกอบสีฟ้าของสี การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float** |
| **float** [get_FloatG](./get_floatg/)() override | คืนค่าองค์ประกอบสีเขียวของสี การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float** |
| **float** [get_FloatR](./get_floatr/)() override | คืนค่าองค์ประกอบสีแดงของสี การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float** |
| **uint8_t** [get_G](./get_g/)() override | คืนค่าองค์ประกอบสีเขียวของสี การแปลงสีทั้งหมดจะถูกละเลย |
| **float** [get_Hue](./get_hue/)() override | คืนค่าโทนสีของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float** |
| **float** [get_Luminance](./get_luminance/)() override | คืนค่าความสว่างของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float** |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | คืนอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว [IDOMObject](../idomobject/) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | คืนพาเรนท์ [IPresentationComponent](../ipresentationcomponent/) อ่านอย่างเดียว [IPresentationComponent](../ipresentationcomponent/) |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | คืนค่าพรีเซ็ตสี อ่าน [Slides::PresetColor](../presetcolor/) |
| **uint8_t** [get_R](./get_r/)() override | คืนค่าองค์ประกอบสีแดงของสี การแปลงสีทั้งหมดจะถูกละเลย อ่าน **uint8_t** |
| **float** [get_Saturation](./get_saturation/)() override | คืนค่าอัตราความอิ่มตัวของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย อ่าน **float** |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | คืนค่าสีที่ระบุโดยโทนสี อ่าน [Slides::SchemeColor](../schemecolor/) |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | คืนค่าสีที่ระบุโดยตารางสีของระบบ อ่าน [Slides::SystemColor](../systemcolor/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| **int32_t** [GetHashCode](./gethashcode/)() const override | คืนค่า hash code |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจ็กต์ การทำงานคล้ายกับคำเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType การทำงานคล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# ทำให้สามารถทำสำเนาชนิดที่กำหนดเองได้ |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้คอนสตรักเตอร์คัดลอกของซับคลาสทำงาน |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้คอนสตรักเตอร์คัดลอกของซับคลาสทำงาน |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงโดยค่าที่ระบุ |
| void [set_B](./set_b/)(**uint8_t**) override | ตั้งค่าองค์ประกอบสีฟ้าของสี การแปลงสีทั้งหมดจะถูกละเลย เขียน **uint8_t** |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | คืนค่าสีที่ได้ (โดยใช้การแปลงสีทั้งหมด) ตั้งค่าสี RGB และเคลียร์การแปลงสีทั้งหมด เขียน [System::Drawing::Color](../../system.drawing/color/) |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | ตั้งค่าการดำเนินการแปลงสีที่ใช้กับสีที่ตำแหน่งที่ระบุ อ่าน/เขียน [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | ตั้งค่าวิธีการกำหนดสี เขียน [Slides::ColorType](../colortype/) |
| void [set_FloatB](./set_floatb/)(**float**) override | ตั้งค่าองค์ประกอบสีฟ้าของสี การแปลงสีทั้งหมดจะถูกละเลย เขียน **float** |
| void [set_FloatG](./set_floatg/)(**float**) override | ตั้งค่าองค์ประกอบสีเขียวของสี การแปลงสีทั้งหมดจะถูกละเลย เขียน **float** |
| void [set_FloatR](./set_floatr/)(**float**) override | ตั้งค่าองค์ประกอบสีแดงของสี การแปลงสีทั้งหมดจะถูกละเลย เขียน **float** |
| void [set_G](./set_g/)(**uint8_t**) override | ตั้งค่าองค์ประกอบสีเขียวของสี การแปลงสีทั้งหมดจะถูกละเลย |
| void [set_Hue](./set_hue/)(**float**) override | ตั้งค่าโทนสีของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย เขียน **float** |
| void [set_Luminance](./set_luminance/)(**float**) override | ตั้งค่าความสว่างของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย เขียน **float** |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | ตั้งค่าพรีเซ็ตสี เขียน [Slides::PresetColor](../presetcolor/) |
| void [set_R](./set_r/)(**uint8_t**) override | ตั้งค่าองค์ประกอบสีแดงของสี การแปลงสีทั้งหมดจะถูกละเลย เขียน **uint8_t** |
| void [set_Saturation](./set_saturation/)(**float**) override | ตั้งค่าอัตราความอิ่มตัวของสีในรูปแบบ HSL การแปลงสีทั้งหมดจะถูกละเลย เขียน **float** |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | ตั้งค่าสีที่ระบุโดยโทนสี เขียน [Slides::SchemeColor](../schemecolor/) |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | ตั้งค่าสีที่ระบุโดยตารางสีของระบบ เขียน [Slides::SystemColor](../systemcolor/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) ช่วยให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | คืนค่า [System::String](../../system/string/) ที่แสดงรูปแบบสีปัจจุบัน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับ weak reference ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject/)
* คลาส [IColorFormat](../icolorformat/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)