---
title: Effect
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของเอฟเฟกต์การแอนิเมชัน.
type: docs
weight: 118
url: /th/aspose.slides.animation/effect/
---
## คลาส Effect


Represents animation effect.

```cpp
class Effect : public Aspose::Slides::Animation::IEffect,
               public Aspose::Slides::IDOMObject
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบ floating point ของ C# ที่ถือว่า NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบ floating point ของ C# ที่ถือว่า NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() override | กำหนดสีหลังการแอนิเมชันสำหรับเอฟเฟกต์. อ่าน [IColorFormat](../../aspose.slides/icolorformat/). |
| [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() override | กำหนดประเภทหลังการแอนิเมชันสำหรับเอฟเฟ็กต์. อ่าน [AfterAnimationType](../afteranimationtype/). |
| [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() override | กำหนดประเภทการแอนิเมตข้อความสำหรับเอฟเฟ็กต์. ข้อความของรูปทรงสามารถแอนิเมตได้ตามอักษร, ตามคำ หรือทั้งหมดพร้อมกัน. อ่าน [AnimateTextType](../animatetexttype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) override | ส่งกลับพฤติกรรมการแอนิเมชันที่ตำแหน่งที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() override | ส่งกลับคอลเลกชันของพฤติกรรมสำหรับเอฟเฟกต์. อ่าน [IBehaviorCollection](../ibehaviorcollection/). |
| **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() override | กำหนดความหน่วงระหว่างส่วนของข้อความที่แอนิเมต (คำหรืออักษร). ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์. ค่าลบระบุความหน่วงเป็นวินาที. อ่าน **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [get_Effect](./get_effect/)(**int32_t**) override | ส่งกลับผลของลำดับที่ตำแหน่งที่ระบุ. |
| [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() override | กำหนดคลาสของเอฟเฟกต์. อ่าน [EffectPresetClassType](../effectpresetclasstype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() override | ส่งกลับลำดับสำหรับเอฟเฟกต์. อ่านอย่างเดียว [ISequence](../isequence/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | กำหนดเสียงฝังในเอฟเฟกต์. อ่าน [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_StopPreviousSound](./get_stopprevioussound/)() override | แอตทริบิวต์นี้ระบุว่าผลกระทบแอนิเมชันหยุดเสียงก่อนหน้าหรือไม่. อ่าน **bool**. |
| [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() override | กำหนดชนิดย่อยของเอฟเฟกต์. อ่าน [EffectSubtype](../effectsubtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() override | ส่งกลับรูปทรงเป้าหมายสำหรับเอฟเฟกต์. อ่านอย่างเดียว [IShape](../../aspose.slides/ishape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() override | [TextAnimation](../textanimation/) อ่านอย่างเดียว [ITextAnimation](../itextanimation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() override | กำหนดค่าการจับเวลาสำหรับเอฟเฟกต์. อ่าน [ITiming](../itiming/). |
| [EffectType](../effecttype/) [get_Type](./get_type/)() override | กำหนดประเภทของเอฟเฟกต์. อ่าน [EffectType](../effecttype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาชนิดที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | กำหนดสีหลังการแอนิเมชันสำหรับเอฟเฟ็กต์. เขียน [IColorFormat](../../aspose.slides/icolorformat/). |
| void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) override | กำหนดประเภทหลังการแอนิเมชันสำหรับเอฟเฟ็กต์. เขียน [AfterAnimationType](../afteranimationtype/). |
| void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) override | กำหนดประเภทการแอนิเมตข้อความสำหรับเอฟเฟ็กต์. ข้อความของรูปทรงสามารถแอนิเมตตามอักษร, คำ หรือทั้งหมดพร้อมกัน. เขียน [AnimateTextType](../animatetexttype/). |
| void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) override | ตั้งค่าพฤติกรรมการแอนิเมชันที่ตำแหน่งที่ระบุ. |
| void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) override | ส่งกลับคอลเลกชันของพฤติกรรมสำหรับเอฟเฟกต์. เขียน [IBehaviorCollection](../ibehaviorcollection/). |
| void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) override | กำหนดความหน่วงระหว่างส่วนของข้อความที่แอนิเมต (คำหรืออักษร). ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์. ค่าลบระบุความหน่วงเป็นวินาที. เขียน **float**. |
| void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) override | กำหนดคลาสของเอฟเฟ็กต์. เขียน [EffectPresetClassType](../effectpresetclasstype/). |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | กำหนดเสียงฝังในเอฟเฟ็กต์. เขียน [IAudio](../../aspose.slides/iaudio/). |
| void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) override | แอตทริบิวต์นี้ระบุว่าผลกระทบแอนิเมชันหยุดเสียงก่อนหน้าหรือไม่. เขียน **bool**. |
| void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) override | กำหนดชนิดย่อยของเอฟเฟ็กต์. เขียน [EffectSubtype](../effectsubtype/). |
| void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | กำหนดค่าการจับเวลาสำหรับเอฟเฟ็กต์. เขียน [ITiming](../itiming/). |
| void [set_Type](./set_type/)([EffectType](../effecttype/)) override | กำหนดประเภทของเอฟเฟ็กต์. เขียน [EffectType](../effecttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเท็มเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IEffect](../ieffect/)
* คลาส [IDOMObject](../../aspose.slides/idomobject/)
* เนมสเปซ [Aspose::Slides::Animation](../)
* ไลบรารี [Aspose.Slides](../../)