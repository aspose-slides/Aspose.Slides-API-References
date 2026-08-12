---
title: IEffect
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทนค่าเอฟเฟกต์การแอนิเมชัน.
type: docs
weight: 248
url: /th/aspose.slides.animation/ieffect/
---
## คลาส IEffect

อธิบายถึงเอฟเฟกต์แอนิเมชัน

```cpp
class IEffect : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() | กำหนดสีหลังการแอนิเมชันสำหรับเอฟเฟกต์ อ่าน [IColorFormat](../../aspose.slides/icolorformat/) |
| virtual [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() | กำหนดประเภทหลังการแอนิเมชันสำหรับเอฟเฟกต์ อ่าน [AfterAnimationType](../afteranimationtype/) |
| virtual [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() | กำหนดประเภทการแอนิเมทข้อความสำหรับเอฟเฟกต์ ข้อความในรูปร่างสามารถแอนิเมทตามตัวอักษร, ตามคำ หรือทั้งหมดพร้อมกัน อ่าน [AnimateTextType](../animatetexttype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) | คืนค่าพฤติกรรมการแอนิเมชันที่ตำแหน่งดัชนีที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() | คืนค่าการรวมของพฤติกรรมสำหรับเอฟเฟกต์ อ่าน [IBehaviorCollection](../ibehaviorcollection/) |
| virtual **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() | กำหนดความหน่วงระหว่างส่วนของข้อความที่แอนิเมท (คำหรืออักษร) ค่าเป็นบวกระบุเป็นเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์ ค่าเป็นลบระบุเป็นวินาที อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffect](./)\> [get_Effect](./get_effect/)(**int32_t**) | คืนค่าผลกระทบของลำดับที่ตำแหน่งดัชนีที่ระบุ |
| virtual [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() | กำหนดคลาสของเอฟเฟกต์ อ่าน [EffectPresetClassType](../effectpresetclasstype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() | คืนค่าลำดับสำหรับเอฟเฟกต์ อ่านอย่างเดียว [ISequence](../isequence/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() | กำหนดเสียงฝังอยู่สำหรับเอฟเฟกต์ อ่าน [IAudio](../../aspose.slides/iaudio/) |
| virtual **bool** [get_StopPreviousSound](./get_stopprevioussound/)() | แอตทริบิวต์นี้ระบุว่าการแอนิเมชันหยุดเสียงก่อนหน้า อ่าน **bool** |
| virtual [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() | กำหนดชนิดย่อยของเอฟเฟกต์ อ่าน [EffectSubtype](../effectsubtype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() | คืนค่า รูปร่างเป้าหมายสำหรับเอฟเฟกต์ อ่านอย่างเดียว [IShape](../../aspose.slides/ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() | คืนค่าการแอนิเมชันข้อความ อ่านอย่างเดียว [ITextAnimation](../itextanimation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() | กำหนดค่าเวลาในการทำงานของเอฟเฟกต์ อ่าน [ITiming](../itiming/) |
| virtual [EffectType](../effecttype/) [get_Type](./get_type/)() | กำหนดประเภทของเอฟเฟกต์ อ่าน [EffectType](../effecttype/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ อนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ระบุโดย targetType อนาล็อกของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนนิ่งของประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมตามค่าที่ระบุ |
| virtual void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) | กำหนดสีหลังการแอนิเมชันสำหรับเอฟเฟกต์ เขียน [IColorFormat](../../aspose.slides/icolorformat/) |
| virtual void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) | กำหนดประเภทหลังการแอนิเมชันสำหรับเอฟเฟกต์ เขียน [AfterAnimationType](../afteranimationtype/) |
| virtual void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) | กำหนดประเภทการแอนิเมทข้อความสำหรับเอฟเฟกต์ ข้อความในรูปร่างสามารถแอนิเมทตามตัวอักษร, ตามคำ หรือทั้งหมดพร้อมกัน เขียน [AnimateTextType](../animatetexttype/) |
| virtual void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) | ตั้งค่าพฤติกรรมการแอนิเมชันที่ตำแหน่งดัชนีที่ระบุ |
| virtual void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) | คืนค่าการรวมของพฤติกรรมสำหรับเอฟเฟกต์ เขียน [IBehaviorCollection](../ibehaviorcollection/) |
| virtual void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) | กำหนดความหน่วงระหว่างส่วนของข้อความที่แอนิเมท (คำหรืออักษร) ค่าเป็นบวกระบุเป็นเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์ ค่าเป็นลบระบุเป็นวินาที เขียน **float** |
| virtual void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) | กำหนดคลาสของเอฟเฟกต์ เขียน [EffectPresetClassType](../effectpresetclasstype/) |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) | กำหนดเสียงฝังอยู่สำหรับเอฟเฟกต์ เขียน [IAudio](../../aspose.slides/iaudio/) |
| virtual void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) | แอตทริบิวต์นี้ระบุว่าการแอนิเมชันหยุดเสียงก่อนหน้า เขียน **bool** |
| virtual void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) | กำหนดชนิดย่อยของเอฟเฟกต์ เขียน [EffectSubtype](../effectsubtype/) |
| virtual void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | กำหนดค่าเวลาในการทำงานของเอฟเฟกต์ เขียน [ITiming](../itiming/) |
| virtual void [set_Type](./set_type/)([EffectType](../effecttype/)) | กำหนดประเภทของเอฟเฟกต์ เขียน [EffectType](../effecttype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่ามัน ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ คืนโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides::Animation](../)
* ไลบรารี [Aspose.Slides](../../)