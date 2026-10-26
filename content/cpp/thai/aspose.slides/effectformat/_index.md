---
title: EffectFormat
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงคุณสมบัติเอฟเฟกต์ของรูปร่าง.
type: docs
weight: 846
url: /th/aspose.slides/effectformat/
---
## EffectFormat คลาส

แทนคุณสมบัติของเอฟเฟกต์สำหรับรูปร่าง

```cpp
class EffectFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IEffectFormat
```

## Methods

| Method | Description |
| --- | --- |
| void [DisableBlurEffect](./disableblureffect/)() override | ปิดการทำงานของเอฟเฟกต์เบลอ |
| void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() override | ปิดการทำงานของเอฟเฟกต์การทับสีเต็ม |
| void [DisableGlowEffect](./disablegloweffect/)() override | ปิดการทำงานของเอฟเฟกต์เรืองแสง |
| void [DisableInnerShadowEffect](./disableinnershadoweffect/)() override | ปิดการทำงานของเอฟเฟกต์เงาใน |
| void [DisableOuterShadowEffect](./disableoutershadoweffect/)() override | ปิดการทำงานของเอฟเฟกต์เงานอก |
| void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() override | ปิดการทำงานของเอฟเฟกต์เงาที่กำหนดล่วงหน้า |
| void [DisableReflectionEffect](./disablereflectioneffect/)() override | ปิดการทำงานของเอฟเฟกต์การสะท้อน |
| void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() override | ปิดการทำงานของเอฟเฟกต์ขอบนิ่ม |
| void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() override | เปิดการทำงานของเอฟเฟกต์การทับสีเต็ม |
| void [EnableGlowEffect](./enablegloweffect/)() override | เปิดการทำงานของเอฟเฟกต์เรืองแสง |
| void [EnableInnerShadowEffect](./enableinnershadoweffect/)() override | เปิดการทำงานของเอฟเฟกต์เงาใน |
| void [EnableOuterShadowEffect](./enableoutershadoweffect/)() override | เปิดการทำงานของเอฟเฟกต์เงานอก |
| void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() override | เปิดการทำงานของเอฟเฟกต์เงาที่กำหนดล่วงหน้า |
| void [EnableReflectionEffect](./enablereflectioneffect/)() override | เปิดการทำงานของเอฟเฟกต์การสะท้อน |
| void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() override | เปิดการทำงานของเอฟเฟกต์ขอบนิ่ม |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมินติก C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ชนิดอ้างอิงในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# ที่ NaN สองค่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# ที่ NaN สองค่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() override | เอฟเฟกต์เบลอ อ่าน [Effects::IBlur](../../aspose.slides.effects/iblur/) |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() override | เอฟเฟกต์การทับสีเต็ม อ่าน [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/) |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() override | เอฟเฟกต์เรืองแสง อ่าน [Effects::IGlow](../../aspose.slides.effects/iglow/) |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() override | เงาใน อ่าน [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/) |
| **bool** [get_IsNoEffects](./get_isnoeffects/)() override | คืนค่า true หากเอฟเฟกต์ทั้งหมดถูกปิด (เช่นเดียวกับเมื่อสร้างใหม่, วัตถุ [EffectFormat](./) เริ่มต้น) อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() override | เงานอก อ่าน [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | คืนค่าอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว [IDOMObject](../idomobject/) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | คืนค่า parent [IPresentationComponent](../ipresentationcomponent/) อ่านอย่างเดียว [IPresentationComponent](../ipresentationcomponent/) |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() override | เงาที่กำหนดล่วงหน้า อ่าน [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/) |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() override | การสะท้อน อ่าน [Effects::IReflection](../../aspose.slides.effects/ireflection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() override | ขอบนิ่ม อ่าน [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() override | รับข้อมูลการจัดรูปแบบเอฟเฟกต์ที่มีผลด้วยการสืบทอดที่ใช้ |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | คืนค่า hash code |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ จำลองการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่ามีอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ จำลองตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | จำลองเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# เปิดใช้งานการสำเนาประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ |
| void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) override | เอฟเฟกต์เบลอ เขียน [Effects::IBlur](../../aspose.slides.effects/iblur/) |
| void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) override | เอฟเฟกต์การทับสีเต็ม เขียน [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/) |
| void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) override | เอฟเฟกต์เรืองแสง เขียน [Effects::IGlow](../../aspose.slides.effects/iglow/) |
| void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) override | เงาใน เขียน [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/) |
| void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) override | เงานอก เขียน [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/) |
| void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) override | เงาที่กำหนดล่วงหน้า เขียน [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/) |
| void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) override | การสะท้อน เขียน [Effects::IReflection](../../aspose.slides.effects/ireflection/) |
| void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) override | ขอบนิ่ม เขียน [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/) |
| void [SetBlurEffect](./setblureffect/)(**double**, **bool**) override | ตั้งค่าเอฟเฟกต์เบลอ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า argument แม่แบบที่ n เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับ pointer ใน container ไปเป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | จำลองเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามคำสั่ง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## See Also

* คลาส [PVIObject](../pviobject/)
* คลาส [IEffectFormat](../ieffectformat/)
* เนมส페ซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)